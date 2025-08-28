## Public Access Modifiers


- If Class, Method or Variable is declared as `public` , it means it is accessible from anywhere ( Within the same Package and from other package also).
  
- It has `widest Scope` Among all access modifiers.

Example 
```
// File: Student.java
package mypackage1;

public class Student {   // public class
    public String name;  // public variable

    public void display() {   // public method
        System.out.println("Name: " + name);
    }
}

```

```
// File: Main.java
package mypackage2;
import mypackage1.Student;  // importing from another package

public class Main {
    public static void main(String[] args) {
        Student s = new Student();  // allowed (public class)
        s.name = "Jainam";          // allowed (public variable)
        s.display();                // allowed (public method)
    }
}

```

