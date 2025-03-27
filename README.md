 liçao web dia 27
jennifer e emily


function concatenarArrays(array1, array2) {
    return array1.concat(array2);
}

const numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
const parteNumeros = numeros.slice(3, 8);
console.log(parteNumeros);

const frutas = ['Maçã', 'Banana', 'Laranja', 'Limão', 'Abacaxi'];
frutas.splice(2, 2, 'Kiwi', 'Pêssego');
console.log(frutas);

const menuPrincipal = ['Arroz com Feijão', 'Bife Acebolado', 'Frango Assado'];
const menuDeSobremesas = ['Pudim', 'Torta de Limão', 'Sorvete'];
const menuCompleto = concatenarArrays(menuPrincipal, menuDeSobremesas);
console.log(menuCompleto);

