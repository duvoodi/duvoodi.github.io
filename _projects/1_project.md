---
layout: page
title: A Simple Calculator
description: Perform basic addition and subtraction of two numbers
tags: calculator, arithmetic, C
img: assets/img/p.jpg
importance: 1
category: work
related_publications: true
---
tags: `calculator`, `arithmetic`, `C`


**Introduction**  

This project demonstrates a simple calculator in C that can perform addition and subtraction of two numbers.

**Code** 

```c
#include <stdio.h>

int main() {
    int num1, num2, choice, result;

    printf("Enter first number: ");
    scanf("%d", &num1);

    printf("Enter second number: ");
    scanf("%d", &num2);

    printf("Choose an operation: 1 for addition, 2 for subtraction: ");
    scanf("%d", &choice);

    if (choice == 1) {
        result = num1 + num2;
        printf("The result of addition is: %d\n", result);
    } else if (choice == 2) {
        result = num1 - num2;
        printf("The result of subtraction is: %d\n", result);
    } else {
        printf("Invalid choice.\n");
    }

    return 0;
}
```

**Explanation**  

1. The program accepts two numbers as input.  
2. It prompts the user to choose an operation: addition (1) or subtraction (2).  
3. Depending on the user's choice, the program calculates the result and prints it.  
4. If the choice is invalid, an error message is displayed.
