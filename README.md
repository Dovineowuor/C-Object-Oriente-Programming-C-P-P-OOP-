# C-Object-Oriente-Programming-C-P-P-OOP-
                           #C++

C++ is a statically typed, compiled, general-purpose, case-sensitive, free-form programming
language that supports procedural, object-oriented, and generic programming.
C++ is regarded as a middle-level language, as it comprises a combination of both highlevel and low-level language features.
C++ was developed by Bjarne Stroustrup starting in 1979 at Bell Labs in Murray Hill, New
Jersey, as an enhancement to the C language and originally named C with Classes but later
it was renamed C++ in 1983.
C++ is a superset of C, and that virtually any legal C program is a legal C++ program.
Note: A programming language is said to use static typing when type checking is performed
during compile-time as opposed to run-time.
Object-Oriented Programming
C++ fully supports object-oriented programming, including the four pillars of object-oriented
development:
 Encapsulation
 Data hiding
 Inheritance
 Polymorphism
Standard Libraries
Standard C++ consists of three important parts:
 The core language giving all the building blocks including variables, data types and
literals, etc.
 The C++ Standard Library giving a rich set of functions manipulating files, strings, etc.
 The Standard Template Library (STL) giving a rich set of methods manipulating data
structures, etc.
1. OVERVIEW 
C++
11
The ANSI Standard
The ANSI standard is an attempt to ensure that C++ is portable; that code you write for
Microsoft's compiler will compile without errors, using a compiler on a Mac, UNIX, a Windows
box, or an Alpha.
The ANSI standard has been stable for a while, and all the major C++ compiler manufacturers
support the ANSI standard.
Learning C++
The most important thing while learning C++ is to focus on concepts.
The purpose of learning a programming language is to become a better programmer; that is,
to become more effective at designing and implementing new systems and at maintaining old
ones.
C++ supports a variety of programming styles. You can write in the style of Fortran, C,
Smalltalk, etc., in any language. Each style can achieve its aims effectively while maintaining
runtime and space efficiency.
Use of C++
C++ is used by hundreds of thousands of programmers in essentially every application
domain.
C++ is being highly used to write device drivers and other software that rely on direct
manipulation of hardware under real-time constraints.
C++ is widely used for teaching and research because it is clean enough for successful
teaching of basic concepts.
Anyone who has used either an Apple Macintosh or a PC running Windows has indirectly used
C++ because the primary user interfaces of these systems are written in C++.
C++
12
Try it Option Online
You really do not need to set up your own environment to start learning C++ programming
language. Reason is very simple, we have already set up C++ Programming environment
online, so that you can compile and execute all the available examples online at the same
time when you are doing your theory work. This gives you confidence in what you are reading
and to check the result with different options. Feel free to modify any example and execute
it online.
Try the following example using our online compiler option available at
http://www.compileonline.com/
#include <iostream>
using namespace std;
int main()
{
 cout << "Hello World";
 return 0;
}
For most of the examples given in this tutorial, you will find Try it option in our website code
sections at the top right corner that will take you to the online compiler. So just make use of
it and enjoy your learning.
Local Environment Setup
If you are still willing to set up your environment for C++, you need to have the following two
softwares on your computer.
Text Editor
This will be used to type your program. Examples of few editors include Windows Notepad,
OS Edit command, Brief, Epsilon, EMACS, and vim or vi.
Name and version of text editor can vary on different operating systems. For example,
Notepad will be used on Windows and vim or vi can be used on windows as well as Linux, or
UNIX.
2. ENVIRONMENT SETUP 
C++
13
The files you create with your editor are called source files and for C++ they typically are
named with the extension .cpp, .cp, or .c.
A text editor should be in place to start your C++ programming.
C++ Compiler
This is an actual C++ compiler, which will be used to compile your source code into final
executable program.
Most C++ compilers don't care what extension you give to your source code, but if you don't
specify otherwise, many will use .cpp by default.
Most frequently used and free available compiler is GNU C/C++ compiler, otherwise you can
have compilers either from HP or Solaris if you have the respective Operating Systems.
Installing GNU C/C++ Compiler:
UNIX/Linux Installation
If you are using Linux or UNIX then check whether GCC is installed on your system by
entering the following command from the command line:
$ g++ -v
If you have installed GCC, then it should print a message such as the following:
Using built-in specs.
Target: i386-redhat-linux
Configured with: ../configure --prefix=/usr .......
Thread model: posix
gcc version 4.1.2 20080704 (Red Hat 4.1.2-46)
If GCC is not installed, then you will have to install it yourself using the detailed instructions
available at http://gcc.gnu.org/install/ .
Mac OS X Installation
If you use Mac OS X, the easiest way to obtain GCC is to download the Xcode development
environment from Apple's website and follow the simple installation instructions.
Xcode is currently available at developer.apple.com/technologies/tools/.
Windows Installation
To install GCC at Windows you need to install MinGW. To install MinGW, go to the MinGW
homepage, www.mingw.org, and follow the link to the MinGW download page. Download the 
C++
14
latest version of the MinGW installation program which should be named MinGW-
<version>.exe.
While installing MinGW, at a minimum, you must install gcc-core, gcc-g++, binutils, and the
MinGW runtime, but you may wish to install more.
Add the bin subdirectory of your MinGW installation to your PATH environment variable so
that you can specify these tools on the command line by their simple names.
When the installation is complete, you will be able to run gcc, g++, ar, ranlib, dlltool, and
several other GNU tools from the Windows command line.
C++
15
When we consider a C++ program, it can be defined as a collection of objects that
communicate via invoking each other's methods. Let us now briefly look into what a class,
object, methods, and instant variables mean.
 Object - Objects have states and behaviors. Example: A dog has states - color, name,
