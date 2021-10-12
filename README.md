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
`string.+` | This is just used for plus opperator | ` string text= "what ever"+ "you say"; Console.WriteLine("what ever you say");` | [String](https://docs.microsoft.com/en-us/dotnet/csharp/how-to/concatenate-multiple-strings)
`$"{}"` | Can put in varibles into what you want to print. We can combine strings using String-Interpolation. Put the $-operator before a string and variables between { and }| `Console.WriteLine($"You have this many eggs{egg Solution.}")` | [String](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
`string.[]` | This is used for stor string arrays or if you wnat to get a leter in the text  | `string kings []= new kings [3]; string hello= "Hello" Console.Writeline(helloe[1]); Output: e `| [Arrays](https://github.com/marczaku/csharp-oop/blob/main/slides/003.3.5-console-basics-4.md#16-arrays) [String](https://www.w3schools.com/cs/cs_strings.php)
`string.IndexOf` | You can also find the index position of a specific character in a string, by using the IndexOf() method: | `string myString = "Hello";Console.WriteLine(myString.IndexOf("e")); // Outputs "1"` | [String](https://www.w3schools.com/cs/cs_strings.php)
`string.SubString(int)` | Another useful method is Substring(), which extracts the characters from a string, starting from the specified character position/index, and returns a new string. This method is often used together with IndexOf() to get the specific character position: | `string name= "John Daniel"; int charPos = name.IndexOf(D); string lastName= name.SubString(charPos) Console.WriteLine(lastName);` | [String](https://www.w3schools.com/cs/cs_strings.php)
`string.Substring(int, int)` | ? | ? | ?
`string.Replace` | Returns a new string in which all occurrences of a specified Unicode character or String in the current string are replaced with another specified Unicode character or String. | `public string Replace (char oldChar, char newChar);` | [String](https://docs.microsoft.com/en-us/dotnet/api/system.string.replace?view=net-5.0)
immutable | Mutable and immutable are English words that mean "can change" and "cannot change" respectively. The meaning of these words is the same in C# programming language; that means the mutable types are those whose data members can be changed after the instance is created but Immutable types are those whose data members can not be changed after the instance is created. | `class MyClass  {private readonly string myStr;  public MyClass(string str)  {  myStr = str;  } public string GetStr  {  get { return myStr; } }` | [Immutable](https://www.c-sharpcorner.com/article/mutable-and-immutable-class-in-c-sharp/)
Logical Operators | Logical operators are used to determine the logic between variables or values: | ? | [Operators](https://www.w3schools.com/cs/cs_operators.php)
`!` | Reverse the result, returns false if the result is true. | `!(x < 5 && x < 10)` | [Operators](https://www.w3schools.com/cs/cs_operators.php)
`&&` | Returns true if both statements are true | `x < 5 &&  x < 10` | [Operators](https://www.w3schools.com/cs/cs_operators.php)
<code>&#124;&#124;</code> | Returns true if one of the statements is true | `x < 5 `<code>&#124;&#124;</code> ` x < 4` | [Operators](https://www.w3schools.com/cs/cs_operators.php)
Comparison Operators | Comparison operators are used to compare two values: | ? | [Operators](https://www.w3schools.com/cs/cs_operators.php)
`>` | Greater than | `x>y` | [Operators](https://www.w3schools.com/cs/cs_operators.php)
`==` | Equal to | `x==y` | [Operators](https://www.w3schools.com/cs/cs_operators.php)
`!=` | 	Not equal | `x!=y` | [Operators](https://www.w3schools.com/cs/cs_operators.php)
`>=` | Greater than or equal to | `x>=y` | [Operators](https://www.w3schools.com/cs/cs_operators.php)
`<=` | Smaller than or equal to | `x<=y` | [Operators](https://www.w3schools.com/cs/cs_operators.php)
`if` | Use if to specify a block of code to be executed, if a specified condition is true | `if(condition){ // block of code to be executed if the condition is True}` | [Operators](https://www.w3schools.com/cs/cs_operators.php)
`else` | Use the else statement to specify a block of code to be executed if the condition is False. | `else {// block of code to be executed if the condition is False}` | [Operators](https://www.w3schools.com/cs/cs_operators.php)
`else if` | Use the else if statement to specify a new condition if the first condition is False. | `else if(condition2){// block of code to be executed if the condition1 is false and condition2 is True}` | [Operators](https://www.w3schools.com/cs/cs_operators.php)
`? :` | C# includes a decision-making operator ?: which is called the conditional operator or ternary operator. It is the short form of the if else conditions. | `condition ? statement 1 : statement 2` | [Operators](https://www.w3schools.com/cs/cs_operators.php)
Flow Control Statements | Like in any programming language, C# provides statements that can change the sequence of program execution. If you have seen or worked with flow charts, you can easily visualize that it's very frequent when we require decision boxes that indicate how the program flow can change based on condition(s). So, let's see how we can use different C# statements to control and change the flow of program execution. | ? | [Flow Control](https://witscad.com/course/csharp-basics/chapter/control-flow-statements)
`System.Random` | Represents a pseudo-random number generator, which is an algorithm that produces a sequence of numbers that meet certain statistical requirements for randomness. | `public class Random` | [Random](https://docs.microsoft.com/en-us/dotnet/api/system.random?view=net-5.0)
pseudo-random | The numbers are pseudo-random: they are using complex mathematical operations to make them appear random* They are guaranteed to be evenly ditributed across all numbers |  | [Random](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#12-random)
seed | That‘s a feature: we can reproduce the same random numbers if we know the seed. | `Random random = new Random(23746);` | [Random](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#12-random)
`Random.Next(int, int)` | Returns a random integer that is within a specified range. | `public virtual int Next (int minValue, int maxValue);` | [Random](https://docs.microsoft.com/en-us/dotnet/api/system.random.next?view=net-5.0#System_Random_Next_System_Int32_System_Int32_)
`Random.Next()` | int Next() gets a random integer between 0 and int.MaxValue (1.2 bln).Returns a non-negative random integer. | `int number = random.Next();` | [RandomMicrosoft](https://docs.microsoft.com/en-us/dotnet/api/system.random.next?view=net-5.0#System_Random_Next_System_Int32_System_Int32_) [RandomGithub](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#12-random)
`Random.NextDouble()` | Returns a random floating-point number that is greater than or equal to 0.0, and less than 1.0. Double NextDouble() Receive a new randomNumber between 0 (inclusive) and 1 (exclusive), so anything between 0.000000 and 0.9999999 | ` double number = random.NextDouble(); ` | [RandomMicrosoft](https://docs.microsoft.com/en-us/dotnet/api/system.random.next?view=net-5.0#System_Random_Next_System_Int32_System_Int32_) [RandomGithub](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#12-random)
`while` | The while loop loops through a block of code as long as a specified condition is True: | `while(condition){// code block to be executed}` | [While](https://www.w3schools.com/cs/cs_while_loop.php)
bool-expression | A Boolean expression is a C# expression that returns a Boolean value: True or False. You can use a comparison operator, such as the greater than (>) operator to find out if an expression (or a variable) is true: | `int x = 10; int y = 9; Console.WriteLine(x > y);` | [Bool](https://www.w3schools.com/cs/cs_booleans.php)
`do..while` | The do/while loop is a variant of the while loop. This loop will execute the code block once, before checking if the condition is true, then it will repeat the loop as long as the condition is true. | `do {// code block to be executed}while (condition);` | [While](https://www.w3schools.com/cs/cs_while_loop.php)
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
