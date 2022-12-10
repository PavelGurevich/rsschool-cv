# Pavel Gurevich

## Contacts

**Phone:** 
****

## About me

I want to become a great web developer.
My personal qualities:
*I'm great at combining practice and theory
*Targetful
*Nice dude
****

## Skills
        *C# - basic
        *Java - basic
        *C++ - intermediate
        *Git
****

## Code example

````
double a, b, c = 0;
bool calc = true;
string sym;
Console.WriteLine("Простейший калькулятор");
Console.WriteLine("Выполняет арифметические операции + - / *");
do
{
    Console.WriteLine("Введите первое число:");
    a = double.Parse(Console.ReadLine());
    Console.WriteLine("Введите символ операции (+ или - или / или *): ");
    sym = Console.ReadLine();
    Console.WriteLine("Введите второе число:");
    b = double.Parse(Console.ReadLine());
    if (a == 0 & b == 0)
    {
        Console.WriteLine("Завершение работы ");
        break;
    }

    switch (sym)
    {
        case "+": c = a + b; Console.WriteLine("{0} {1} {2} = {3}", a, sym, b, c); break;
        case "-": c = a - b; Console.WriteLine("{0} {1} {2} = {3}", a, sym, b, c); break;
        case "*": c = a * b; Console.WriteLine("{0} {1} {2} = {3}", a, sym, b, c); break;
        case "/": c = a / b; Console.WriteLine("{0} {1} {2} = {3}", a, sym, b, c); break;
        default:
            Console.WriteLine("Некорректный символ операции");
            calc = false;
            break;
    }

}
while (calc == true);
Console.WriteLine("Программа завершена");
````
****

## Education
Francisk Skorina Gomel State University
****
