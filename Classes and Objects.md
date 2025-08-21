## Classes 
- Classes are blueprint from which objects are created.
- It represent set of properties and methods which are common for all objects 

```
public class Jainam{
	int x = 10;
	public void methods{
	
	}
	public static void main(String[] args){
		
	}
}
```

- The above code shows how to create the class.
- You can see the class contains attributes and methods.
- Attributes are like variable and methods are like function.
- This attribute and methods are used by objects of class.

## Why Classes required ?

- Classes is blueprint /  template for creating the objects.
- It groups data and methods together.
- Without classes, we’d have to write separate code for each object, which is **messy and repetitive**.

## Objects

- An Object is basic unit of OOPS that represent real life entities 
- An Object is instance of Class 
- To create the object of specific class -> specify the class name then object name then use `new` keyword.
- Hence `new` keyword is used to create the object of a class.
- example:
		`Student s1 = new Student()`;
- Above we can see s1 is object name and student is class name and new keyword is used to create the object and Student() is constructor.

```
public class Jainam{
	String name = "Bheda";
	int age = 18;
	Jainam(){
		System.out.println("Construtor Called");
	}
}
public class Main{
	public static void main(String[] args){ 
		Jainam obj = new Jainam();
		System.out.println(obj.age);
		System.out.println(obj.name);
	}
}
```

- So the above code shows that how to create the object using `new` keyword.

## Step by process when `new`keyword is used.

1. **Memory Allocation in Heap**

	- Java allocated memory for the objects in the Heap area.
	- The size of memory = sum of instance variable in the class.

2. **Default Initialization**

