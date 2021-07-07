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
```kotlin
Kotlin
fun main() {
    val p = Hero("Huscar","Streight")
    p.print()
    
}

class Hero(val name:String,val attribute:String){
    fun print(){
        println("$name"+" "+"$attribute")
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
```kotlin
Kotlin
fun main() {
    val p = Planta()
    p.comer()
    
}

abstract class SerVivo(){
    abstract fun comer()
}

class Planta():SerVivo(){
    override fun comer(){
        println("Fotosintesis")
    }
}
```
### Static
```ts
TypeScript
class  MyClass {
	static  x = 0;
	static  printX() {
	console.log(MyClass.x);
	}
}
MyClass.printX();
```
```python
Python
class MyClass():
	x = 0
	@staticmethod
	def printX():
		print(MyClass.x)

MyClass.printX()
```
```java
class MyClass{
	public static int x = 0;
	public static void printX(){
	System.out.println(MyClass.x);
}
public class helloWorld{
	public static void main(String[] args){
	MyClass.printX();
}
}

```







<!--stackedit_data:
eyJoaXN0b3J5IjpbLTM5ODU0Mjk4LDQ2MTk3NTUzMiw0NjE5Nz
U1MzIsNzM1NDg0MzQ0LC05NDQ2OTA2MywtNDAyMDU3ODIyLC0y
MDI1NTExMjY5LDExNTU2NzQ4MzUsLTE0MDE3NzA0MTIsMTIwNT
A2MDYwMCwxNDMzNDgwMjg4LC0yMDcxNTk2MjMsODIzOTQzMTg3
LDYzNjc4ODEzNCwtNzEzMTM0MjYxLC0xMjQ3MTEyNjEzLC0xNj
AyNjIzNDE1LC03MTUxNTExODYsLTE5Mjk5MDIyMyw4MzA0NzIy
ODddfQ==
-->