breed as well as behaviors - wagging, barking, and eating. An object is an instance of
a class.
 Class - A class can be defined as a template/blueprint that describes the
behaviors/states that object of its type support.
 Methods - A method is basically a behavior. A class can contain many methods. It is
in methods where the logics are written, data is manipulated and all the actions are
executed.
 Instant Variables - Each object has its unique set of instant variables. An object's
state is created by the values assigned to these instant variables.
C++ Program Structure
Let us look at a simple code that would print the words Hello World.
#include <iostream>
using namespace std;
// main() is where program execution begins.
int main()
{
 cout << "Hello World"; // prints Hello World
 return 0;
}
Let us look at the various parts of the above program:
1. The C++ language defines several headers, which contain information that is either
necessary or useful to your program. For this program, the header <iostream> is
needed.
3. BASIC SYNTAX 
C++
16
2. The line using namespace std; tells the compiler to use the std namespace.
Namespaces are a relatively recent addition to C++.
3. The next line ‘// main() is where program execution begins.’ is a single-line
comment available in C++. Single-line comments begin with // and stop at the end of
the line.
4. The line int main() is the main function where program execution begins.
5. The next line cout << "This is my first C++ program."; causes the message "This
is my first C++ program" to be displayed on the screen.
6. The next line return 0; terminates main() function and causes it to return the value 0
to the calling process.
Compile & Execute C++ Program
Let's look at how to save the file, compile and run the program. Please follow the steps given
below:
1. Open a text editor and add the code as above.
2. Save the file as: hello.cpp
3. Open a command prompt and go to the directory where you saved the file.
4. Type 'g++ hello.cpp' and press enter to compile your code. If there are no errors in
your code the command prompt will take you to the next line and would generate a.out
executable file.
5. Now, type 'a.out' to run your program.
6. You will be able to see ' Hello World ' printed on the window.
$ g++ hello.cpp
$ ./a.out
Hello World
Make sure that g++ is in your path and that you are running it in the directory containing file
hello.cpp.
You can compile C/C++ programs using makefile. For more details, you can check
our ‘Makefile Tutorial’.
Semicolons & Blocks in C++
In C++, the semicolon is a statement terminator. That is, each individual statement must be
ended with a semicolon. It indicates the end of one logical entity.
For example, following are three different statements:
C++
17
x = y;
y = y+1;
add(x, y);
A block is a set of logically connected statements that are surrounded by opening and closing
braces. For example:
{
 cout << "Hello World"; // prints Hello World
 return 0;
}
C++ does not recognize the end of the line as a terminator. For this reason, it does not matter
where you put a statement in a line. For example:
x = y;
y = y+1;
add(x, y);
is the same as
x = y; y = y+1; add(x, y);
C++ Identifiers
A C++ identifier is a name used to identify a variable, function, class, module, or any other
user-defined item. An identifier starts with a letter A to Z or a to z or an underscore (_)
followed by zero or more letters, underscores, and digits (0 to 9).
C++ does not allow punctuation characters such as @, $, and % within identifiers. C++ is a
case-sensitive programming language. Thus, Manpower and manpower are two different
identifiers in C++.
Here are some examples of acceptable identifiers:
mohd zara abc move_name a_123
myname50 _temp j a23b9 retVal
C++ Keywords
The following list shows the reserved words in C++. These reserved words may not be used
as constant or variable or any other identifier names.
C++
18
asm else new this
auto enum operator throw
bool explicit private true
break export protected try
case extern public typedef
catch false register typeid
char float reinterpret_cast typename
class for return union
const friend short unsigned
const_cast goto signed using
continue if sizeof virtual
default inline static void
delete int static_cast volatile
do long struct wchar_t
double mutable switch while
dynamic_cast namespace template
C++
19
Trigraphs
A few characters have an alternative representation, called a trigraph sequence. A trigraph is
a three-character sequence that represents a single character and the sequence always starts
with two question marks.
Trigraphs are expanded anywhere they appear, including within string literals and character
literals, in comments, and in preprocessor directives.
Following are most frequently used trigraph sequences:
Trigraph Replacement
??= #
??/ \
??' ^
??( [
??) ]
??! |
??< {
??> }
??- ~
All the compilers do not support trigraphs and they are not advised to be used because of
their confusing nature.
Whitespace in C++
A line containing only whitespace, possibly with a comment, is known as a blank line, and
C++ compiler totally ignores it.
Whitespace is the term used in C++ to describe blanks, tabs, newline characters and
comments. Whitespace separates one part of a statement from another and enables the 
C++
20
compiler to identify where one element in a statement, such as int, ends and the next element
begins. Statement 1:
int age;
In the above statement there must be at least one whitespace character (usually a space)
between int and age for the compiler to be able to distinguish them. Statement 2:
fruit = apples + oranges; // Get the total fruit
In the above statement 2, no whitespace characters are necessary between fruit and =, or
between = and apples, although you are free to include some if you wish for readability
purpose.
C++
21
Program comments are explanatory statements that you can include in the C++ code. These
comments help anyone reading the source code. All programming languages allow for some
form of comments.
C++ supports single-line and multi-line comments. All characters available inside any
comment are ignored by C++ compiler.
C++ comments start with /* and end with */. For example:
/* This is a comment */
/* C++ comments can also
* span multiple lines
*/
A comment can also start with //, extending to the end of the line. For example:
#include <iostream>
using namespace std;
main()
{
 cout << "Hello World"; // prints Hello World
 return 0;
}
When the above code is compiled, it will ignore // prints Hello World and final executable
will produce the following result:
Hello World
Within a /* and */ comment, // characters have no special meaning. Within a // comment, /*
and */ have no special meaning. Thus, you can "nest" one kind of comment within the other
kind. For example:
4. COMMENTS IN C++ 
C++
22
/* Comment out printing of Hello World:
cout << "Hello World"; // prints Hello World
*/
C++
23
While writing program in any language, you need to use various variables to store various
information. Variables are nothing but reserved memory locations to store values. This means
that when you create a variable you reserve some space in memory.
You may like to store information of various data types like character, wide character, integer,
floating point, double floating point, boolean etc. Based on the data type of a variable, the
operating system allocates memory and decides what can be stored in the reserved memory.
Primitive Built-in Types
C++ offers the programmer a rich assortment of built-in as well as user defined data types.
Following table lists down seven basic C++ data types:
Type Keyword
Boolean bool
Character char
Integer int
Floating point float
Double floating point double
Valueless void
Wide character wchar_t
Several of the basic types can be modified using one or more of these type modifiers:
 signed
 unsigned
 short
