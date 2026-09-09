// Liczba losowa

Console.WriteLine($"Program służący do zgadywania liczb");

Random r = new Random();
int losowa = r.Next(100);
int twojaliczba = -1;
while (twojaliczba != losowa)
{
    twojaliczba = int.Parse(Console.ReadLine());

    if (twojaliczba < losowa)
    {
        Console.WriteLine($"Twoja liczba jest mniejsza od liczby losowej");
    }
    else if (twojaliczba > losowa)
    {
        Console.WriteLine($"Twoja liczba jest większa od liczby losowej");
    }
    else if (twojaliczba == losowa)
    {
        Console.WriteLine($"Twoja liczba jest równa liczbie losowej");
    }
}
