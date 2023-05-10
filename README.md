# Aula-array

Em programação de computadores, um array é uma estrutura de dados que armazena uma coleção de elementos de tal forma que cada um dos elementos possa ser identificado por, pelo menos, um índice ou uma chave. Essa estrutura de dados também é conhecida como variável indexada, vetor e matriz.

# Manipulação de Métodos e Propriedades em array.

## listar em ordem alfabética 

let animais = [“gato”, “cachorro”, “elefante”, “abelha”, “sapo”];
Animais.sort();
Console.log(animais);

## Adicionar(último)

var adicionar = frutas.push('Laranja');

## Adicionar(primeiro)

var adicionar = frutas.unshift('Morango') // adiciona ao início

## Adicionar(index)

Array.splice(posicao_inicial, 0, novo_elemento...);

## Remover(último)

var ultimo = frutas.pop(); // remove Laranja (do final)

## Remover(primeiro)

var primeiro = frutas.shift(); // remove Maçã do início

## Remover(index)

var removedItem = frutas.splice(pos, 1);

## Separar

// Array retornado: ["João", "da", "Silva", "Oliveira"]
stringExemplo = "João da Silva Oliveira";
resultado = stringExemplo.split(" ");

// Array retornado: ["J", "o", "ã", "o", " ", "d", "a", " ", "S", "i",
// "l", "v", "a", " ", "O", "l" , "i", "v", "e", "i", "r", "a"]
stringExemplo = "João da Silva Oliveira";
resultado = stringExemplo.split("");

// Array retornado: ["João", "da", "Silva"]
stringExemplo = "João da Silva Oliveira";
resultado = stringExemplo.split(" ", 3);

// Array retornado: ["usuario", "gmail.com"]
stringExemplo = "usuario@gmail.com";
resultado = stringExemplo.split("@");

// Array retornado: ["Os ", " números ", " precisam ser ", " removidos"]
stringExemplo = " Os 8000 números 345 precisam ser 1 removidos";
resultado = stringExemplo.split(/\d+/);

// Array retornado: ["exemplo", "com", "dados", "no", "formato", "csv"]
conteudoCSV = "exemplo ; com ; dados ; no ; formato ; csv";
resultado = conteudoCSV.split(/\s*;\s*/);

## Copiar

var copiar = frutas.slice()

## Juntar Arrays - arr.concat(valor1, valor2, ..., valorN)

const paisesAfricanos = ["Gana", "Nigéria", "Ruanda"];
const paisesEuropeus = ["Alemanha", "França", "Espanha"];
let paises = [].concat(paisesAfricanos, paisesEuropeus);

## Filtrar

const words = ['spray', 'limit', 'elite', 'exuberant', 'destruction', 'present'];
const result = words.filter(word => word.length > 4);
console.log(result);

## Converter em String 

var monthNames = ['Jan', 'Feb', 'Mar', 'Apr'];
var myVar = monthNames.toString(); // atribui 'Jan,Feb,Mar,Apr' para myVar.

## Inverter Ordem 

var myArray = ['one', 'two', 'three'];
myArray.reverse();
console.log(myArray) // ['three', 'two', 'one']

## Confirmar Elemento

const array1 = [5, 12, 8, 130, 44];
const found = array1.find(element => element > 10);
console.log(found);
// Expected output: 12

