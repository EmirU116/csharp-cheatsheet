# CSharp Cheat Sheet Template

Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
`;`     | Used to separate statements from each other.| `int i = 5; i++; Console.WriteLine(i);` | [Script Execution](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#0-script-execution)
`//`    | Used for single-line comments              | `float multiplier = 0.01f; // % to float (e.g. 24% = 0.24)` | [Comments](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#single-line-comments)
Variable Initialization | When a value is assigned to a variable for the first time | `int a = 5;` | [Variables](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#variable-initialization)
`dotnet new console -o project-name` | Create a new project | `dotnet new console -o name` | [Dotnet](https://github.com/marczaku/csharp-basics/blob/main/slides/003.1-hello-world.md#1-create-a-project)
Script Execution Order | It executes the script from top to bottom | `Starts Script from ↑ Goes ↓`| [Execution order](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#0-script-execution)
Formatting | String Method:You can put variable in the string without using + | `Console.writeline($"text");` | [Formatting](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
`Console.WriteLine` | Prints out data | `Console.WriteLine();` | [Print](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#1-printing-output)
`Console.Write` | Prints out data like WriteLine but the diffrence is, is that WriteLine prints under each other, Write prints on the same row | `Console.Write();` | [Print](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#1-printing-output)
Multi-Line Comment | If you need to type a large comment | `/* and */`| [Comment](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#2-comments)
XML Documentation Comment | The API is getting docummented in XML | `///` | [Comment](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#2-comments)
Variable | Store data | `int a = 5;` | [Varible](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#3-variables)
Variable Declaration | Used to store data | `ìnt a;` |  [Variable](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#variable-declaration)
Variable Assignment | Gives variables data | `=` | [Variable](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#variable-assignment)
Uninitialized Variable | When variable is not assigned and you call it, its going to be uninitialized | `Error` | [Variable](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#variable-initialization)
`=` (Assignment Operator) | "=" assign data to the variable | `=` | [Variable](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#variable-initialization)
Scope | Where you put your code | `{}` | [Scope](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#31-scope)
Variable Scope | Variable should be inside the scope | `{var}`| [Variable Scope](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#variable-scope)
`int` | Full number | `int a = 5;` | [Basic Data Type](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`float` | Decimal numbers | `float a = 5.53F;` | [Basic Data Type](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`double` | More precise fractionals | `double name = 24e-10;` | [Basic Data Type](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`bool` | true or false variable | `bool a = true;` | [Basic Data Type](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`char` | A single Charater | `char chr = "@"` | [Basic Data Type](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`string` | String is text | `string a = "Hello";` | [Basic Data Type](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`byte` | ? | ? | [Basic Data Type](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
Implicit Casting | Small numbers to big | `Idk honestly` | [Conversion](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#5-conversion)
Explicit Casting | Big numbers to small | `Idk honestly`| [Conversion](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#5-conversion)
Type Conversion | ? | ? | ?
`Convert.ToInt32` | This converts variables to integer | `Convert.Toint32` | [Conversion](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#5-conversion)
Operators | Functions that are presented by symbols, they executes operation and return the result | `number /= 2;number *= 5;number -= 3;number %= 9;` | [Operator](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
Arithmetic Operators | Is for Mathimatical operations | `int e = 5 + 5;` | [Operator](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`+` | This adds togheter | `+` | [Operator](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`-` | This substracts | `-` | [Operator](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`*` | This mulieplies | `*` | [Operator](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`/` | This divides | `/` | [Operator](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`%` | This Returns after divided | `%` | [Operator](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`+=` | This adds and returns result | `+=` | [Operator](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`-=` | This substracts and return result | `-=` | [Operator](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`++` | This adds | `i++` | [Operator](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`--` | This substracts | `i--` | [Operator](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
Post-Increment `i++` | the value is increased by 1, but the value used is still the old one | `i++` | [Operator](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
Pre-Increment `++i` | the value is increased by 1 and then the already increased value is used. | `++i` | [Operator](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`System.Math` | Its a math class | `System.Math` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`static` | Its a class | `static` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Max` | Its a function that finds the biggest number | `Math.Max(2, 5);` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Min` | Its a function that finds the lowest number | `Math.Min(2, 5);` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Sqrt` | ? | ? | ?
`Math.Abs` | ? | ? | ?
`Math.Round` | ? | ? | ?
`Math.Floor` | ? | ? | ?
`Math.Ceiling` | ? | ? | ?
`Math.Clamp` | ? | ? | ?
`Math.Pow` | ? | ? | ?
`string.Length` | ? | ? | ?
`string.ToUpper` | ? | ? | ?
`string.+` | ? | ? | ?
`$"{}"` | ? | ? | ?
`string.[]` | ? | ? | ?
`string.IndexOf` | ? | ? | ?
`string.SubString(int)` | ? | ? | ?
`string.Substring(int, int)` | ? | ? | ?
`string.Replace` | ? | ? | ?
immutable | ? | ? | ?
Logical Operators | ? | ? | ?
`!` | ? | ? | ?
`&&` | ? | ? | ?
`||` | ? | ? | ?
Comparison Operators | ? | ? | ?
`>` | ? | ? | ?
`==` | ? | ? | ?
`!=` | ? | ? | ?
`||` | ? | ? | ?
`>=` | ? | ? | ?
`<=` | ? | ? | ?
`if` | ? | ? | ?
`else` | ? | ? | ?
`else if` | ? | ? | ?
`? :` | ? | ? | ?
Flow Control Statements | ? | ? | ?
`System.Random` | ? | ? | ?
pseudo-random | ? | ? | ?
seed | ? | ? | ?
`Random.Next(int, int)` | ? | ? | ?
`Random.Next()` | ? | ? | ?
`Random.NextDouble()` | ? | ? | ?
`Random.Next()` | ? | ? | ?
`while` | ? | ? | ?
bool-expression | ? | ? | ?
`do..while` | ? | ? | ?
`for` | ? | ? | ?
iteration statement | ? | ? | ?
loop body | ? | ? | ?
loop | ? | ? | ?
execution | ? | ? | ?
execution jump | ? | ? | ?
`break` | ? | ? | ?
`continue` | ? | ? | ?
`Array` | ? | ? | ?
`int[]` | ? | ? | ?
Array Initialization | ? | ? | ?
Array Access for Assignment | ? | ? | ?
Array Access for Reading | ? | ? | ?
`Array.Resize` | ? | ? | ?
`Array.Length` | ? | ? | ?
`foreach` | ? | ? | ?
`2D-Array` | ? | ? | ?
2D-Array Initialization | ? | ? | ?
2D-Array Access for Assignment | ? | ? | ?
2D-Array Access for Reading | ? | ? | ?
Jagged Arrays | ? | ? | ?
Method | ? | ? | ?
`void` | ? | ? | ?
Return Type | ? | ? | ?
`()` | ? | ? | ?
Parameter | ? | ? | ?
Argument | ? | ? | ?
Parameter | ? | ? | ?
Parameter-List | ? | ? | ?
Named Arguments | ? | ? | ?
Optional Arguments | ? | ? | ?
Default Value | ? | ? | ?
`return` | ? | ? | ?
Code Paths | ? | ? | ?
Method Overloading | ? | ? | ?
Object-Oriented Programming | ? | ? | ?
Data | ? | ? | ?
Function | ? | ? | ?
Structured Programming | ? | ? | ?
Objects | ? | ? | ?
Instance Method | ? | ? | ?
Class | ? | ? | ?
Type | ? | ? | ?
`class` | ? | ? | ?
`new` | ? | ? | ?
Class Member | ? | ? | ?
Class Instance | ? | ? | ?
Garbage Collector | ? | ? | ?
`null` | ? | ? | ?
Invoke | ? | ? | ?
Field | ? | ? | ?
Static Class Member | ? | ? | ?
Static Class | ? | ? | ?
Global Access | ? | ? | ?
Constructor | ? | ? | ?
Initial Class Values | ? | ? | ?
Parameterless | ? | ? | ?
Default Contructor | ? | ? | ?
Finalizer | ? | ? | ?
Object Destruction | ? | ? | ?
`GC.Collect` | ? | ? | ?
Encapsulation | ? | ? | ?
Access Modifier | ? | ? | ?
`private` | ? | ? | ?
`protected` | ? | ? | ?
`public` | ? | ? | ?
`internal` | ? | ? | ?
Class Member Access | ? | ? | ?
Inheritance | ? | ? | ?
Property | ? | ? | ?
Getter Method | ? | ? | ?
Setter Method | ? | ? | ?
Validation | ? | ? | ?
Processing | ? | ? | ?
`get` | ? | ? | ?
`set` | ? | ? | ?
Expression Body Syntax | ? | ? | ?
Auto Property | ? | ? | ?
Read-Only Property | ? | ? | ?
Auto Property | ? | ? | ?
base-Class | ? | ? | ?
Inherit From | ? | ? | ?
Derived Class | ? | ? | ?
Child Class | ? | ? | ?
Parent Class | ? | ? | ?
`sealed` | ? | ? | ?
Polymorphism | ? | ? | ?
`as` | ? | ? | ?
`virtual` | ? | ? | ?
`override` | ? | ? | ?
`base` | ? | ? | ?
Abstraction | ? | ? | ?
`abstract` | ? | ? | ?
Implementation | ? | ? | ?
Composition | ? | ? | ?
"Composition over Inheritance" | ? | ? | ?
