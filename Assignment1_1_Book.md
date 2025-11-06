# 🧮 Assignment 1.1 – Book Information  

## 🎯 Question  
Create a Java class called **Book**  

### 🧩 Instructions  
1. Create a class named **Book**  
2. Inside it, create a **main() method**  
3. Inside main, print the following data properly using `System.out.println()`  

| Field | Example Value |
|-------|----------------|
| id | 202 |
| title | Atomic Habits |
| author | James Clear |
| price | 25.99 USD |
| publisher | Penguin Books |
| category | Self-Help |
| description | A powerful guide to building good habits and breaking bad ones. |

---

## 💡 Answer (Java Code)

```java
package labexercises;

public class Book {
    public static void main(String[] args) {
        int id = 202;
        String title = "Atomic Habits";
        String author = "James Clear";
        double price = 25.99;
        String publisher = "Penguin Books";
        String category = "Self-Help";
        String description = "A powerful guide to building good habits and breaking bad ones.";

        System.out.println("Book Information:");
        System.out.println("ID: " + id);
        System.out.println("Title: " + title);
        System.out.println("Author: " + author);
        System.out.println("Price: $" + price + " USD");
        System.out.println("Publisher: " + publisher);
        System.out.println("Category: " + category);
        System.out.println("Description: " + description);
    }
}

🧾 Output Preview

Book Information:
ID: 202
Title: Atomic Habits
Author: James Clear
Price: $25.99 USD
Publisher: Penguin Books
Category: Self-Help
Description: A powerful guide to building good habits and breaking bad ones.

🧠 Learning Outcome

Practiced writing a complete Java class with multiple variables.
Learned how to use System.out.println() for structured output.
Understood how to display text, numeric, and string data together.
Enhanced confidence in Java syntax and console output formatting.
