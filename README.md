# fizzbuzz

//Pseudocode:

//Player puts any number n;
//When he presses the button the number typed is sent to the function;
//The number entered must be an integer;
//the function calculates from 1 to n, the numbers divisible by 3, 5 and 15 and replace them with fizz, buzz and fizz buzz respectively;
//subproblem: how to ensure it wouldn't be split in the correct order (in the if function the order matters!)
//the sequence of numbers returns the screen to the player;
//subproblem: how to print all numbers on the screen and not just the last one and how to erase the old return when a new one is triggered;
//subproblem: give space between numbers and add commas;

//What I've learned:

//playerInput is a variable that only takes the value placed by the player in the input (if you don't use .value, the getElementById function brings the entire line of code)
//since we are going to use only integers, I added parseInt to getElement function.
//Also when using parseInt, the captured value that comes in the form of text (string) is transformed into a number.
//Another way to transform a string into a number is by adding the + sign to the variable (+playerInput)
//console.log prints the result of the function to the console
//typeof returns the type of variable (text or number)
//The printResult.innerHTML function only prints the last input, to solve this, it was necessary to use += to keep the old value and add a new one on the screen.
//When using If/Else the order of execution matters.
//.value e uma propriedade do obiektu INPUT, enquanto .textContent e uma propriedade do obiektu <p>, <h2>...