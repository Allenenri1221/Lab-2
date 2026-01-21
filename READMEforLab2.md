# Lab-2

#include <iostream>
using namespace std;

int main()
{
    int age;
    int height;

    // Get user input
    cout << "Welcome to Six Flags." << endl;
    cout << "Input age: ";
    cin >> age;

    cout << "Please enter your height (in inches): ";
    cin >> height;

    // Check eligibility
    if (age >= 12 && height >= 48)
    {
        cout << "You are able to ride the rollercoaster." << endl;
    }
    else if (age < 12 && height >= 48)
    {
        cout << "ineligible due to age." << endl;
    }
    else if (age >= 12 && height < 48)
    {
        cout << "Ineligible due to height." << endl;
    }
    else
    {
        cout << "Ineligible due to age or height." << endl;
    }

    return 0;

}