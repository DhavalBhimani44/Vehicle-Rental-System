# Vehicle Rental System

This is a simple vehicle rental system implemented in C++. The program allows users to rent vehicles such as cars, motorcycles, and trucks, and calculates the total rental fee based on the number of days and quantity of vehicles rented.

## How to Use the Vehicle Rental System

1. Compile the Program: To run the program, you need a C++ compiler. You can compile the program using a command like:

    ```bash
    g++ -o vehicle_rental_system vehicle_rental_system.cpp
    ```

2. Run the Program: Execute the compiled program in your terminal or command prompt.

    ```bash
    ./vehicle_rental_system
    ```

3. Interact with the Program: Follow the on-screen instructions to interact with the program. You will be able to choose from a list of available vehicles, specify the quantity and rental duration for each vehicle, and calculate the total rental fee.

4. View the Results: The program will display a summary of the vehicles rented, including their types, manufacturers, models, quantities, rental days, rates, and rental fees. It will also show the total payable amount.

5. Exiting the Program: After reviewing the results, you can choose whether to continue renting vehicles or exit the program.

## Program Structure

The program consists of the following main components:

- **Vehicle**: The base class for all types of vehicles, including common attributes like make, model, daily rate, and rental status.

- **Derived classes**: Car, Motorcycle, and Truck, inherit from the Vehicle class and provide specific implementations for calculating rental fees.

- The program uses a vector to store instances of different vehicles.

- Users can interact with the program to select vehicles, specify rental quantities, and rental durations.

- The program calculates the total rental fee and displays a summary of the rental.

- The program handles memory management by releasing dynamically allocated vehicle objects when the program terminates.

## Class Diagram

![Class Diagram](https://raw.githubusercontent.com/DhavalBhimani44/Vehicle-Rental-System/master/Class%20Diagram.png)

### Author

This vehicle rental system was created by Dhaval Bhimani, Dhruv Patel and Harsh Kharwar and is intended for educational purposes. Feel free to modify and use it as needed. If you encounter any issues or have suggestions for improvement, please contact dhaval.bhimani.btech2022@sitpune.edu.in.
