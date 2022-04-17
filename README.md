# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:

### Step1:
Start.

### Step2:
Create a class and declare the variable with string datatype.

### Step3:
Get the string from the user and store the string in the value variable.

### Step4:
Store the value data to another variable and use the for loop function to check the condition.

### Step5:
Use if - else condition to print that the given string is palindrome or not.

### Step6:
stop.

## Program:
```python

using System;
class HelloWorld
{
    static void Main()
    {
        string value, dupvalue, rev = "";
        Console.WriteLine("Enter the string");  
        value = Console.ReadLine();
        dupvalue = value;
        for (int s = value.Length - 1; s >= 0; s--)
        {
            rev += value[s];
        }
        if (rev == dupvalue)
            Console.WriteLine(dupvalue + " is a palindrome");
        else
            Console.WriteLine(dupvalue + " is not a palindrome");
    }
}

```

## Output:

<img width="674" alt="image" src="https://user-images.githubusercontent.com/75235554/163707307-5eb102ea-0c6b-4614-9157-309f0a9cbd6d.png">


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
