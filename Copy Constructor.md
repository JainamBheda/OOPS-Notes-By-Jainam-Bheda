
- Unlike other constructors , copy constructors is passed with another object which copies the data available from passed objects to newly created object. 
- Example:
		Below is code which shows implementation of how copy constructors can be used to create a new object by copying the values of another object.

```
class Jainam{
	string name;
	int age;
	Jainam(string name, int age){
		this.name = name;
		this.age = age;
	}
	
	// copy constructor
	Jainam(Jainam obj2){
		this.name = obj2.name;
		this.age = obj2.age;
	}
}

class Main{
	public static void main(String []args){
		Jainam obj1 = new Jainam("BHeda",60);
		Jainam obj2 = new Jainam(obj1);
	}
}
```

- So copy constructor is used to create dublicate object easily from existing object.
- Also is provides `TO ALLOW REFERENCE SHARING (SHALLOW COPY PROBLEM)`

```
Student s1 = new Student();
s1.name = "Jainam";

Student s2 = s1; // Just copies reference
s2.name = "Rahul";

System.out.println(s1.name); // Rahul (unexpected!)

```

`TO AVOID ABOVE PROBLEM WE USE COPY CONSTRUCTOR`

- That's why we use COPY CONSTRUCTOR , 
- And these Copy Constructor helps to create a `DEEP COPY`.

