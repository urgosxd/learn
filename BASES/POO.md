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
### Clases y Metodos Abstractos

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

```




<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0MDE3NzA0MTIsMTIwNTA2MDYwMCwxND
MzNDgwMjg4LC0yMDcxNTk2MjMsODIzOTQzMTg3LDYzNjc4ODEz
NCwtNzEzMTM0MjYxLC0xMjQ3MTEyNjEzLC0xNjAyNjIzNDE1LC
03MTUxNTExODYsLTE5Mjk5MDIyMyw4MzA0NzIyODcsMTc1NDIz
MTUwNV19
-->