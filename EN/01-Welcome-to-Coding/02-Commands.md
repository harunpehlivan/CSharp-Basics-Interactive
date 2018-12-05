[slide]

# Commands

**Commands** tell the computer to execute a single action, e.g. print something, read a value or perform a calculation.

Let's start learning about writing commands from a **simple C# command**:
```cs
Console.WriteLine("I am coding");
```

The above command **prints given text** at the standard program output (the system console). It tells the `Console` object: please **write a line**, holding the text "_I am coding_".

The above command prints the following **output**:
```
I am coding
```

Run the above command using the [**Run**] button. Modify it, play with it.

Another example of a command is to **calculate an expression** and print teh result:
```cs
Console.WriteLine(5 + 5);
```

**Run** the above command, modify it, play with it.

The above command prints as **output** the result of the above calculation `5 + 5`:
```
10
```

## Incorrect Commands

Commands in C# are **case-sensitive**, which means that `WriteLine` is different than `writeline`. Commands in C# should end with `;` at the end, otherwise an error is shown. Not all verbs are valid commands. Follow the logic of the above examples to write valid commands.

All of the below examples are **incorrect C# commands**:
```cs
console.WriteLine("Type 'Console' with capital 'C' at the start");
```
```cs
Console.Writeline("Type 'WriteLine' with capital 'L'");
```
```cs
Console.WriteLine("Put `;` at the end of each command")
```
```cs
WriteLine("Missing 'Console.' before 'WriteLine'")
```
```cs
Coffee.CreateNew("Unknown class or object: 'Coffee'")
```
```cs
Console.WriteLine(Missing quotes);
```
```cs
Console.WriteLine("Missing closing bracket";
```

[/slide]


[slide]
# Exercises: Simple Commands

Now it is your turn to write a **simple commands** in C#. You will print text messages and will calculate and print the value of simple expressions.

# Exercise: Print "Hello World!"

[code-task title="Print Hello World" executionStrategy="csharp-dot-net-core-code"]

Write a command to print the message "**_Hello World!_**" at the console.

[code-editor language=csharp]
Console.WriteLine("");
[/code-editor]

**Modify the above code** to complete the exercise and submit your solution to check whether it is correct.

[/code-task]


# Exercise: Calculate and Print 5 * 5

[code-task title="Print 5 * 5" executionStrategy="csharp-dot-net-core-code"]

Write a command to calculate and print the expression `5 * 5`.

[code-editor language=csharp]
[/code-editor]

**Write the missing command** to complete the exercise and submit your solution to check whether it is correct.

[/code-task]

[/slide]
