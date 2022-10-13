---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: Week2
layout: default
nav_order: 2
has_children: true
permaklink: week2
---
  เนื้อหาของสัปดาห์ที่2

  code สัปดาห์ที่ 2
## การประกาศตัวแปร
```java
package com;

import java.io.FileWriter;
import java.io.IOException;

public class Main{
    public static void main(String[] args) {
        String myName = "chinnie";
        int number = 12345678;
        System.out.println("Your name = " + myName);
        System.out.println("Your number is = " + number);

    }
}
```

## การประกาศเงื่อไข

```java
package com;

import java.io.FileWriter;
import java.io.IOException;

public class Main{
    public static void main(String[] args) {
        System.out.printin("=========== Learn Condition ============= ");
        System. out.printin("Please type your Book Name");
        Scanner sc = new Scanner(System.in);
        String book = sc.nextLine();
        int maximumBookLength = 20;
        System.out.printin("Book Length : " + book.length());
        if (book.length()<maximumBookLength)  {
        System.out.println("Your book book "+ length + "<" + maximumBookLength);
        } else {
        System.out.println("Your book "+ book +" length >= "+ maximumBookLength);
        }
    }
}
```