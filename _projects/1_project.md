---
layout: page
title: A Simple Calculator
tags: calculator, arithmetic, C 
description: Perform basic addition and subtraction of two numbers.
img: assets/img/p.jpg
importance: 1
category: Programing
related_publications: true
---

**Introduction**

This project determines the largest of three numbers entered by the user.

**Code**

```C
#include <stdio.h>

int main() {
    int num1, num2, num3, largest;

    printf("Enter three numbers: ");
    scanf("%d %d %d", &num1, &num2, &num3);

    if (num1 >= num2 && num1 >= num3) {
        largest = num1;
    } else if (num2 >= num1 && num2 >= num3) {
        largest = num2;
    } else {
        largest = num3;
    }

    printf("The largest number is: %d\n", largest);

    return 0;
}
```

**Explanation**

+ The program accepts three numbers as input.
+ It uses conditional statements to compare the three numbers.
+ The largest number is identified and displayed.


