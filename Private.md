## Private access modifier

- The Method or data member declared as private are accesible only within the class in which they are declared.

Lets see example;

```
class A{
	private void display(){
		System.out.println("Hello my name is Jainam Bheda");
	}
}

class B{
	public static void main(String[] args){
		A obj = new A();
		A.display();
	}
}
```