5. DATA TYPES 
C++
24
 long
The following table shows the variable type, how much memory it takes to store the value in
memory, and what is maximum and minimum value which can be stored in such type of
variables.
Type Typical Bit Width Typical Range
char 1byte -127 to 127 or 0 to 255
unsigned char 1byte 0 to 255
signed char 1byte -127 to 127
int 4bytes -2147483648 to 2147483647
unsigned int 4bytes 0 to 4294967295
signed int 4bytes -2147483648 to 2147483647
short int 2bytes -32768 to 32767
unsigned short int Range 0 to 65,535
signed short int Range -32768 to 32767
long int 4bytes -2,147,483,647 to 2,147,483,647
signed long int 4bytes same as long int
unsigned long int 4bytes 0 to 4,294,967,295
float 4bytes +/- 3.4e +/- 38 (~7 digits)
double 8bytes +/- 1.7e +/- 308 (~15 digits)
long double 8bytes +/- 1.7e +/- 308 (~15 digits)
C++
25
wchar_t 2 or 4 bytes 1 wide character
The size of variables might be different from those shown in the above table, depending on
the compiler and the computer you are using.
Following is the example, which will produce correct size of various data types on your
computer.
#include <iostream>
using namespace std;
int main()
{
 cout << "Size of char : " << sizeof(char) << endl;
 cout << "Size of int : " << sizeof(int) << endl;
 cout << "Size of short int : " << sizeof(short int) << endl;
 cout << "Size of long int : " << sizeof(long int) << endl;
 cout << "Size of float : " << sizeof(float) << endl;
 cout << "Size of double : " << sizeof(double) << endl;
 cout << "Size of wchar_t : " << sizeof(wchar_t) << endl;
 return 0;
}
This example uses endl, which inserts a new-line character after every line and << operator
is being used to pass multiple values out to the screen. We are also using sizeof() function
to get size of various data types.
When the above code is compiled and executed, it produces the following result which can
vary from machine to machine:
Size of char : 1
Size of int : 4
Size of short int : 2
Size of long int : 4
Size of float : 4
Size of double : 8
Size of wchar_t : 4
C++
26
typedef Declarations
You can create a new name for an existing type using typedef. Following is the simple syntax
to define a new type using typedef:
typedef type newname;
For example, the following tells the compiler that feet is another name for int:
typedef int feet;
Now, the following declaration is perfectly legal and creates an integer variable called
distance:
feet distance;
Enumerated Types
An enumerated type declares an optional type name and a set of zero or more identifiers that
can be used as values of the type. Each enumerator is a constant whose type is the
enumeration.
Creating an enumeration requires the use of the keyword enum. The general form of an
enumeration type is:
enum enum-name { list of names } var-list;
Here, the enum-name is the enumeration's type name. The list of names is comma separated.
For example, the following code defines an enumeration of colors called colors and the variable
c of type color. Finally, c is assigned the value "blue".
enum color { red, green, blue } c;
c = blue;
By default, the value of the first name is 0, the second name has the value 1, and the third
has the value 2, and so on. But you can give a name, a specific value by adding an initializer.
For example, in the following enumeration, green will have the value 5.
enum color { red, green=5, blue };
Here, blue will have a value of 6 because each name will be one greater than the one that
precedes it.
C++
27
A variable provides us with named storage that our programs can manipulate. Each variable
in C++ has a specific type, which determines the size and layout of the variable's memory;
the range of values that can be stored within that memory; and the set of operations that can
be applied to the variable.
The name of a variable can be composed of letters, digits, and the underscore character. It
must begin with either a letter or an underscore. Upper and lowercase letters are distinct
because C++ is case-sensitive:
There are following basic types of variable in C++ as explained in last chapter:
Type Description
bool Stores either value true or false.
char Typically a single octet (one byte). This is an integer type.
int The most natural size of integer for the machine.
float A single-precision floating point value.
double A double-precision floating point value.
void Represents the absence of type.
wchar_t A wide character type.
C++ also allows to define various other types of variables, which we will cover in subsequent
chapters like Enumeration, Pointer, Array, Reference, Data structures, and Classes.
Following section will cover how to define, declare and use various types of variables.
6. VARIABLE TYPES 
C++
28
Variable Definition in C++
A variable definition tells the compiler where and how much storage to create for the variable.
A variable definition specifies a data type, and contains a list of one or more variables of that
type as follows:
type variable_list;
Here, type must be a valid C++ data type including char, w_char, int, float, double, bool or
any user-defined object, etc., and variable_list may consist of one or more identifier names
separated by commas. Some valid declarations are shown here:
int i, j, k;
char c, ch;
float f, salary;
double d;
The line int i, j, k; both declares and defines the variables i, j and k; which instructs the
compiler to create variables named i, j and k of type int.
Variables can be initialized (assigned an initial value) in their declaration. The initializer
consists of an equal sign followed by a constant expression as follows:
type variable_name = value;
Some examples are:
extern int d = 3, f = 5; // declaration of d and f.
int d = 3, f = 5; // definition and initializing d and f.
byte z = 22; // definition and initializes z.
char x = 'x'; // the variable x has the value 'x'.
For definition without an initializer: variables with static storage duration are implicitly
initialized with NULL (all bytes have the value 0); the initial value of all other variables is
undefined.
Variable Declaration in C++
A variable declaration provides assurance to the compiler that there is one variable existing
with the given type and name so that compiler proceed for further compilation without
needing complete detail about the variable. A variable declaration has its meaning at the time
of compilation only, compiler needs actual variable declaration at the time of linking of the
program.
C++
29
A variable declaration is useful when you are using multiple files and you define your variable
in one of the files which will be available at the time of linking of the program. You will
use extern keyword to declare a variable at any place. Though you can declare a variable
multiple times in your C++ program, but it can be defined only once in a file, a function or a
block of code.
Example
Try the following example where a variable has been declared at the top, but it has been
defined inside the main function:
#include <iostream>
using namespace std;
// Variable declaration:
extern int a, b;
extern int c;
extern float f;

