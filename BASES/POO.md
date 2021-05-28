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
	
```


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEyNDcxMTI2MTMsLTE2MDI2MjM0MTUsLT
cxNTE1MTE4NiwtMTkyOTkwMjIzLDgzMDQ3MjI4NywxNzU0MjMx
NTA1XX0=
-->