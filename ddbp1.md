// Programmer: DD  

// Project Name: Bank Project 1 

// Date Written: Feb 25, 2021 

// Desc: This program will allow Robert to input his password and access both his checking and savings accounts. 

 

#include <iostream> 

using namespace std; 

int main ( ) 

{ 

int Password; 

int SavingsAccountBalance; 

int CheckingAccountBalance; 

int SavingsDeposit; 

int num1; 

// variable 

int Password = 123; 

if( Password < 123 ) {      

cout << "access denied"; 

  } 

if( Password = 123 ) {   

cout << "access granted";  

} 

int SavingsAccountBalance = 2500; 

int SavingsDeposit = SavingsAccountBalance + num1; 

cout << ”Hi Robert! Please enter your Password” << endl; 

cin << Password << endl; 

cout << “How much would you like to deposit into your savings?” << endl; 

cin << num1 << endl; 

cout << SavingsDeposit & “dollars. This is your new savings balance.” << endl; 

} 

{ 

int num2; 

int SavingsChecking; 

//variable 

int CheckingAccountBalance = 35; 

int SavingsChecking = CheckingAccountBalance + num2; 

cout << “We have successfully accessed your checking account. How much would you like to deposit?” << endl; 

cin << num2 << endl; 

cout << SavingsChecking & “dollars. This is your new checking balance.” << endl; 

cout << “Thank You for banking with us Robert, have a nice day!” << endl; 

} 

return 0; 

} 
