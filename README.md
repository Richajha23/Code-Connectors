# CodeConnectors
👋 Hello, I'm Richa Jha
This is my first Git Repository.

Skills Flowchart

```mermaid
graph TD;
    A[Skills] --> B[Languages]
    A --> C[Concepts]
    A --> D[Tools]
    B --> E[HTML]
    B --> F[C]
    B --> G[C++]
    C --> H[Data Structures]
    C --> I[Algorithms]
    D --> J[Git]
    D --> K[GitHub]
    D --> L[VS Code]

#include <iostream>
#include <vector>
#include <fstream>
#include <string>
using namespace std;

// Class definition
class Person {
public:
    string name;
    int age;

    // Constructor
    Person(string n, int a) : name(n), age(a) {}

    // Member function
    void printPerson() const {
        cout << "Name: " << name << ", Age: " << age << endl;
    }
};

// Function template
template <typename T>
T add(T a, T b) {
    return a + b;
}

int main() {
    // Basic data types and variables
    int a = 10;
    float b = 20.5;
    char c = 'A';
    bool flag = true;

    // Reference variable
    int &ref = a;

    // Control flow statements
    if (a > 5) {
        cout << "a is greater than 5" << endl;
    } else {
        cout << "a is less than or equal to 5" << endl;
    }

    // Looping statements
    for (int i = 0; i < 5; i++) {
        cout << "i = " << i << endl;
    }

    // Object-oriented programming
    Person person1("John Doe", 30);
    person1.printPerson();

    // Template usage
    cout << "Sum of 10 and 20 is " << add(10, 20) << endl;
    cout << "Sum of 10.5 and 20.5 is " << add(10.5, 20.5) << endl;

    // Exception handling
    try {
        if (b < 0) {
            throw runtime_error("Negative value not allowed");
        } else {
            cout << "b is positive" << endl;
        }
    } catch (const runtime_error &e) {
        cout << "Caught an exception: " << e.what() << endl;
    }

    // Standard Template Library (STL) usage
    vector<int> vec = {1, 2, 3, 4, 5};
    for (int v : vec) {
        cout << "vec element: " << v << endl;
    }

    // File handling
    ofstream file("example.txt");
    if (file.is_open()) {
        file << "Hello, File!" << endl;
        file.close();
    } else {
        cout << "Unable to open file" << endl;
    }

    return 0;
}

