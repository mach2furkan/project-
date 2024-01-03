#include <iostream>
using namespace std;

int main() {
    double height, weight, coffeeAmount;
    int age;
    char sex;

    // Get user inputs
    cout << "Enter your height in meters: ";
    cin >> height;

    cout << "Enter your weight in kilograms: ";
    cin >> weight;

    cout << "Enter your age in years: ";
    cin >> age;

    cout << "Enter your sex (M/F): ";
    cin >> sex;

    cout << "Enter the amount of coffee you drink per day in milliliters: ";
    cin >> coffeeAmount;

    // Calculations or analysis based on the inputs (basic example)
    // You can add more detailed calculations or health recommendations here
    double bmi = weight / (height * height);
    bool highCoffeeIntake = coffeeAmount > 400; // High caffeine intake threshold

    // Display some information based on inputs
    cout << "\n*** Health Information ***\n";
    cout << "BMI (Body Mass Index): " << bmi << endl;
    if (highCoffeeIntake) {
        cout << "You are consuming a high amount of coffee. Consider reducing it for better health.\n";
    } else {
        cout << "Your coffee intake is within the recommended limits.\n";
    }

cout<< "this programme created by furkan askin "<<endl;



   
    return 0;
}
