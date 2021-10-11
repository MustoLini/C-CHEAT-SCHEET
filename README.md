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
Explicit Casting | Explicit casting must be done manually by placing the type in parentheses in front of the value: | `double myDouble = 9.78; int myInt = (int) myDouble;` | [Casting](https://www.w3schools.com/cs/cs_type_casting.php)
Type Conversion | There is Conversion from String to Int And int to string and bool to string. | ` int myInt= 5; nsole.WriteLine(Convert.ToString(myInt)); //OutPut: covert int to string.` | [Conversion](https://www.w3schools.com/cs/cs_type_casting.php)
`Convert.ToInt32` | Convert to Double to int. | `int myInt= 5; onsole.WriteLine(Convert.ToDouble(myInt));`| [Conversion](https://www.w3schools.com/cs/cs_type_casting.php)
Operators | Operators are functions represented by symbols |  `int x = 5 + 5; // x = 10`  | [Operators](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
Arithmetic Operators | Arithmetic operators are used for mathematical operations |  | [Operators](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`+` | Plus is just plus | `int d = x + x` | [Operators](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`-` | Minus is just Minus | `int y = x -t;` | [Operators](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`*` | Multiplictaion | `int x= y*u`| [Operators](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`/` | Divide | `int u=t/u` | [Operators](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-MustoLini/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`%` | Modules Returns the division remainder | `x%y` | [Operators](https://www.w3schools.com/cs/cs_operators.php)
`+=` | Plus to things. | `x += 3; x = x + 3;` | [Operators](https://www.w3schools.com/cs/cs_operators.php)
`-=` | Minus to things | `x -= 3; x = x - 3;` | [Operators](https://www.w3schools.com/cs/cs_operators.php)
`++` | Increment | `Increases the value of a variable by 1: x++` | [Operators](https://www.w3schools.com/cs/cs_operators.php)
`--` | Decrement | `Decreases the value of a variable by 1: x--` | [Operators](https://www.w3schools.com/cs/cs_operators.php)
Post-Increment `i++` | Adds i Again after. |  | [Operators](https://www.w3schools.com/cs/cs_operators.php)
Pre-Increment `++i` | Adds i Before i  |  | [Operators](https://www.w3schools.com/cs/cs_operators.php)
`System.Math` | System.Math is a static class containing many useful functions for numbers. static means, it can not be instantiated, you can not write Math math = new Math(); | int max = Math.Max(5, 3); | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#assignments-00332-console-basics-2)
`static` | Static means, it can not be instantiated. | `static void Main(){}` | 
`Math.Max` | Get the Max Value of two Number | `int max = Math.Max(5,4); Output: 5` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#assignments-00332-console-basics-2)
`Math.Min` | Gets The Min value of two number | `int min = Math.Min(3,4); Output: 3` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#assignments-00332-console-basics-2)
`Math.Sqrt` | Gets the SquareRoot of a Value | `double sqrt= Math.Sqrt(16); Output: 4` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#assignments-00332-console-basics-2)
`Math.Abs` | returns a number that is allways positivt | ` double abs= Math.Abs(-4.5); Output: 4.5` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#assignments-00332-console-basics-2)
`Math.Round` | Returns Rounded number. Closest to the number. | `double round = Math.Round(12.6); Output: 13` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#assignments-00332-console-basics-2)
`Math.Floor` | Returns Rounded number. But Round down.  | `double floor = Math.Floor(12.6); Output: 12 ` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#assignments-00332-console-basics-2)
`Math.Ceiling` | Returns Rounded number. But Round down. | `double ceil = Math.Ceiling(12.1);` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#assignments-00332-console-basics-2)
`Math.Clamp` | int Clamp(int value, int min, int max) returns the value made fit min and max | `double clamp = Math.Clamp(15, 0, 10);` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#assignments-00332-console-basics-2)
`Math.Pow` | double Pow(double value, double power) returns the value to the power of power. | `double pow = Math.Pow(2, 3);` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#assignments-00332-console-basics-2)
`string.Length` | Gets the strings lenght  | `string txt = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"; Console.WriteLine("The length of the txt string is: " + txt.Length); Output: The length of the txt string is: 26` | [String](https://www.w3schools.com/cs/cs_strings.php)
`string.ToUpper` | String to upper meens it will make your string to uppercases. | `string firstName="John"; string toUpper= firstName.ToUpper; Output= JOHN.` | [String](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
`string.+` | ? | ? | ?
`$"{}"` | Can put in varibles into what you want to print. We can combine strings using String-Interpolation. Put the $-operator before a string and variables between { and }| `Console.WriteLine($"You have this many eggs{egg Solution.}")` | [String](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
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
