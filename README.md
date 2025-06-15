# 📐 Trapezoid Area Calculation in Java

This repository contains a simple Java code example for calculating the **area of a trapezoid**, using `double` variables and console output.

---

## 📌 Problem Description

The goal is to calculate the area of a trapezoid based on the following mathematical formula:

Area = (b + B) / 2 × h


Where:

- **b** → Smaller base
- **B** → Larger base
- **h** → Height

---

## 🖥️ Source Code

```java
package main;

public class Aula24SaidaDadosJava {

    public static void main(String[] args) {
    
        double b, B, h, area;
        
        b = 6.0;
        B = 8.0;
        h = 5.0;
        
        area = (b + B) / 2.0 * h;
        
        System.out.println(area);
    }
}


