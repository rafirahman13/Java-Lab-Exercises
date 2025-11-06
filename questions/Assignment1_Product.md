# 🧮 Assignment 1 – Product Information  

## 🎯 Question  
Create a class called **Product**  
- Add a **main method**  
- Print the following data in the main method  

| Field | Example Value |
|-------|----------------|
| id | 101 |
| title | iphone 15 |
| price | 1895 euros |
| description | perfect product with best image quality |
| category | phone |

---

## 💡 Answer (Java Code)

```java
package labexercises;

public class Product {
    public static void main(String[] args) {
        int id = 101;
        String title = "iphone 15";
        double price = 1895.0;
        String description = "perfect product with best image quality";
        String category = "phone";

        System.out.println("Product Information:");
        System.out.println("ID: " + id);
        System.out.println("Title: " + title);
        System.out.println("Price: " + price + " euros");
        System.out.println("Description: " + description);
        System.out.println("Category: " + category);
    }
}

🧾 Output Preview

```text
Product Information:
ID: 101
Title: iPhone 15
Price: 1895.0 euros
Description: perfect product with best image quality
Category: phone


🧠 Learning Outcome

Learned how to create and use class structure in Java.

Practiced variable declaration and data types.

Improved understanding of output formatting using System.out.println().
