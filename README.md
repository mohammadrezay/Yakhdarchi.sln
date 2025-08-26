# Yakhdarchi.sln

namespace yakhDarchi
{
    internal class Program
    {
        static void Main(string[] args)
        {
            //Console.WriteLine("Enter a number:");
            int T = Convert.ToInt32(Console.ReadLine());
            if (T > 100)
            {
                Console.WriteLine("Steam");
            }
            else if (T < 0  )
            {
                Console.WriteLine("Ice");
            }
            else
            {
                Console.WriteLine("Water");
            }
        }
    }
}
