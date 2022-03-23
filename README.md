# Prompt-user-input
 The following program prompts the user to input a number and stores it in the variable a:


You can accept user input multiple times throughout the program by declaring both variables at the beginning then using cin >> for each variable.
EXAMPLE; 

#include <iostream>
using namespace std;

int main()
{
    int a, b;
    cout << "Enter a number \n";
    cin >> a;
    cout << "Enter another number \n";
    cin >> b;

    cout << a << " "<< b;

    return 0;
}
