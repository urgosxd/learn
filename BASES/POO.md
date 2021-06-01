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



	public class Main
	{
		public static void main(String[] args) {
			Hero p = new Hero("tiny","streight");
			p.print();
		}
	}

```
## Particularidades

4421210



<!--stackedit_data:
eyJoaXN0b3J5IjpbNjM2NTIwMDg1LDgyMzk0MzE4Nyw2MzY3OD
gxMzQsLTcxMzEzNDI2MSwtMTI0NzExMjYxMywtMTYwMjYyMzQx
NSwtNzE1MTUxMTg2LC0xOTI5OTAyMjMsODMwNDcyMjg3LDE3NT
QyMzE1MDVdfQ==
-->