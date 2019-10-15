# 1
namespace Rextester
{
    public class Program
    {
        public static void Main(string[] args)
        {
            Console.WriteLine("введите число") ;
            int n=Int32.Parse(Console.ReadLine ()) ;
            if (n >=0) 
{
int a;
a = n - 50;
Console.WriteLine (a);
Console.ReadKey();
}
if (n<0) 
{
int b;
b = n + 100;
Console.WriteLine (b);
Console.ReadKey();
}
        }
    }
}
