# javascript-test-0001-final-26258-bhagyashri
Final Project Assignment - This repository contains the complete final project code and documentation.
let n = 5;
for (let i = 1; i <= n; i++) {
    let row = "";

    for (let j = i; j < n; j++) {
        row += " ";
    }

    row += "*";
    if (i > 1) {
        for (let j = 1; j <= (2 * i - 3); j++) {
            row += " ";
        }
        row += "*";
    }

    console.log(row);
}
for (let i = n - 1; i >= 1; i--) {
    let row = "";

    for (let j = n; j > i; j--) {
        row += " ";
    }

    row += "*";
    if (i > 1) {
        for (let j = 1; j <= (2 * i - 3); j++) {
            row += " ";
        }
        row += "*";
    }

    console.log(row);
}
