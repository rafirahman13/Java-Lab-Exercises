# 🧮 Assignment 5 – Product Information (User Input)

## 🎯 Question  
Create a Java class called **Product** that takes user input for product details and then displays them on the screen.

---

### 🧩 Instructions  
1. Create a class named **Product**  
2. Inside it, create a **main() method**  
3. Declare variables — `id`, `title`, `price`, `description`, `category`  
4. Take user input for each variable using `Scanner`  
5. Print all product details properly using `System.out.println()`  

---

## 💡 Answer (Java Code)

```java
/*
 * Assignment-5 (User Input)
 * step 1: create a class called Product
 * step 2: create a main method
 * step 3: declare variables: id, title, price, description, category
 * step 4: get user input for each variable
 * step 5: print the variables
 */

package labexercises;

import java.util.Scanner;

public class Product {
    public static void main(String[] args) {

        // Step 3: declare variables
        int id;
        String title;
        double price;
        String description;
        String category;

        // Step 4: get user input
        Scanner input = new Scanner(System.in);

        System.out.print("Enter Product ID: ");
        id = input.nextInt();
        input.nextLine(); // consume newline

        System.out.print("Enter Product Title: ");
        title = input.nextLine();

        System.out.print("Enter Product Price: ");
        price = input.nextDouble();
        input.nextLine(); // consume newline

        System.out.print("Enter Product Description: ");
        description = input.nextLine();

        System.out.print("Enter Product Category: ");
        category = input.nextLine();

        input.close();

        // Step 5: print product details
        System.out.println("\nProduct Information:");
        System.out.println("ID: " + id);
        System.out.println("Title: " + title);
        System.out.println("Price: " + price + " euros");
        System.out.println("Description: " + description);
        System.out.println("Category: " + category);
    }
}

🧾 Output Preview

Enter Product ID: 505
Enter Product Title: Smartwatch
Enter Product Price: 299.99
Enter Product Description: Latest generation smartwatch with health tracking.
Enter Product Category: Electronics

Product Information:
ID: 505
Title: Smartwatch
Price: 299.99 euros
Description: Latest generation smartwatch with health tracking.
Category: Electronics

🧠 Learning Outcome

✅ Practiced using Scanner for user input in Java.
✅ Learned how to handle both numeric and string inputs safely.
✅ Improved understanding of Java’s input/output (I/O) system.
✅ Enhanced ability to create interactive console-based programs.
