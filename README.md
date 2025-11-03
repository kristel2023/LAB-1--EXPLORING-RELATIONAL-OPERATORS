# LAB-1--EXPLORING-RELATIONAL-OPERATORS

#include <iostream>
using namespace std;

int main() {
    int a = 5, b = 10, c = 5;

    cout << "a == b: " << (a == b) << endl;
    cout << "a != c: " << (a != c) << endl;
    cout << "a < b: " << (a < b) << endl;
    cout << "b > c: " << (b > c) << endl;
    cout << "(a + c) <= b: " << ((a + c) <= b) << endl;

    cout << "'A' < 'a': " << ('A' < 'a') << endl;

    cout << "\nExplanation:" << endl;
    cout << "Characters are compared based on their ASCII values." << endl;
    cout << "'A' has an ASCII value of 65, while 'a' has 97." << endl;
    cout << "Since 65 < 97, the expression ('A' < 'a') is true, so it displays 1." << endl;

    return 0;
}
