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
	class Hero:
    def __init__(self,name,atributte):
        self.name=name
        self.atributte=atributte
    
    def Print(self):
        print(self.name," ",self.atributte)


p = Hero("Timber","streight")

p.Print()
```


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTcxMzEzNDI2MSwtMTI0NzExMjYxMywtMT
YwMjYyMzQxNSwtNzE1MTUxMTg2LC0xOTI5OTAyMjMsODMwNDcy
Mjg3LDE3NTQyMzE1MDVdfQ==
-->