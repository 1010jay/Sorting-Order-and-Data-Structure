# Radix Sort Implementations in Python and C++

This project provides implementations of the Radix Sort algorithm in both Python and C++. The code efficiently sorts a list of product IDs ranging from 0 to 9999, making it ideal for applications like inventory management where quick sorting of large datasets is crucial.

## Project Structure


- **C++ Code/**: Contains the C++ implementation of Radix Sort.
  - `test.cpp`: Source code file with the Radix Sort function and a usage example.
- **Python Code/**: Contains the Python implementation of Radix Sort.
  - `test.py`: Script file with the Radix Sort function and a usage example.

## Getting Started

### Prerequisites

- **Python Code**
  - Python 3.x installed on your system.

- **C++ Code**
  - A C++ compiler that supports C++11 or later (e.g., GCC, Clang, MSVC).

### Running the Python Code

1. Navigate to the `Python Code` directory:

   ```bash
   cd "Python Code"
2. Run the script:
    python test.py

### Running the C++ Code

1. Navigate to the `C++ Code` directory:

    ```bash
    cd "C++ Code"

2. Compile the code using a C++ compiler:

    g++ -std=c++11 -o radix_sort test.cpp

    Replace g++ with your compiler if different

3. Run the executable: 

    ./radix_sort
    
    On Windows, run: radix_sort.exe

