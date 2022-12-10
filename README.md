# -ehir-plaka-uygulamas-
plakayı yazınca ilgili şehir çıkıyor


namespace PROJE;
class Program
{
    static void Main(string[] args)
    {
        int plaka;
        Console.WriteLine();
        plaka = Convert.ToInt16(Console.ReadLine());

        switch(plaka)
        {
            case 1: Console.WriteLine("Merhaba Adana"); 
               break;
            case 2: Console.WriteLine("Merhaba Adıyaman"); 
               break;
            case 3: Console.WriteLine("Merhaba Giresun");
               break;
            default: Console.WriteLine("Henüz bu şehir bilgisi girilmedi!");
               break;


        }
            Console.Read();

    }
}
