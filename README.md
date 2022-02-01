# ArraySorting
public class Main
{
	public static void main(String[] args) {
		int A[] = {8,2,3,1,6};
		int n = 5;
		int count = 0;
		while(count<=3)
		{
		    for(int i=0;i<n-1;i++)
		    {
		        if(A[i]>A[i+1])
		        {
		            int temp = A[i];
		            A[i] = A[i+1];
		            A[i+1] = temp;
		        }
		        
		    }
		      count++;
		}
		
		for(int i=0;i<n;i++)
		{
		    System.out.println(A[i]);
		}
		
	}
}
