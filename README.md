const numbers = [];

for (let i = 0; i < 10; i++) {
    const number = parseInt(prompt("Inserisci un numero"));
    numbers.push(number);
};




let sum = 0;

for(let i = 0; i < numbers.length; i++) {
    sum += numbers[i];
}

    console.log(sum)