int main ()
{
 // Variable definition:
 int a, b;
 int c;
 float f;
 // actual initialization
 a = 10;
 b = 20;
 c = a + b;
 cout << c << endl ;
 f = 70.0/3.0;
 cout << f << endl ;
C++
30
 return 0;
}
When the above code is compiled and executed, it produces the following result:
30
23.3333
Same concept applies on function declaration where you provide a function name at the time
of its declaration and its actual definition can be given anywhere else. For example:
// function declaration
int func();
int main()
{
 // function call
 int i = func();
}
// function definition
int func()
{
 return 0;
}
Lvalues and Rvalues
There are two kinds of expressions in C++:
 lvalue : Expressions that refer to a memory location is called "lvalue" expression. An
lvalue may appear as either the left-hand or right-hand side of an assignment.
 rvalue : The term rvalue refers to a data value that is stored at some address in
memory. An rvalue is an expression that cannot have a value assigned to it which
means an rvalue may appear on the right- but not left-hand side of an assignment.
C++
31
Variables are lvalues and so may appear on the left-hand side of an assignment. Numeric
literals are rvalues and so may not be assigned and cannot appear on the left-hand side.
Following is a valid statement:
int g = 20;
But the following is not a valid statement and would generate compile-time error:
10 = 20;
C++
32
A scope is a region of the program and broadly speaking there are three places, where
variables can be declared:
 Inside a function or a block which is called local variables,
 In the definition of function parameters which is called formal parameters.
 Outside of all functions which is called global variables.
