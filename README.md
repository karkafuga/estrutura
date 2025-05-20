MenuED - Interactive Console Menu for Data Structures (C#)

Overview

This C# console application provides an interactive menu to practice data structures:

Vectors (arrays)

Matrices (2D arrays)

Lists

Queues

Stacks

Search Algorithms

Each structure has its own submenu with educational exercises.

Prerequisites

Visual Studio 2022 (or later) with .NET Desktop Development workload installed

.NET 6.0 SDK or newer

Step-by-Step Guide to Run the Program

Clone the repository

git clone https://github.com/your-username/menu-estruturas-dados.git

Open the Solution

Launch Visual Studio.

Select File > Open > Project/Solution...

Navigate to the cloned folder and open MenuEstruturasDados.sln.

Restore NuGet Packages
Visual Studio should automatically restore any required packages. If not:

Right-click the solution in Solution Explorer.

Choose Restore NuGet Packages.

Set Startup Project

In Solution Explorer, right-click the MenuED project.

Select Set as Startup Project.

Build the Solution

Go to Build > Rebuild Solution.

Ensure there are no build errors.

Run the Application

Press F5 or click Start Debugging.

A console window opens showing the MAIN MENU.

Navigate the Menus

Enter the number corresponding to the data structure you want to explore.

In each submenu, choose the exercise number to execute.

Press 0 to go back or Exit on the main menu to close.

Project Structure

menu-estruturas-dados/
├── MenuEstruturasDados.sln      # Visual Studio solution
└── MenuED/                      # C# console project
    ├── Program.cs               # Main menu controller
    └── Structures/              # Submenu implementations
        ├── VectorMenu.cs
        ├── MatrixMenu.cs
        ├── ListMenu.cs
        ├── QueueMenu.cs
        ├── StackMenu.cs
        └── SearchMenu.cs

License

This project is open-source and free for educational use.

Author

Developed as part of SENAI programming exercises.
