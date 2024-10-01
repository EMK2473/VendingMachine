# Vending Machine
![Github license](https://img.shields.io/badge/mit-blue.svg)
 
 Licensing: [mit](https://choosealicense.com/licenses/mit/)

## Table of Contents
- [Description](#description)
- [Installation Requirements](#installation-requirements)
- [Application Usage](#application-usage)
- [License](#licensing-information)
- [Contributions](#contributions)
- [Tests Commands](#tests-commands)
- [Questions](#questions)
## Description
A Java program that simulates a simple vending machine. The program allows users to purchase drinks, restock inventory, and report the current number of bottles in stock. This project demonstrates basic object-oriented programming principles and encapsulation.

## Installation Requirements
Ensure you have Java Development Kit (JDK) installed on your system. You can download it from [Oracle](https://www.oracle.com/java/technologies/downloads/) or use a package manager like Homebrew for macOS or apt-get for Linux. 

- Clone or download the repository: 
```Java 
- git clone https://github.com/EMK2473/VendingMachine.git 
```

- Navigate to the project directory: 
```Java
- cd VendingMachine 
```
- Compile the VendingMachine.java file: 
```Java
- javac VendingMachine.java 
```
- Run the program: 
```Java
- java VendingMachine
```

## Application Usage
Once the program is running, it will prompt the user to input the number of bottles to purchase and restock. After entering the data, the program will display the current inventory of bottles in the vending machine. The vending machine holds a default value of 20 bottles in it's inventory. 

The user first input value indicates the number of bottles to be purchased, the second input value indicates the number of bottles to be restocked, and the third input value indicates the number of bottles to be purchased (again).

Example: 


Input: 
```Java
5 10 3 
```
- 5 bottles to be purchased
- 10 bottles to be restocked
- 3 bottes to be purchased
- Prints out inventory report

Output: 
```Java
Inventory: 18 bottles 
```

In this example, the user first purchases 5 bottles, then restocks with 10 bottles, and finally purchases 3 bottles, resulting in 18 bottles remaining in the inventory.

## Contributions
Eric Keeton

## Test Commands
Test the program with various purchase and restock inputs to ensure accurate inventory reporting.

## Questions
For Questions, contact me at emk2473@gmail.com or visit My Github: [EMK2473](https://github.com/EMK2473)