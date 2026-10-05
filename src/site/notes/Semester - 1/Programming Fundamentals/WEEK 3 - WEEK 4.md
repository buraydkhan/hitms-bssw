---
{"dg-publish":true,"permalink":"/semester-1/programming-fundamentals/week-3-week-4/","dg-note-properties":{}}
---

# WEEK 3
## Lecture # 6 : Varaible and Data Types

Static Program -> he source code or binary file of a program as it exists in storage (on disk/RAM) before execution. It represents fixed, unexecuted instructions and data definitions.
Ex : HITMS
Dynamic Program -> A running instance of a program in execution (a process). Its behavior, state, and memory allocation change over time based on runtime inputs and execution flow.
Ex : Youtube

> [!question] What do you think a variable is ?
> It changes, a name/tag where we store a data/Name given to a location
> 1002 - Ali
> 1006 - Azhar

> [!NOTE] Types of Data
> Text, audio, video, image
> 
> What would you store ?
> Name : Ali -> string (text), character (letters)
> Age : 29 -> integer
> Height : 5.7 -> floating point
> Employeed : Yes -> boolean
> 

> [!NOTE] Syntax 
> Refers to the set of rules that defines the correct structure and arrangement of words, symbols, or phrases to form valid sentences in a language or valid statements in a programming language.
> 
> Syntax to declare variable
> Datatype nameofvariable = value ; 


```
#include <iostream>
using namespace std;

int main()
{
    int age = 18;
    cout << "Age: ";
    cout << age;
    }

or 

cout << "Age" << age ;

```

> [!question] Naming Rules
> - **Allowed Characters:** A variable name can only contain letters (`a-z`, `A-Z`), digits (`0-9`), and underscores (`_`).
>     
> - **First Character Rule:** A variable name **must start with a letter or an underscore**. It **cannot** start with a digit.
>     
>     - _Valid:_ `totalCount`, `_temp`, `score2`
>         
>     - _Invalid:_ `2ndPlace`
>         
> - **Case Sensitivity:** C++ is strictly case-sensitive. `myVar`, `MyVar`, and `MYVAR` are three completely different variables.
>     
> - **No Keywords:** You cannot use C++ reserved keywords (such as `int`, `for`, `class`, `return`, `void`, `double`) as variable names.
>     
> - **No Spaces or Special Characters:** Variable names cannot contain spaces, hyphens, or symbols like `@`, `#`, `$`, `%`, `!`.
>     
>     - _Valid:_ `user_age`, `userAge`
>         
>     - _Invalid:_ `user age`, `user-age`, `user$price`

## Lecture 7 : Input & Output Constructs 

cout => character out => output
cin => character in => input
cin  >> variable ;

```
#include <iostream>

using namespace std;

int main()
{
    int number;

    cout << "Please enter any number: ";
    cin >> number;

    cout << "The number you have entered: ";
    cout << number;
}

```

## Lecture 8 : Expressions & Operators

Expression -> Combination of values, variables & operators produces a single result or value. Ex : A = B + C

Operators -> Used to perform specific operations on values or varaibles 

> [!NOTE] Assignment Operators
> An assignment operator in C++ is a binary operator used to evaluate an expression on its right-hand side and assign the resulting value to a variable or memory location on its left-hand side.
> 
> - **`=`** (Basic Assignment): Sets the value of the left variable equal to the right expression.
>     
> - **`+=`** (Addition Assignment): Adds the right value to the left variable and updates it.
>     
> - **`-=`** (Subtraction Assignment): Subtracts the right value from the left variable and updates it.
>     
> - **`*=`** (Multiplication Assignment): Multiplies the left variable by the right value and updates it.
>     
> - **`/=`** (Division Assignment): Divides the left variable by the right value and updates it.
>     
> - **`%=`** (Modulus Assignment): Calculates the remainder of dividing the left variable by the right value and updates it.

Arithmetic Operators -> +,-,* , /, %, ++, --
Its a prioritizes structure. Ex : DMAS,BODMAS rule

# WEEK 4 

## Lecture 9 : Conditional Statements

if (condition) -> relation operators are used -> <,>,== , <=, >=, !=

```
int age = 17
if (age > 18){
cout<<"eligible";
}
```

Flowchart: 
`start`
`|`
`if condition`
`|`
`if block`
`|`
`end`

Syntax : 
```
if(condition){
statements;
}
```

Nested Conditions

A **nested condition** is a condition _inside_ another condition. Like:

> "If it's raining, **and if** I have an umbrella, I'll go out. **Otherwise if** I have a raincoat, I'll still go."

```
#include <iostream>
using namespace std;

int main() {
    int age = 20;
    bool hasID = true;

    if (age >= 18) {              // outer condition
        if (hasID) {              // inner (nested) condition
            cout << "You can enter." << endl;
        } else {
            cout << "You need an ID." << endl;
        }
    } else {
        cout << "Too young to enter." << endl;
    }

    return 0;
}
```