We will learn what a function is, and it's parameter in subsequent chapters. Here let us explain
what local and global variables are.
Local Variables
Variables that are declared inside a function or block are local variables. They can be used
only by statements that are inside that function or block of code. Local variables are not
known to functions outside their own. Following is the example using local variables:
#include <iostream>
using namespace std;
int main ()
{
 // Local variable declaration:
 int a, b;
 int c;
 // actual initialization
 a = 10;
 b = 20;
 c = a + b;
 cout << c;
 return 0;
7. VARIABLE SCOPE 
C++
33
}
GlobalVariables
Global variables are defined outside of all the functions, usually on top of the program. The
global variables will hold their value throughout the life-time of your program.
A global variable can be accessed by any function. That is, a global variable is available for
use throughout your entire program after its declaration. Following is the example using global
and local variables:
#include <iostream>
using namespace std;
// Global variable declaration:
int g;
int main ()
{
 // Local variable declaration:
 int a, b;
 // actual initialization
 a = 10;
 b = 20;
 g = a + b;
 cout << g;
 return 0;
}
A program can have same name for local and global variables but value of local variable inside
a function will take preference. For example:
#include <iostream>
using namespace std;
C++
34
// Global variable declaration:
int g = 20;
int main ()
{
 // Local variable declaration:
 int g = 10;
 cout << g;
 return 0;
}
When the above code is compiled and executed, it produces the following result:
10
Initializing Local and Global Variables
When a local variable is defined, it is not initialized by the system, you must initialize it
yourself. Global variables are initialized automatically by the system when you define them
as follows:
Data Type Initializer
int 0
char '\0'
float 0
double 0
pointer NULL
C++
35
It is a good programming practice to initialize variables properly, otherwise sometimes
program would produce unexpected result.
C++
36
Constants refer to fixed values that the program may not alter and they are called literals.
Constants can be of any of the basic data types and can be divided into Integer Numerals,
Floating-Point Numerals, Characters, Strings and Boolean Values.
Again, constants are treated just like regular variables except that their values cannot be
modified after their definition.
Integer Literals
An integer literal can be a decimal, octal, or hexadecimal constant. A prefix specifies the base
or radix: 0x or 0X for hexadecimal, 0 for octal, and nothing for decimal.
An integer literal can also have a suffix that is a combination of U and L, for unsigned and
long, respectively. The suffix can be uppercase or lowercase and can be in any order.
Here are some examples of integer literals:
212 // Legal
215u // Legal
0xFeeL // Legal
078 // Illegal: 8 is not an octal digit
032UU // Illegal: cannot repeat a suffix
Following are other examples of various types of Integer literals:
85 // decimal
0213 // octal
0x4b // hexadecimal
30 // int
30u // unsigned int
30l // long
30ul // unsigned long
8. CONSTANTS/LITERALS 
C++
37
Floating-point Literals
A floating-point literal has an integer part, a decimal point, a fractional part, and an exponent
part. You can represent floating point literals either in decimal form or exponential form.
While representing using decimal form, you must include the decimal point, the exponent, or
both and while representing using exponential form, you must include the integer part, the
fractional part, or both. The signed exponent is introduced by e or E.
Here are some examples of floating-point literals:
3.14159 // Legal
314159E-5L // Legal
510E // Illegal: incomplete exponent
210f // Illegal: no decimal or exponent
.e55 // Illegal: missing integer or fraction
Boolean Literals
There are two Boolean literals and they are part of standard C++ keywords:
 A value of true representing true.
 A value of false representing false.
