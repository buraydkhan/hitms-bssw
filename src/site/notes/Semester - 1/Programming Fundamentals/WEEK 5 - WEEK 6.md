---
{"dg-publish":true,"permalink":"/semester-1/programming-fundamentals/week-5-week-6/","dg-note-properties":{}}
---

# WEEK 5 & 6

## Lecture 10: Repetitive Structure

> [!QUESTION]
> Question: How would you print your name 10 times? cout ten times? 
> What about 100 times? cout hundred times?

**A good programmer saves time, memory and his/her code is less and efficient**

Loops/Repetitive Structures

> [!NOTE]
> Loops are structure that are used to repeat certain line(s) of code(s)
> It has two types 
> 1. Unconditional
> 2. Conditional 
> 
> Unconditional Loops: You want a loop to execute either a certain number of times. An unconditional loop has no condition and therefore will run fixed times. Is a fixed loop
> 
> For Loop: In C++, for loop is an entry-controlled loop that is used to execute a block of code repeatedly for the given number of times

Syntax:
```cpp
> for (initialization; test_expression; increment/decrement)
> {
> statement(s);
> }
```

```cpp
int main() {
    // Prints numbers from 1 to 5
    for (int i = 1; i <= 5; i++) {
        printf("Iteration: %d\n", i);
    }

    return 0;
}
```

Nested Loop (for): Nested for loop refers to any type of loop that is defined inside a "for" loop

Syntax:
```cpp

for (outer_initialization; outer_test_expression; outer_increment/decrement) {
    
    // Code executed before the inner loop runs

    for (inner_initialization; inner_test_expression; inner_increment/decrement) {
        // Statement(s) executed inside the inner loop
    }

    // Code executed after the inner loop finishes a full cycle
}
```

```cpp
int main() {
    // Outer loop controls rows (runs 3 times)
    for (int i = 1; i <= 10; i++) {
        
        // Inner loop controls columns (runs 3 times for EVERY 1 outer iteration)
        for (int j = 0; j <= 10; j++) {
	        cout<<"*\n";
        }
    }
    return 0;
}
```

While Loop: A 'while' loop is used to repeat a specific block of code an unknown number of times, until a condition is met

Syntax:
```cpp
while(condition){
statement(s);
}
```

```cpp
int choice;
while (choice!=1){
cout<<"Press 1 to exit";
cin>>choice
}
cout<<"Exited";
```

Nested While Loop: Refers to any type of loop that is defined inside a 'while' loop 

Syntax:
```cpp
while(condition){
	while(condition){
	}
	// statement of outer loop
}
```

Do While Loop: The do/while loop is a variant of the while loop. This loop will execute the code block once, before checking if the condition is true, then it will repeat the loop as long as the condition is true.

Nested Do While Loop: 
