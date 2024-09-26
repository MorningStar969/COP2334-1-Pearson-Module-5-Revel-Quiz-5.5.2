# COP2334-1-Pearson-Module-5-Revel-Quiz-5.5.2
This is a GitHub repository link for the Pearson Module 5 Revel of Quiz 5.5.2.

//This simulation program is a calculation of the distance a robot traveled into difficult areas of terrain.

//Include the header file
#include <iostream>
using namespace std;
//Declare the function prototypes
int main() {
  int distance = 0;
  int totalDistance = 0;
  char choice;
  do {
    //Display the menu
    cout << "Enter the distance traveled by the robot: ";
    cin >> distance;
    //Validate the input
    totalDistance += distance;
    //Display the total distance traveled
    cout << "Total distance traveled by the robot: " << totalDistance << endl;
    //Ask the user if they want to continue
    cout << "Do you wish to continue? (y/n): ";
    cin >> choice;
    //Validate the user's input
  } while (choice == 'y' || choice == 'Y');
  return 0;
}
