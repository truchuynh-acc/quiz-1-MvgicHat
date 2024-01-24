[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/tYncE4AO)
# quiz1_class_and_objects

## Instructions:
Please fill in the blank
```cplus
/*
* Name: Aaron Bond
*/

// Question: Create a C++ class representing a car with attributes like model, year, and color. Include a method to display car details.
// Answer:

#include <iostream>
#include <string>

class Car {
private:
    std::string model;
    int year;
    std::string color;
public:
    //Models//
    void getModel(string model) {
        return model;
    }
    void setModel(string newModel) {
        model = newModel    
    }
    //Years//
    void getYear(int year) {
        return year;
    }
    void setYear(int newYear) {
        newYear = year;
    }
    //Colors//
    void getColor(string color) {
        return color;
    }
    void setColor(string newColor) {
        newCOlor = color;
    }

    void displayDetails() {
        std::cout << "Model: " << model << ", Year: " << year << ", Color: " << color << std::endl;
    }
};

int main() {
    Car myCar;
    myCar.setModel(Toyota);
    myCar.setYear(2022);
    myCar.setColor(white);
    myCar.displayDetails();

    return 0;
}

```
