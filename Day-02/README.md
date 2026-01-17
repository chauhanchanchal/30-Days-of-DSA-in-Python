# Day 02 – Conditional Statements and Loops

---

## 1. Conditional Statements

Conditional statements are used to make decisions in a program based on conditions.

---


### 1.1 if Statement

The `if` statement executes a block of code only when the condition is true.

**Syntax:**
```cpp
if (condition) {
    // statement
}

```

example
```cpp
int x = 10;
if (x > 5) {
    cout << "Greater than 5";
}
```

### 1.2 if–else Statement

The `if–else` statement executes one block of code if the condition is true and another block if the condition is false.

**Syntax:**
```cpp
if (condition) {
    // statement 1
} else {
    // statement 2
}
```
example
```
int n = 5;
if (n % 2 == 0) {
    cout << "Even";
} else {
    cout << "Odd";
}
```
### 1.3 if–else–if Ladder

The `if–else–if` ladder is used to check multiple conditions.  
The first true condition is executed.

**Syntax:**
```cpp
if (condition1) {
    // statement 1
} else if (condition2) {
    // statement 2
} else {
    // statement
}
```
example
```
int marks = 90;
if (marks >= 90) {
    cout << "A";
} else if (marks >= 60) {
    cout << "B";
} else {
    cout << "C";
}
```

### Loop Statements



