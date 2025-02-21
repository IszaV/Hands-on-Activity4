function checkEvenOdd(number) {
    if (number % 2 === 0) {
        console.log(number + " is even.");
    } else {
        console.log(number + " is odd.");
    }
}

for (let i = 1; i <= 10; i++) {
    checkEvenOdd(i);
}
