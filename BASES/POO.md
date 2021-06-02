# POO
Primero veremos la forma general de declarar una clase, con atributos, constructor y sus respectivos metodos.
```ts
	TypeScript
	class Hero{
		name:string
		atributte:string

		constructor(name:string,atributte:string){
		  this.name=name
		  this.atributte=atributte
		}
		print(){
		console.log(this.name+" "+this.atributte)
		}
	
	}
	const p:Hero = new  Hero("huscar","streight")
	p.print()
```
```python
	Python
	class Hero:
    def __init__(self,name,atributte):
        self.name=name
        self.atributte=atributte
    
    def Print(self):
        print(self.name," ",self.atributte)


	p = Hero("Timber","streight")
	p.Print()
```
```java
	Java
	class Hero
	{
	    String name;
	    String atributte;
    
	    public Hero(String name,String atributte){
        this.name = name;
        this.atributte = atributte;
	    }
    
	    public void print(){
	        System.out.println(this.name+" "+this.atributte);
	    }
	}



	public class Main4
	{
		public static void main(String[] args) {
			Hero p = new Hero("tiny","streight");
			p.print();
		}
	}

```
## Particularidades
### Abstraction

```ts
TypeScript
abstract class SerVivo{
	abstract comer():void;
	
}
class Planta extends SerVivo{
	comer(){
		console.log("Fotosintesis")
	}
}

const p = new Planta();
p.comer()
```

```python
Python
from abc import ABC, abstractmethod

class SerVivo(ABC):    
    @abstractmethod
    def comer(self):
        pass
    
class Planta(SerVivo):
    def comer(self):
        print("Fotosintesis")

p = Planta()
p.comer()
```

```java
Java
abstract class SerVivo{
	public abstract void Comer();
}

class Planta extends SerVivo{
	@Override
	public void Comer(){
	System.out.println("Fotosintesis")
	}
}

public class helloWorld{
public static void main(String[] args){
	Planta p = new Planta();
	p.Comer();
}
}
```
### Static
```ts
class  MyClass {
	static  x = 0;
	static  printX() {
	console.log(MyClass.x);
	}
}
MyClass.printX();
```






<!--stackedit_data:
eyJoaXN0b3J5IjpbLTQwMjA1NzgyMiwtMjAyNTUxMTI2OSwxMT
U1Njc0ODM1LC0xNDAxNzcwNDEyLDEyMDUwNjA2MDAsMTQzMzQ4
MDI4OCwtMjA3MTU5NjIzLDgyMzk0MzE4Nyw2MzY3ODgxMzQsLT
cxMzEzNDI2MSwtMTI0NzExMjYxMywtMTYwMjYyMzQxNSwtNzE1
MTUxMTg2LC0xOTI5OTAyMjMsODMwNDcyMjg3LDE3NTQyMzE1MD
VdfQ==
-->