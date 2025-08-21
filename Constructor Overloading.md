## Constructor Overloading

This allows us to create multiple constructor in the same class with different parameter list.

Example:
		Below code shows implementation of Constructor Overloading.

```
class Jainam{
	String name;
	int age;
	Jainam(){
		System.out.println("This is Default Constructor");
	}
	Jainam(String name){
		this.name = name;
	}
	Jainam(int age){
		this.age = age;
	}
	Jainam(String name,int age){
		this.name = name;
		this.age = age;
	}
	Jainam(Jainam obj1){
		this.name = obj1.name;
		this.age = obj2.age;
	}
}

class Main{
	public static void main (String []args){
		Jainam obj1 = new Jainam();
		Jainam obj2 = new Jainam("Bheda");
		Jainam obj3 = new Jainam(20);
		Jainam obj4 = new Jainma("Jainam",25);
		Jainam obj5 = new Jainam(obj4);
 	}
}
```

- As we can see that using different parameter style we can intialize the object in different way.