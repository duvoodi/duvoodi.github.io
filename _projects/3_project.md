---
layout: page
title: Checking if a Number is Even or Odd
description: Determine whether a number is even or odd
tags: even, odd, C
img: assets/img/p.jpg
importance: 1
category: fun
related_publications: true
---
tags: `#even`, `#odd`, `#C`



**Introduction**

This project checks whether a given number is even or odd.

**Code** 

```c
#include <stdio.h>

int main() {
    int num;

    printf("Enter a number: ");
    scanf("%d", &num);

    if (num % 2 == 0) {
        printf("The number %d is even.\n", num);
    } else {
        printf("The number %d is odd.\n", num);
    }

    return 0;
}
```

**Explanation**  

1. The program takes an integer input from the user.  
2. It calculates the remainder when the number is divided by 2.  
3. If the remainder is 0, the number is even; otherwise, it is odd.  
4. The result is displayed to the user.
