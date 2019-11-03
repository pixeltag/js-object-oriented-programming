// Object Oriented Programming OOP
// Four Pillars

let baseSalary = 3000;
let overTime = 10;
let rate = 20;

function getWage(baseSalary , overTime , rate) {
    return baseSalary + (overTime * rate);
}

//  - Encapsulation : Regroup the properties and methods 
        // - Reduce complexity + increase reusability

let employee = {
    baseSalary: 3000,
    overTime: 10,
    rate: 20,
    // The best function are those with no parameters ! - Uncle Bob
    getWage : function() {
        return this.baseSalary + (this.overTime * this.rate);
    }
}
employee.getWage();


//  - Abstraction
        // - isolate impact of change 
        // - Simpler Interface
        // - Reduce the Imapct of change

//  - Inheritance
        // - Eliminate redundant code

//  - Polymorphism : Many Form
        // - Refactor ugly switch/case statements