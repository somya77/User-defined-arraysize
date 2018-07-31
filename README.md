# User-defined-arraysize
Here user can define the array length. And the array length is displayed on the screen.
import java.util.Scanner;
class Test11
{
 public static void main(String args[])
{
 Scanner obj=new Scanner(System.in);
System.out.println("Enter the number of elements");
 int n=obj.nextInt(); 
int num[]=new int[n];
System.out.println("Enter the elements");
for(int i=0;i<n;i++)
{
  num[i]=obj.nextInt();
}
System.out.println("Entered number is:");
for(int i=0;i<n;i++)
{
System.out.println(num[i]);
}
System.out.println(num.length);
}
}
