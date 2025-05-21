# 📚 MenuED - Interactive Console Menu for Data Structures (C#)

## 🧾 Overview
This C# console application provides an interactive menu for practicing data structures through hands-on exercises.

**Supported Data Structures**:
- **Vectors** (arrays)
- **Matrices** (2D arrays)
- **Lists**
- **Queues**
- **Stacks**
- **Search Algorithms**

---

## ✅ Prerequisites
- **Visual Studio 2022** (or later) with **.NET Desktop Development** workload
- **.NET 6.0 SDK** or newer

---

## 🚀 How to Run the Program

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/menu-estruturas-dados.git

2. Open in Visual Studio
   Launch Visual Studio
   Go to File > Open > Project/Solution...
   Select MenuEstruturasDados.sln

3. Set the Startup Project
   In Solution Explorer, right-click the MenuED project
    Choose Set as Startup Project

4. Restore & Build
    If prompted, restore NuGet packages
    Go to Build > Rebuild Solution
    Confirm there are no build errors
   
5. Run the application
    Press F5 or click Start Debugging
    A console window will open showing the MAIN MENU

6. Use the Menu
    Enter the number for the desired data structure
    Choose one of the exercises listed
    Press 0 to return or exit

## Project Structure

menu-estruturas-dados/
├── MenuEstruturasDados.sln    # Visual Studio solution file
└── MenuED/                    # C# console project
    ├── Program.cs             # Main menu controller
    └── Structures/            # Data structure modules
        ├── VectorMenu.cs      # Vector exercises
        ├── MatrixMenu.cs      # Matrix exercises
        ├── ListMenu.cs        # List operations
        ├── QueueMenu.cs       # Queue operations
        ├── StackMenu.cs       # Stack operations
        └── SearchMenu.cs      # Search algorithms
