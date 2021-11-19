* Javascript prep

* Tests in jest

`test("that waterLevel decreases after drought", () => {
    index.yew.waterLevel = 25
    index.yew.drought()
    expect(index.yew.waterLevel).toBe(0)
})`

`test("that leaves fall for autumn", () => {
    index.birch.leaves = 200
    index.birch.autumn()
    expect(index.birch.leaves).toBe(50)
})`



* Command line practise

Pwd – print working directory
Cd Desktop/ goes to the folder (press tab to auto complete)
Mkdir – makes a directory(folder) Can create multiple folders in one go separated by spaces
Ls – list all files in current
Touch index.js – creates file index.js
Rm index.js – removed the file
Mv indet.js index.js – renamed to index.js (moves content to new file)
Mv index.js tempFolder/ - moves the file in the folder
Cd .. – moves up one in the path
Cd ../.. – moves up two
Cd ../ *tab tab* - shows whats in the folder above
Cd ~ - takes us back to the home directory
Mkdir “folder1” && mkdir “folder1”/”folder2” – create folder inside folder
Rm -r this deletes things permanently 

* presentation prep

* notes recap with questions and team

* ISTQB mock tests

* extra html css work 

`function myFunction() {
    var element = document.getElementById("change");
    var form = document.getElementById("form");
    var button = document.getElementById("button");
    var pForm = document.getElementById("pForm");
    pForm.remove();
    element.classList.remove("notActive");
    button.classList.add("notActive");
    form.classList.add("notActive");
  }`



* java

Eclipse for Java. 
Int a = 5; 
Char b = ‘I’
Long c = 400;
Double d = 3.2;

String name = “Susan”;
Name.(displays everything you can do)

Run some code through multiple times 
For(int I = 0; I < 8; i++)


* eclipse tutorial

* Unit testing - 

Testing a specific unit of code e.g., a function
Tests a small part of code that is already scripted. Remove syntax errors (code walkthrough to make sure it runs) 
You do look at the script line by line (white box). 
Validation technique. Examine the code thoroughly and evaluate the output to see if the excepted output is produced. 
100% test coverage by making sure the correct input is selected. 
Statement coverage
Decision coverage 
Path coverage
Condition coverage
Branch
X= i/p(numeric value)
If x > 0 
Messagebox “1”
Else
Messagebox “0”
End if 
Testing the basic blocks (remove problems early on) 
Performed by Devs or QA team (show what went right or wrong) either manually or automate
Junit can be used to automate. 

* API video

* Agile roles review 
•	Product owner
•	SCRUM master
•	Team members

* Scopes, var, let, const

`var tester = "hey hi";
    
    function newFunction() {
        var hello = "hello";
    }
    console.log(hello); // error: hello is not defined`

`let greeting = "say Hi";
   let times = 4;

   if (times > 3) {
        let hello = "say Hello instead";
        console.log(hello);// "say Hello instead"
    }
   console.log(hello) // hello is not defined`

`const greeting = "say Hi";
    greeting = "say Hello instead";// error: Assignment to constant variable. `

* Switch cases

* Jasmine work

runnin the same tests from jest but with jasmine and looking at differences and changes

* jest in python

`"jest": {
    "moduleFileExtensions": ["py"],
    "runner": "jest-pytest",
    "testPathIgnorePatterns": [],
    "testMatch": ["**/test_*.py"]
}`

* Python videos (Corey schaefer)

