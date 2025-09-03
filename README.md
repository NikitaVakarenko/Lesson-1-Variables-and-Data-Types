# C# Lesson 1: Variables and Data Types


This repository contains a simple C# console application designed to demonstrate the fundamental concepts of declaring variables and using basic data types.

## Overview

The project is a basic console application written in C# that:
1.  Declares variables of different data types (`int`, `double`, `string`, `bool`).
2.  Assigns values to these variables.
3.  Prints the values to the console in a formatted string.

This serves as an introductory lesson for those new to programming in C#.

## Code Snippet

The core logic is contained within the `Program.cs` file. Here is the `Main` method which serves as the entry point for the application:

```csharp
static void Main(string[] args)
{
    /*
     * Lesson 1: Variables and Data Types
     */
    int age = 25; // Integer
    double height = 5.9; // Double
    string name = "John"; // String
    bool isStudent = true; // Boolean
    Console.WriteLine($"Name: {name}, Age: {age}, Height: {height}, Is Student: {isStudent}");
    Console.ReadLine();
}
```

### Data Types Demonstrated
*   **`int`**: Used for whole numbers (e.g., `25`).
*   **`double`**: Used for floating-point numbers, including decimals (e.g., `5.9`).
*   **`string`**: Used for a sequence of characters or text (e.g., `"John"`).
*   **`bool`**: Used for boolean values, which can only be `true` or `false`.

## Getting Started

To run this project, you will need Visual Studio installed.

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/nikitavakarenko/lesson-1-variables-and-data-types.git
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd lesson-1-variables-and-data-types
    ```
3.  **Open the solution file:**
    Open `Lessons.sln` with Visual Studio.

4.  **Run the application:**
    Press `F5` or select `Debug > Start Debugging` from the menu to build and run the project.

## Expected Output

When you run the application, a console window will appear and display the following output:

```
Name: John, Age: 25, Height: 5.9, Is Student: True