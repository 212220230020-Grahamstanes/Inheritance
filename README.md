### EX NO : 08
### DATE  : 01.06.2022
# <p align="center">Inheritance</p>

## Aim:
To write a C# program to print some messages using hierarchical inheritance.
## Algorithm:
### step 1: 
Create a base class.

### step 2:
Create two child class.

### step 3:
Create a constructor in the base class and print a message.

### step 4:
create a function in child class to print a message.

<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
## Program:
```c#
using System;
namespace fawzi{
    public class vehicle
    {
        public vehicle()
        {
            Console.Write("tyre is attached");
        }

    }
    public class car : vehicle
    {
        public void display()
        {
            Console.Write(" to car");
        }
    }
    public class scooter : vehicle
    {
        public void display()
        {
            Console.Write(" to scooter");
        }
    }
    public class program{
        public static void Main(string[] args)
        {
            car car = new car();
            car.display();
            Console.WriteLine();
            scooter scooter = new scooter();
            scooter.display();
            Console.ReadKey();
        }
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/75235488/172887578-8084f80a-4634-40dc-9ec2-04761992270a.png)

## Result
C# program to print some messages using hierarchical inheritance is implemented successfully.
