---
layout: page
title: Finding the Largest of Three Numbers
description: Identify the largest among three user-provided numbers
tags: comparison, largest number, C
img: assets/img/p.jpg
importance: 1
category: fun
related_publications: true
---
tags: `#comparison`, `#largest_number`, `#C`



‌
**Introduction**  

This project determines the largest of three numbers entered by the user.

**Code** 

```c
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

1. The program accepts three numbers as input.  
2. It uses conditional statements to compare the three numbers.  
3. The largest number is identified and displayed.
