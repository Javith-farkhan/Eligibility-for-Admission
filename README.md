# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:
step 1 :
Import the 'System' namespace to use the classes present in the 'System' namespace.

step 2:
Declare the Main method.

step 3:
Declare name variable in string format and marks variable in integer format.

step 4:
Using " Console.Write " print the statement and get the input from user using " Console.ReadLine " .

step 5:
Add the 3 subject marks and store it in tot1. Add the marks of physics and maths and store it in tot2.

step 6:
Using Nested if loop check whether the student is eligible or not eligible for engineering admission with the conditions given.

step 7:
print the result

## Program:
```
using System;
namespace exp1
{
    class experiment
    {
        static void Main(string[] args)
        {
            int physics_mark, maths_mark, chemistry_mark, total;
            Console.WriteLine("Enter the mark in Physics");
            physics_mark=Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter the mark in maths:");
            maths_mark=Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter the mark in Chemistry:");
            chemistry_mark=Convert.ToInt32(Console.ReadLine());
            if(maths_mark>=65 && physics_mark>=55 && chemistry_mark>=50)
            {
                total = maths_mark + physics_mark + chemistry_mark;
                if(total>=180 || (maths_mark+physics_mark>=140))
                {
                    Console.WriteLine("Student is eligible for the admission");
                }
                
            }
            else
            {
                Console.WriteLine("Student is not eligible for the admission");
            }
        }
    }
}

```


## Output:
![c#1](https://github.com/Guru-Guna/Eligibility-for-Admission/assets/93427255/52828f09-b407-4d71-af0f-96f5f811470a)


## Result:
Thus a C# program to find the eligibility for admission to an engineering course is written and executed.
