# CSharp Cheat Sheet Template

Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
`;`     | Used to separate statements from each other.| `int i = 5; i++; Console.WriteLine(i);` | [Script Execution](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#0-script-execution)
`//`    | Used for single-line comments              | `float multiplier = 0.01f; // % to float (e.g. 24% = 0.24)` | [Comments](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#single-line-comments)
Variable Initialization | When a value is assigned to a variable for the first time | `int a = 5;` | [Variables](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#variable-initialization)
`dotnet new console -o project-name` | Used to make a new console script and you type it in your `CMD` | ? | [Creat Project](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.1-hello-world.md#1-create-a-project)
Script Execution Order | The order where code starts and ends. | ? | ?
Formatting | Converts the value of objects to strings based on the formats specified and inserts them into another string. | ? | ?
`Console.WriteLine` | Writes on to the console on a new Line | `Console.WriteLine("HelloWorld");` | [Hello World](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.1-hello-world.md#4-helloworldcsproj)
`Console.Write` | Write on the console on the same line | `Console.Write("HelloWorld");` | [Hello World](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.1-hello-world.md#4-helloworldcsproj)
Multi-Line Comment | Multi-Line Comment is to Comment out Big things in your code so the console cant read it  | This is how you write it `*/` | [Commet](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.3.1-console-basics-1.md#2-comments)
XML Documentation Comment | HTML- och XML-dokument innehåller data som omges av taggar, men där slutar likheten mellan de två språken. | ? | [XML](https://support.microsoft.com/sv-se/office/xml-f%C3%B6r-nyb%C3%B6rjare-a87d234d-4c2e-4409-9cbc-45e4eb857d44)
Variable | Variable are used to store data, Variable consist of type and name. | `int = x;` | [Variables](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.3.1-console-basics-1.md#3-variables)
Variable Declaration | ? | `int=x;` | [Variables](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.3.1-console-basics-1.md#3-variables)
Variable Assignment | Here I Assign the Variable to the number 5| int x = 5; | [Variables](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.3.1-console-basics-1.md#3-variables)
Uninitialized Variable | This will give you an error if you just write this. | `int = x; Console.WriteLine(x);` | [Variables](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.3.1-console-basics-1.md#3-variables)
`=` (Assignment Operator) | This mean that I Assign two things or something to something. | `int = x; int x= 5;`  | [Variables](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.3.1-console-basics-1.md#3-variables)
Scope | ? | ? | ?
Variable Scope | ? | ? | ?
`int` | Interture is a Number | `int x = 5;` | [BasicDataType](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`float` | This is a Fractional numbers | `float numberCool=0.004f;` | [BasicDataType](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`double` | Same as int but prints out decimal Number | double x= 0.004; | [BasicDataType](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`bool` | Bool Varibles print out true or false statements | `bool isWinning=True;` | [BasicDataType](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`char` | Char print out only a singel character | `char euroSign = "€";` | [BasicDataType](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`string` | String can fit text. | string name="Isak"; | [BasicDataType](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`byte` |  | ? | ?
Implicit Casting | Type casting is when you assign a value of one data type to another type. | `int myInt = 9; double myDouble = myInt; ` | [Casting](https://www.w3schools.com/cs/cs_type_casting.php)
Explicit Casting | ? | ? | ?
Type Conversion | ? | ? | ?
`Convert.ToInt32` | ? | ? | ?
Operators | ? | ? | ?
Arithmetic Operators | ? | ? | ?
`+` | ? | ? | ?
`-` | ? | ? | ?
`*` | ? | ? | ?
`/` | ? | ? | ?
`%` | ? | ? | ?
`+=` | ? | ? | ?
`-=` | ? | ? | ?
`++` | ? | ? | ?
`--` | ? | ? | ?
Post-Increment `i++` | ? | ? | ?
Pre-Increment `++i` | ? | ? | ?
`System.Math` | ? | ? | ?
`static` | ? | ? | ?
`Math.Max` | ? | ? | ?
`Math.Min` | ? | ? | ?
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
