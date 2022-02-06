# PrograminginCSharpCourse
namespace ConsoleApp2
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Salam");
            Console.WriteLine("Zehmet olmasa birinci ededi daxil edin");
            int var1;
            while(true)
            {
                try
                {
                    var1 = int.Parse(Console.ReadLine());
                    break;

                }
                catch (Exception exc)
                {
                    Console.WriteLine("Ancaq eded daxil ede bilersiniz");
                    


                }
            


               
            }
            

            
            
            Console.WriteLine("Zehmet olmasa ikinci ededi daxil edin");
            int var2;

            while (true)
            {
                try
                {
                    var2 = int.Parse(Console.ReadLine());
                    break;

                }
                catch (Exception exc)
                {
                    Console.WriteLine("Ancaq eded daxil ede bilersiniz");



                }




            }
            Console.WriteLine("Zehmet olmasa ucuncu ededi daxil edin");
            int var3;

            while (true)
            {
                try
                {
                    var3 = int.Parse(Console.ReadLine());
                    break;

                }
                catch (Exception exc)
                {
                    Console.WriteLine("Ancaq eded daxil ede bilersiniz");



                }




            }
            Console.WriteLine("Zehmet olmasa dorduncu ededi daxil edin");
            int var4;

            while (true)
            {
                try
                {
                    var4 = int.Parse(Console.ReadLine());
                    break;

                }
                catch (Exception exc)
                {
                    Console.WriteLine("Ancaq eded daxil ede bilersiniz");



                }




            }






            int sum = Sum(var1, var2, var3, var4);
            Console.WriteLine("Cemi:" + sum);
            Console.WriteLine("Bizden yararlandiginiz  ucun tesekkurler");




        }

        public static int Sum(int var1, int var2 , int var3 , int var4)
        {
            return var1 + var2 + var3 + var4;
        }
       
        

        private static void Main2(string[] args)
        {



            Console.WriteLine("Hello World!");
        }


    }
}
