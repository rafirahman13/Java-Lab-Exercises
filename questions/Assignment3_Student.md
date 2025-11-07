# 🧮 Assignment 3 – Student Information  

## 🎯 Question  
Create a Java class called **Student**

### 🧩 Instructions  
1. Create a class named **Student**  
2. Inside it, create a **main() method**  
3. Declare variables — `id`, `name`, `course`, `marks`, `grade`  
4. Assign data to each variable  
5. Print all student information using `System.out.println()`

| Field | Example Value |
|-------|----------------|
| id | 201 |
| name | Rafi Rahman |
| course | Computer Science |
| marks | 92.5 |
| grade | A+ |

---

## 💡 Answer (Java Code)

```java
package labexercises;

public class Student {
    public static void main(String[] args) {
        // Step 3: declare variables
        int id;
        String name;
        String course;
        double marks;
        String grade;

        // Step 4: assign data
        id = 201;
        name = "Rafi Rahman";
        course = "Computer Science";
        marks = 92.5;
        grade = "A+";

        // Step 5: print data
        System.out.println("Student Information:");
        System.out.println("ID: " + id);
        System.out.println("Name: " + name);
        System.out.println("Course: " + course);
        System.out.println("Marks: " + marks);
        System.out.println("Grade: " + grade);
    }
}

🧾 Output Preview

Student Information:
ID: 201
Name: Rafi Rahman
Course: Computer Science
Marks: 92.5
Grade: A+

🧠 Learning Outcome

Practiced how to declare, assign, and print data in Java.
Learned proper structure of a class and main() method.
Improved understanding of variable types and formatted output.
Gained confidence in writing clean, readable Java programs.
