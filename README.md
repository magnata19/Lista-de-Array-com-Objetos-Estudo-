# Lista-de-Array-com-Objetos-Estudo-

let spaceship =[
{name: "Supernova", crewQuantity: 6},
{name: "Colossus", crewQuantity: 3},
{name: "Elemental", crewQuantity: 10},
]

console.log(spaceship[1].name)

"Colossus"

//name == Nome da Espaçonave 
//crewQuantity == Quantidade de tripulantes

//Essa opção do console.log foi para acessar o nome da nave "Colossus". Estou em aprendizado em JS , e sse foi um estudo de hoje. 29/03/2023
//Para acessarmos algum Objeto dentro do array , basta fazermos da seguinte maneira: declarar a Variável "spaceship" + [] e dentro colocar o número do item do array ao qual queira acessar , no caso do exemplo acima foi o 1 , lembrando que a contagem começa sempre do 0. Caso queira acessar , por exemplo, crewQuantity , basta ao invés de colocar .name , colocar .crewQuantity. O mesmo vale para caso queira adicionar outra propriedade , como por exemplo .toUpperCase() , que deixaria o nome em maiúsculo.

//Exemplo:

let spaceship =[
{name: "Supernova", crewQuantity: 6},
{name: "Colossus", crewQuantity: 3},
{name: "Elemental", crewQuantity: 10},
]

console.log(spaceship[1].name.toUpperCase())

"COLOSSUS"
