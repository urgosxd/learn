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
```


<!--stackedit_data:
eyJoaXN0b3J5IjpbNjIxMzI1NDYwLC0xNjAyNjIzNDE1LC03MT
UxNTExODYsLTE5Mjk5MDIyMyw4MzA0NzIyODcsMTc1NDIzMTUw
NV19
-->