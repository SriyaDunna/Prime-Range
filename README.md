# Prime-Range
import java.util.*;
public class Prime
{
    public static void main(String args[])
    {
    int i,j,n,flag;
    {
        Scanner s = new Scanner(System.in);
        System.out.println("Enter the range");
        n=s.nextInt();
    }
        for(i=2;i<n;i++)
        {
            flag=1;
            for(j=2;j<1;j++)
            {
                if(i%j==0)
                {
                    flag=0;
                    break;
                }
            }
            if(flag==1)
            System.out.println(i+"\t");
        }
    }
}
