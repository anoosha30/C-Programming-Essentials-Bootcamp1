# C++ Programming-Essentials-Bootcamp1
Assignment - C++ Programming Essentials Bootcamp

#include <iostream>

int main() {
    int number;

    // Input from the user
    std::cout << "Enter a number: ";
    std::cin >> number;

    // Check if the number is even or odd
    if (number % 2 == 0) {
        std::cout << "Number is even." << std::endl;
    } else {
        std::cout << "Number is odd." << std::endl;
    }

    return 0;
}
