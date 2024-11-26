#include <iostream>
using namespace std;

double computeAverage(double a, double b, double c) {
    return (a + b + c) / 3;
}

int main() {
    double num1, num2, num3;
    cout << "Enter three numbers: ";
    cin >> num1 >> num2 >> num3;

    double average = computeAverage(num1, num2, num3);
    cout << "The average is: " << average << endl;

    return 0;
}



