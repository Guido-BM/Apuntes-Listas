# Definiciones y usos

### Las funciones forEach, reduce, filter y map en JavaScript. Estas son funciones de orden superior que son parte de JavaScript y se utilizan comúnmente en programación funcional y trabajando con matrices.

### forEach

forEach se utiliza para iterar sobre una matriz y ejecutar una función para cada elemento de la matriz.

javascript

    const numbers = [1, 2, 3, 4, 5];

    numbers.forEach((number) => {
    console.log(number);
    });
Esto imprimirá los números del 1 al 5 en la consola.

### reduce

 reduce se utiliza para reducir una matriz a un solo valor acumulando los resultados de una función en cada elemento.

javascript

    const numbers = [1, 2, 3, 4, 5];

    const sum = numbers.reduce((accumulator, currentValue) => {
    return accumulator + currentValue;
    }, 0);

    console.log(sum); // Esto imprimirá 15, que es la suma de todos los números.
    
### filter

 filter se utiliza para crear una nueva matriz que contiene solo los elementos que cumplan con ciertos criterios.

javascript

    const numbers = [1, 2, 3, 4, 5];

    const evenNumbers = numbers.filter((number) => {
    return number % 2 === 0;
    });

    console.log(evenNumbers); // Esto imprimirá [2, 4], que son los números pares.
    

### map

### map se utiliza para crear una nueva matriz aplicando una función a cada elemento de la matriz original.

javascript

    const numbers = [1, 2, 3, 4, 5];

    const doubledNumbers = numbers.map((number) => {
    return number * 2;
    });

    console.log(doubledNumbers); // Esto imprimirá [2, 4, 6, 8, 10], que son los números originales multiplicados por 2.


 Estas funciones son poderosas y versátiles, y son útiles para realizar diversas operaciones en matrices de manera eficiente en JavaScript.