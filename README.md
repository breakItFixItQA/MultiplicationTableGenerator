# MultiplicationTableGenerator
Multiplication Table Generator
This Java program generates and displays the multiplication table for any number input by the user. It prints the first 10 multiples of the given number in a clear and readable format.

📋 Features
Prompts the user to enter a number

Generates a multiplication table from 1 to 10

Displays results in the format: number x multiplier = result

🛠️ How It Works
The program asks the user to enter an integer.

It uses a for loop to calculate and print the multiplication results for values 1 through 10.

Output is shown directly in the console.

💻 Code Overview
Main logic is contained in the MultiplicationTableGenerator class within the day6 package.

java
Copy
Edit
for (int i = 1; i <= 10; i++) {
    int result = number * i;
    System.out.println(number + " x " + i + " = " + result);
}
🧪 Example Output
css
Copy
Edit
Enter a number to print its multiplication table
5
Multiplication Table for 5:
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
...
5 x 10 = 50
📦 How to Run
Open this file in your Java IDE (like Eclipse or IntelliJ).

Compile and run the MultiplicationTableGenerator.java file.

Input a number when prompted in the console.

📄 Requirements
Java JDK 8 or higher
A basic Java IDE or terminal for compiling and running the program
