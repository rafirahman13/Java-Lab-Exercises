# 🧮 Assignment 4 – Product Discount Calculator  

## 🎯 Question  
Create a Java class called **ProductDiscount** to calculate the final price of a product after applying a discount percentage.  

### 🧩 Instructions  
1. Create a class named **ProductDiscount**  
2. Inside it, create a **main() method**  
3. Declare variables → `id`, `title`, `price`, `discount`, `category`  
4. Assign data for each variable  
5. Calculate the final price after applying the discount  
6. Print all the data using `System.out.println()`  

| Field | Example Value |
|-------|----------------|
| id | 303 |
| title | Laptop |
| price | 1200.0 |
| discount | 15% |
| category | Electronics |

---

## 💡 Answer (Java Code)

```java
package labexercises;

public class ProductDiscount {
    public static void main(String[] args) {

        // Step 3: declare variables
        int id;
        String title;
        double price;
        double discount;
        String category;

        // Step 4: assign data
        id = 303;
        title = "Laptop";
        price = 1200.0;
        discount = 15.0;
        category = "Electronics";

        // Step 5: calculate discounted price
        double finalPrice = price - (price * discount / 100);

        // Step 6: print data
        System.out.println("Product Information:");
        System.out.println("ID: " + id);
        System.out.println("Title: " + title);
        System.out.println("Price: " + price + " euros");
        System.out.println("Discount: " + discount + "%");
        System.out.println("Final Price: " + finalPrice + " euros");
        System.out.println("Category: " + category);
    }
}

🧾 Output Preview

Product Information:
ID: 303
Title: Laptop
Price: 1200.0 euros
Discount: 15.0%
Final Price: 1020.0 euros
Category: Electronics

🧠 Learning Outcome

✅ Practiced using variables and arithmetic operators in Java.
✅ Learned how to calculate percentages and apply formulas in code.
✅ Improved understanding of formatted console output.
✅ Strengthened problem-solving and logic-building skills.
