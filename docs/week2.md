---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: Week2
layout: default
nav_order: 2
has_children: false
permaklink: week2
---
  เนื้อหาของสัปดาห์ที่2

## code สัปดาห์ที่ 2
## การประกาศตัวแปร
```java
package com;

import java.util.Scanner;

public class Main{
    public static void main(String[] args) {
        String myName = "chinnie";
        int number = 12345678;
        double myPi = 3.14147;
        System.out.println("Your name = " + myName);
        System.out.println("Your number is = " + number);
        System.out.println("My Pi " + number);

    }
}
```

## การประกาศเงื่อนไข

```java
package com;

import java.util.Scanner;

public class Main{
    public static void main(String[] args) {

        System.out.println("=========== Learn Condition ============= ");
        System. out.println("Please type your Book Name");
        Scanner sc = new Scanner(System.in);
        String book = sc.nextLine();
        int maximumBookLength = 20;
        System.out.println("Book Length : " + book.length());
        if (book.length()<maximumBookLength)  {
            System.out.println("Your book book "+ book  + "  length <" + maximumBookLength);
        } else {
            System.out.println("Your book "+ book  +" length >= "+ maximumBookLength);
s
    }
    }
}
```