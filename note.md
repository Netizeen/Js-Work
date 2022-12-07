
// console.log('How you like THAT!! You gon like that');
// 
// DataTypes And Variables+
// 1 String
// middleName = 'Mama';
// const lastname = "Dina";
// console.log(lastname);
let firstName= "my";
let lastName = "twin";
let fullName = firstName + '' + lastName
let otherName = `Good morning ${firstName} ${lastName}`
console.log(fullName);
console.log(otherName);

// 2 Number

let firstNumber = 59;
let secondNumber = 22;

let sum = firstNumber + secondNumber;
console.log(firstNumber);
console.log(typeof firstNumber);
console.log('the sum is: ' + sum);
// 3 Arrays

let rsuStudents = ["Grace Amags", 'Ranting Raga', "Ruth Anga", "Favour Amah"];
let diss = rsuStudents[3]
let scores = [39, 88, 76, 98];

console.log(rsuStudents);
console.log(diss);

// 4 Objects
let InstructorProfile = {
    firstName:'Kelvin',
    stateofOrigin: 'Imo',
    age: 59,
    department: 'web development',
    level: 7843894,
}
console.log(InstructorProfile);
console.log(InstructorProfile.firstName);

// 5 Boolean
let isTheUserSignedIn = true
if (isTheUserSignedIn){
    console.log('Welcome to the Dashboard');
}else{
    console.log('Sign in');
}

// 6 Null & Undefined
let firstName;
let middleName = null;

console.log(firstName);
console.log(middleName);

// 7 Date/Time
let mydate = new Date();

console.log(mydate);
console.log(mydate.getMonth()); 
console.log(mydate.getFullYear());

// Calculate the Date of an Individual

let currentYear = mydate.getFullYear();

let dateOfBirth = 1988;

let age = currentYear - dateOfBirth
console.log(age);

// Complex 

let lecturers =[
    {
        fullName: "Ebiwareme Liberty",
        department: "Mathematics",
        stateOfOrigin : "Bayelsa",
        salary: "7,999,999",
        age: null,
        courses: ["mth 111", "mth 223", 'mth 261']
    },
    {
        fullName: "Benneth Odioka",
        department: "Computer Science",
        stateOfOrigin : "Rivers",
        salary: '15,000,000',
        age: 67,
        courses: ["mth 111", "mth 223", 'mth 261']
    }
]
console.log(lecturers);
console.log(lecturers[0]);
console.log(lecturers[0].courses[2]);

let lecturersProfile ={
    fullName: "Olise Belema",
    department: "Computer Science",
    stateOfOrigin : "Bayelsa",
    salary: "7,999,999",
    age: null,
    courses: ["mth 111", "mth 223", 'mth 261'],
    medicalReport : {
        genotype: "AA",
        bloodgroup: "O",
        height: "9ft",
        visitedDate: ["12th Feb 2019", "25th Mar 2019"],
        eyeDefects:[
            {
                type: "Miopia",
                treatment: "portgin bracing",
            },
            {
                type: "Astigmatism",
                treatment: "none",
            }
        ]
    }
};
console.log(lecturersProfile.medicalReport.visitedDate[1]);
console.log(lecturersProfile.medicalReport.eyeDefects[1].treatment);

let studentScores = [55,67,87,94,24,14,1,23,89];

let studentProfile = {
    name: 'Kelvin',
    age: '26',
    department: 'web development'
};

// Comparison operators
// Greater than >
// Less than <
// Greater than or equal to >=
// Less than or equal to <=
// Equal to ===
// Not equal to !==
// Negation !

// Examples
let x = 67
let y = 40

if (x>y) {
    console.log(`${x} is greater than ${y}`);
} else if(x<y) {
    console.log(`${y} is greater than ${x}`);
} else{
    console.log(`${x} is equal to ${y}`);
}

// Logical operators

// And &&
// Or ||

let username = "Netizen Darkota"
let password = "7667"

if (username === "Netizen Darkota"&& password === "7667") {
    console.log("Welcome to your dashboard");
}else {
    console.log("Incorrect name or password");
}

let stateOfOrigin = "rivers"
let gpa = '4.'

if (stateOfOrigin === "rivers" || gpa === 4.5) {
    console.log("You are qualified for the scholarship");
} else {
    console.log("You are not qualified for the scholarship");
}

// conditional Statements

// 3 categories
// if
// Switch
// Tenary

let favouritefruit = "grape"

switch (favouritefruit) {
    case 'strawberry':
            console.log("nice fruit" + favouritefruit);
        break;
    case 'apple':
            console.log("they are wonderful" + favouritefruit);
        break;
    case 'banana':
            console.log("Amazing" + favouritefruit);
        break;
    case 'grape':
            console.log("You got the " + favouritefruit);
        break;
    default:
            console.log("cant find that");
        break;
}


let a =5;
let b = 12;

let output;

!(a>b) ? (output= `${a} is greater than ${b}`): (output= `${a} is less than ${b}`);

console.log(output);

// Loops
// while

let a = 0;

while (a < 20) {
    console.log(a);
    a = a + 2
}

// for
for (let x = 10; x < 40; x++) {
    console.log(x);   
}

// do while
let d =5
do {
    console.log(d);
} while (d < 20);