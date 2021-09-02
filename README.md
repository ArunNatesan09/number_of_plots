class pefectnumber {
	public static void main(String[] args)
	{
	Scanner sc=new Scanner(System.in);
	int a=sc.nextInt();
	int[] arr=new int[a];
	int count=0;
	for(int i=0;i<arr.length;i++)
	{
		arr[i]=sc.nextInt();
		
	}
	for(int i=0;i<arr.length;i++)
	{
		for(int j=2;j<arr[i];j++)
		{
			if(arr[i]%1==0 && (j*j)==arr[i])
			{
				count++;
			}
			else
			{
				continue;
			}
		}
	}
     System.out.println(count);
	}
}


// to find the perfect square in the given array 
//8
//79 77 54 81 48 34 25 16
//3


//8
//16 25 81 4 9 36 100 49
//8
