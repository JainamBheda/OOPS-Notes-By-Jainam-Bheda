## Default 

- When no access modifier are specified for a class, methods or data member , it is said to have the default access modifier.

`Only classes within same package can access it`

consider example :

```
package p1;
class Jainam{
	void display(){
		System.out.println("hello World");
	}
}
```

```
package p2;
import p1.*;
class Bheda{
	public static void main(String []args){
		Bheda b = nre
	}
}
```