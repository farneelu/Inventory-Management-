# Simple Inventory Management System (C)

This project implements a basic inventory management system in C. It allows users to add new items, update quantities, search for items, and display inventory reports.  Data is stored in a text file using a comma-separated value (CSV) format.

## Features

*   **Add Item:** Adds a new item to the inventory.
*   **Update Quantity:** Updates the quantity of an existing item.
*   **Search Item:** Searches for an item by ID and displays its details.
*   **Display Inventory Report:** Displays a formatted report of all inventory items, including total inventory value.
*   **File Persistence:** Loads and saves inventory data to a file (inventory.txt) using CSV format.

## Getting Started

1.  **Prerequisites:**
    *   A C compiler (e.g., GCC) is required.  If you don't have GCC, you can usually install it using your system's package manager (e.g., `apt-get install gcc` on Debian/Ubuntu, `brew install gcc` on macOS).

2.  **Clone the Repository (Optional):**
    If you are cloning from GitHub:
    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git]  # Replace with your repo URL
    cd YOUR_REPOSITORY_NAME
    ```

3.  **Compile the Code:**
    Open a terminal or command prompt in the project directory and compile the C code using GCC:

    ```bash
    gcc inventory_management.c -o inventory_management
    ```

4.  **Create the Data File:**
    Create an empty file named `inventory.txt` in the same directory as the executable. This file will store the inventory data.  The program will create it for you if it doesn't already exist.

## How to Run the Program

Execute the compiled program:

```bash
./inventory_management