You should not consider the value of true equal to 1 and value of false equal to 0.
Character Literals
Character literals are enclosed in single quotes. If the literal begins with L (uppercase only),
it is a wide character literal (e.g., L'x') and should be stored in wchar_t type of variable.
Otherwise, it is a narrow character literal (e.g., 'x') and can be stored in a simple variable of
char type.
A character literal can be a plain character (e.g., 'x'), an escape sequence (e.g., '\t'), or a
universal character (e.g., '\u02C0').
There are certain characters in C++ when they are preceded by a backslash they will have
special meaning and they are used to represent like newline (\n) or tab (\t). Here, you have
a list of some of such escape sequence codes:
Escape sequence Meaning
\\ \ character
C++
38
\' ' character
\" " character
\? ? character
\a Alert or bell
\b Backspace
\f Form feed
\n Newline
\r Carriage return
\t Horizontal tab
\v Vertical tab
\ooo Octal number of one to three digits
\xhh . . . Hexadecimal number of one or more digits
Following is the example to show a few escape sequence characters:
#include <iostream>
using namespace std;
int main()
{
 cout << "Hello\tWorld\n\n";
 return 0;
}
C++
39
When the above code is compiled and executed, it produces the following result:
Hello World
String Literals
String literals are enclosed in double quotes. A string contains characters that are similar to
character literals: plain characters, escape sequences, and universal characters.
You can break a long line into multiple lines using string literals and separate them using
whitespaces.
Here are some examples of string literals. All the three forms are identical strings.
"hello, dear"
"hello, \
dear"
"hello, " "d" "ear"
Defining Constants
There are two simple ways in C++ to define constants:
 Using #define preprocessor.
 Using const keyword.
The #define Preprocessor
Following is the form to use #define preprocessor to define a constant:
#define identifier value
Following example explains it in detail:
#include <iostream>
using namespace std;
C++
40
#define LENGTH 10
#define WIDTH 5
#define NEWLINE '\n'
int main()
{
 int area;

 area = LENGTH * WIDTH;
 cout << area;
 cout << NEWLINE;
 return 0;
}
When the above code is compiled and executed, it produces the following result:
50
The const Keyword
You can use const prefix to declare constants with a specific type as follows:
const type variable = value;
Following example explains it in detail:
#include <iostream>
using namespace std;
int main()
{
 const int LENGTH = 10;
 const int WIDTH = 5;
 const char NEWLINE = '\n';
 int area; 
C++
41

 area = LENGTH * WIDTH;
 cout << area;
 cout << NEWLINE;
 return 0;
}
When the above code is compiled and executed, it produces the following result:
50
Note that it is a good programming practice to define constants in CAPITALS.
C++
42
C++ allows the char, int, and double data types to have modifiers preceding them. A
modifier is used to alter the meaning of the base type so that it more precisely fits the needs
of various situations.
The data type modifiers are listed here:
 signed
 unsigned
 long
 short
