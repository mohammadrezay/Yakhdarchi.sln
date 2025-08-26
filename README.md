# Yakhdarchi.sln

- **Link:** [Quera Problem #3429](https://quera.org/problemset/3429)
- **Description:** Given an integer **T** (water temperature in a samovar), print "Steam" if **T** > 100, "Ice" if **T** < 0, or "Water" otherwise.
- **Solution:** Implemented in C#.

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
