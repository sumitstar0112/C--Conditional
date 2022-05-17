<!-- C#--Conditional
Conditional Statements -->

namespace Conditional_Loops
{
    internal class Program
    {
        static void Main(string[] args)
        {
            /*//Conditional Statements - If statement. 
            int x = 20, y = 15;
            if (x >= 15)
            {
                Console.WriteLine("x is greater than 15");
            }
            if (y <= 10)
            {
                Console.WriteLine("y is less than 10");
            }
            Console.WriteLine("Press enter key to exit..");
            Console.Read();*/

            Console.Write("Enter First Number : ");
            int x = Convert.ToInt32( Console.ReadLine());
           
            Console.WriteLine("Enter Second Number : ");
            int y = Convert.ToInt32(Console.ReadLine());

            Console.WriteLine("Enter Second Number : ");
            int z = Convert.ToInt32(Console.ReadLine());

            /* if (x > y)
             {
                 Console.WriteLine("{0} is greater than {1}",x,y);
             }
             else
             {
                 Console.WriteLine("{0} is less than {1}",x,y);
             }*/

            /* if(x>y && x>z)
             {
                 Console.WriteLine("{0} is greater than {1} and {2}", x, y, z);
             }
             else if(y>z)
             {
                 Console.WriteLine("{1} is greater than {0} and {2}", x, y, z);
             }
             else
                 Console.WriteLine("{2} is greater than {0} and {1}", x, y, z);

             Console.WriteLine("Press enter key to exit..");
             Console.Read();*/

            Console.WriteLine();

            //Ternary Operator (?:)
            //It is a decision making operator, it is a substitute of if-else statement.
            // (condition / expression) ? (if condition satisfied than this expression will execute) : (if condition is not satisfied than this second expression will execute)

            string result = (x > y && x > z) ? "First number is greatest" : (y > z) ? "Second number is greatest" : "Third number is greatest";
            Console.WriteLine(result);

            Console.WriteLine("Press enter key to exit..");
            Console.Read();
        }
    }
}

   