The modifiers signed, unsigned, long, and short can be applied to integer base types. In
addition, signed and unsigned can be applied to char, and long can be applied to double.
The modifiers signed and unsigned can also be used as prefix to long or short modifiers.
For example, unsigned long int.
C++ allows a shorthand notation for declaring unsigned, short, or long integers. You can
simply use the word unsigned, short, or long, without int. It automatically implies int. For
example, the following two statements both declare unsigned integer variables.
unsigned x;
unsigned int y;
To understand the difference between the way signed and unsigned integer modifiers are
interpreted by C++, you should run the following short program:
#include <iostream>
using namespace std;
/* This program shows the difference between
* signed and unsigned integers.
*/
int main()
{
 short int i; // a signed short integer
9. MODIFIER TYPES 
C++
43
 short unsigned int j; // an unsigned short integer
 j = 50000;
 i = j;
 cout << i << " " << j;
 return 0;
}
When this program is run, following is the output:
-15536 50000
The above result is because the bit pattern that represents 50,000 as a short unsigned integer
is interpreted as -15,536 by a short.
Type Qualifiers in C++
The type qualifiers provide additional information about the variables they precede.
Qualifier Meaning
const Objects of type const cannot be changed by your program during execution
volatile The modifier volatile tells the compiler that a variable's value may be
changed in ways not explicitly specified by the program.
restrict A pointer qualified by restrict is initially the only means by which the object
it points to can be accessed. Only C99 adds a new type qualifier called
restrict.
C++
44
A storage class defines the scope (visibility) and life-time of variables and/or functions within
a C++ Program. These specifiers precede the type that they modify. There are following
storage classes, which can be used in a C++ Program
 auto
 register
 static
 extern
 mutable
The auto Storage Class
The auto storage class is the default storage class for all local variables.
{
 int mount;
 auto int month;
}
The example above defines two variables with the same storage class, auto can only be used
within functions, i.e., local variables.
The register Storage Class
The register storage class is used to define local variables that should be stored in a register
instead of RAM. This means that the variable has a maximum size equal to the register size
(usually one word) and can't have the unary '&' operator applied to it (as it does not have a
memory location).
{
 register int miles;
}
The register should only be used for variables that require quick access such as counters. It
should also be noted that defining 'register' does not mean that the variable will be stored in
10. STORAGE CLASSES 
C++
45
a register. It means that it MIGHT be stored in a register depending on hardware and
implementation restrictions.
The static Storage Class
The static storage class instructs the compiler to keep a local variable in existence during the
life-time of the program instead of creating and destroying it each time it comes into and
goes out of scope. Therefore, making local variables static allows them to maintain their
values between function calls.
The static modifier may also be applied to global variables. When this is done, it causes that
variable's scope to be restricted to the file in which it is declared.
In C++, when static is used on a class data member, it causes only one copy of that member
to be shared by all objects of its class.
#include <iostream>
// Function declaration
void func(void);
static int count = 10; /* Global variable */
main()
{
 while(count--)
 {
 func();
 }
 return 0;
}
// Function definition
void func( void )
{
 static int i = 5; // local static variable
 i++;
 std::cout << "i is " << i ;
 std::cout << " and count is " << count << std::endl;
C++
46
}
When the above code is compiled and executed, it produces the following result:
i is 6 and count is 9
i is 7 and count is 8
i is 8 and count is 7
i is 9 and count is 6
i is 10 and count is 5
i is 11 and count is 4
i is 12 and count is 3
i is 13 and count is 2
i is 14 and count is 1
i is 15 and count is 0
The extern Storage Class
The extern storage class is used to give a reference of a global variable that is visible to ALL
the program files. When you use 'extern' the variable cannot be initialized as all it does is
point the variable name at a storage location that has been previously defined.
When you have multiple files and you define a global variable or function, which will be used
in other files also, then extern will be used in another file to give reference of defined variable
or function. Just for understanding extern is used to declare a global variable or function in
another file.
The extern modifier is most commonly used when there are two or more files sharing the
same global variables or functions as explained below.
First File: main.cpp
#include <iostream>
int count ;
extern void write_extern();
main()
{
 count = 5;
C++
47
 write_extern();
}
Second File: support.cpp
#include <iostream>
extern int count;
void write_extern(void)
{
 std::cout << "Count is " << count << std::endl;
}
Here, extern keyword is being used to declare count in another file. Now compile these two
files as follows:
$g++ main.cpp support.cpp -o write
This will produce write executable program, try to execute write and check the result as
follows:
$./write
5
The mutable Storage Class
The mutable specifier applies only to class objects, which are discussed later in this tutorial.
It allows a member of an object to override const member function. That is, a mutable
member can be modified by a const member function.
C++
48
An operator is a symbol that tells the compiler to perform specific mathematical or logical
manipulations. C++ is rich in built-in operators and provide the following types of operators:
 Arithmetic Operators
 Relational Operators
 Logical Operators
 Bitwise Operators
 Assignment Operators
 Misc Operators
