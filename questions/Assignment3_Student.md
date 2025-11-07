# 🧮 Assignment-3 – Student Information  

## 🎯 Question  
Create a class called **Student** and display student details following the steps below.  

---

### 🧩 Instructions  
* step 1: create a class called Student  
* step 2: create a main method  
* step 3: declare variables → id, name, course, marks, grade  
* step 4: assign the following data in main method  
  `201, "Rafi Rahman", "Computer Science", 92.5, "A+"`  
* step 5: print the data using `System.out.println()`  

---

## 💡 Answer (Java Code)

```java
/*
 * Assignment-3 (Variable and Data Type)
 *
 * step 1: create a class called Student
 * step 2: create a main method
 * step 3: declare variables → id, name, course, marks, grade
 * step 4: assign the following data in main method
 *         201, "Rafi Rahman", "Computer Science", 92.5, "A+"
 * step 5: print the data
 */

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

        // Step 5: print the data
        System.out.println("Student Information:");
        System.out.println("ID: " + id);
        System.out.println("Name: " + name);
        System.out.println("Course: " + course);
        System.out.println("Marks: " + marks);
        System.out.println("Grade: " + grade);
    }
}
