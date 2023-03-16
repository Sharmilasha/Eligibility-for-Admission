# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:
Step1: Start by creating a new class.

Step2: Initiate the integer variables to assign the marks of Maths, Physics and Chemistry and a string variable to assign the name of the student; read the input from the user.

Step3: Calculate the first total that sums all the 3 subject marks; and the second total that sums maths and physics marks.

Step4: Based on the condition given, check whether the student is eligible for the engineering admission.

Step5: Display the output for the input read from the user.

Step6: Stop the execution.

## Program:
Developed by : sharmila .A Register Number : 212221230094
using System;

public class ConsoleApp1
{
    public static void Main(string[] args)
    {
        int p, c, m, tot1, tot2;
        string name;
        Console.WriteLine("Enter the Physics mark:");
        p= Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter the chemistry mark:");
        c = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter the maths mark:");
        m = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter a Name of the student");
        name = Console.ReadLine();
        tot1 = p + c + m;
        tot2 = p + m;
        if (p >= 55 && c >= 50 && m >= 65)
        {
            if (tot1 >= 180 || tot2 >= 140)
            {
                Console.WriteLine("{0} is eligible for engineering admission", name);
            }
            else
            {
                Console.WriteLine(name + " is not eligible for engineering admission");

            }
        }
        else
        {
            Console.WriteLine("{0} is not eligible for engineering admission", name);
        }

    }
}






## Output:





## Result:
