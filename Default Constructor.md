## Default Constructor

- A Constructor that has no parameter is known as default construtor.
- Default constructor can be `Implicit` / `Explicit` in nature 

#### Implicit Default Constructor 

- If no constructor is defined in a class, the JAVA compiler automatically provide default constructor.
- This constructor doesn't take any parameter and intialize the object whenever created.

#### Explicit Default Constructor 

- If we define constructor with no parameter, it is called explicit default constructor. 


- Example :
	The Below Code shows the use of Default constructor, which is automatically called whenever the object is created. 
```
import java.util.*;

class Main{
	Main(){
		System.out.println("Default Constructor Called");
	}
	public static void main(String []args){
		Main m = new Main(); // prints Default Constructor Called
	} 
}
```

`Note Default constructor provides the default values to the object like 0, null, false etc. depending on the type.`
