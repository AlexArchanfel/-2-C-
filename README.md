// Задача 2. Напишите программу, которая на вход принимает два числа и выдает, какое число большее, а какое меньшее.]

Console.WriteLine("Введите первое число ");
int x = int.Parse(Console.ReadLine()!);
Console.WriteLine("Введите второе число ");
int y = int.Parse(Console.ReadLine()!);

if (x > y)
{
    Console.WriteLine($"Максимальное число {x}, минимальное число {y}");
}else
{
    Console.WriteLine($"Максимальное число {y}, минимальное число {x}");
}