This chapter will examine the arithmetic, relational, logical, bitwise, assignment and other
operators one by one.
Arithmetic Operators
There are following arithmetic operators supported by C++ language:
Assume variable A holds 10 and variable B holds 20, then:
Operator Description Example
+ Adds two operands A + B will give 30
- Subtracts second operand from the
first
A - B will give -10
* Multiplies both operands A * B will give 200
/ Divides numerator by de-numerator B / A will give 2
% Modulus Operator and remainder of
after an integer division
B % A will give 0
11. OPERATORS 
C++
49
++ Increment operator, increases
integer value by one
A++ will give 11
-- Decrement operator, decreases
integer value by one
A-- will give 9
Try the following example to understand all the arithmetic operators available in C++.
Copy and paste the following C++ program in test.cpp file and compile and run this program.
#include <iostream>
using namespace std;
main()
{
 int a = 21;
 int b = 10;
 int c ;
 c = a + b;
 cout << "Line 1 - Value of c is :" << c << endl ;
 c = a - b;
 cout << "Line 2 - Value of c is :" << c << endl ;
 c = a * b;
 cout << "Line 3 - Value of c is :" << c << endl ;
 c = a / b;
 cout << "Line 4 - Value of c is :" << c << endl ;
 c = a % b;
 cout << "Line 5 - Value of c is :" << c << endl ;
 c = a++;
 cout << "Line 6 - Value of c is :" << c << endl ;
 c = a--;
 cout << "Line 7 - Value of c is :" << c << endl ;
 return 0;
C++
50
}
When the above code is compiled and executed, it produces the following result:
Line 1 - Value of c is :31
Line 2 - Value of c is :11
Line 3 - Value of c is :210
Line 4 - Value of c is :2
Line 5 - Value of c is :1
Line 6 - Value of c is :21
Line 7 - Value of c is :22
Relational Operators
There are following relational operators supported by C++ language
Assume variable A holds 10 and variable B holds 20, then:
Operator Description Example
== Checks if the values of two operands
are equal or not, if yes then
condition becomes true.
(A == B) is not true.
!= Checks if the values of two operands
are equal or not, if values are not
equal then condition becomes true.
(A != B) is true.
> Checks if the value of left operand is
greater than the value of right
operand, if yes then condition
becomes true.
(A > B) is not true.
< Checks if the value of left operand is
less than the value of right operand,
if yes then condition becomes true.
(A < B) is true.
C++
51
>= Checks if the value of left operand is
greater than or equal to the value of
right operand, if yes then condition
becomes true.
(A >= B) is not true.
<= Checks if the value of left operand is
less than or equal to the value of
right operand, if yes then condition
becomes true.
(A <= B) is true.
Try the following example to understand all the relational operators available in C++.
Copy and paste the following C++ program in test.cpp file and compile and run this program.
#include <iostream>
using namespace std;
main()
{
 int a = 21;
 int b = 10;
 int c ;
 if( a == b )
 {
 cout << "Line 1 - a is equal to b" << endl ;
 }
 else
 {
 cout << "Line 1 - a is not equal to b" << endl ;
 }
 if ( a < b )
 {
 cout << "Line 2 - a is less than b" << endl ;
 }
C++
52
 else
 {
 cout << "Line 2 - a is not less than b" << endl ;
 }
 if ( a > b )
 {
 cout << "Line 3 - a is greater than b" << endl ;
 }
 else
 {
 cout << "Line 3 - a is not greater than b" << endl ;
 }
 /* Let's change the values of a and b */
 a = 5;
 b = 20;

(Tutorialspoint,2014) C++, Cplusplus: cpp_tutorial.pdf
https://store.tutorialspoint.com
