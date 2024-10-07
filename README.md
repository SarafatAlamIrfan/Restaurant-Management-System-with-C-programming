# FRIENDS Restaurant Management System

## Overview
This is a simple console-based restaurant ordering system written in C. The program allows users to select various menu items, specify quantities, and calculate the total bill with taxes and additional charges for dine-in or takeaway options. It also handles different payment methods (cash or credit card) and their respective charges.

## How to Run the Code

### Prerequisites
To run this code, you need:
- A C compiler installed on your system (e.g., GCC or a compiler within an IDE like Code::Blocks).
- Make sure to include support for `conio.h` if your environment requires it.

### Steps
1. **Download the code:**
   - Clone this repository or download the `.c` file.

2. **Set up a C compiler:**
   - **GCC (for Linux/Mac/Windows using MinGW):**
     - Install GCC on your system. On Linux/Mac, it's usually pre-installed, or you can install it using `sudo apt-get install gcc` (for Linux).
     - For Windows, you can use MinGW to install GCC.
   - **Code::Blocks:**
     - Download and install Code::Blocks from [here](https://www.codeblocks.org/downloads/).

3. **Compile the program:**
     
     - If you're using Code::Blocks :
     - Open the IDE, create a new project, and copy-paste the code.
     - Compile and run the program directly within the IDE.


   - If you're using GCC:
     - Open the terminal or command prompt.
     - Navigate to the directory where the `.c` file is saved.
     - Run the following command:
       ```bash
       gcc -o restaurant_system restaurant_system.c
       ```
     - This will compile the code and generate an executable file (`restaurant_system` or `restaurant_system.exe`).
     - Run the executable:
       ```bash
       ./restaurant_system
       ```

5. **Running the program:**
   - After successfully compiling, you will see the restaurant's menu displayed in the console.
   - Follow the on-screen instructions to order and calculate the total bill.

## Notes
- Make sure to compile in a console-based environment to see the interactive output.
- The `conio.h` library is used for screen clearing (`system("cls")`) in some sections. If your compiler doesn't support it, you can replace this with `system("clear")` for Linux/Mac or remove it entirely for smooth running on other compilers.

## Authors
- Md Sarafat Alam Mozumder
- Sadia Islam Dia

Feel free to reach out if you encounter any issues while setting up or running the program!
