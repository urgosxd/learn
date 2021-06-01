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
	
}
```




<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQzMzQ4MDI4OCwtMjA3MTU5NjIzLDgyMz
k0MzE4Nyw2MzY3ODgxMzQsLTcxMzEzNDI2MSwtMTI0NzExMjYx
MywtMTYwMjYyMzQxNSwtNzE1MTUxMTg2LC0xOTI5OTAyMjMsOD
MwNDcyMjg3LDE3NTQyMzE1MDVdfQ==
-->