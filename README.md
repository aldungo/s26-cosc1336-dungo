# s26-cosc1336-dungo

## C++ Hello World Assignment

Welcome! This is a simple C++ programming assignment to help you get started with coding in C++.

### What You'll Learn
- How to compile a C++ program
- How to run a C++ program
- Basic C++ syntax with `iostream` and `cout`

### Prerequisites
- GitHub Codespaces (or any environment with g++ installed)

### Step-by-Step Instructions

#### Step 1: Open the Terminal
In GitHub Codespaces, you should see a terminal at the bottom of your screen. If you don't see it, you can open one by:
- Clicking on the menu: **Terminal → New Terminal**

#### Step 2: Verify You're in the Right Directory
Make sure you're in the project directory by running:
```bash
pwd
```
You should see a path ending with `s26-cosc1336-dungo`.

#### Step 3: Compile the Program
To compile the `main.cpp` file, type the following command in the terminal:
```bash
g++ main.cpp -o hello
```

**What this does:**
- `g++` - This is the C++ compiler
- `main.cpp` - This is the source file we want to compile
- `-o hello` - This tells the compiler to create an executable file named `hello`

If the compilation is successful, you won't see any output. No news is good news!

#### Step 4: Run the Program
Now that you've compiled the program, run it with:
```bash
./hello
```

**What this does:**
- `./hello` - This runs the executable file we just created

#### Step 5: See the Output
You should see the following output in your terminal:
```
Hello, World!
```

Congratulations! You've just compiled and run your first C++ program! 🎉

### Troubleshooting

**If you get a "command not found" error:**
- Make sure you typed the command exactly as shown
- Make sure you completed Step 3 (compilation) before Step 4 (running)

**If you get compilation errors:**
- Check that the `main.cpp` file exists in your current directory
- Make sure you didn't accidentally modify the `main.cpp` file

### Understanding the Code

Let's look at what's in `main.cpp`:

```cpp
#include <iostream>

int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```

- `#include <iostream>` - This includes the input/output stream library
- `int main()` - This is the main function where your program starts
- `std::cout` - This is used to print output to the console
- `<<` - This is the stream insertion operator
- `std::endl` - This adds a newline and flushes the output buffer
- `return 0` - This indicates the program finished successfully

### Next Steps
- Try modifying the message in `main.cpp` to print something different
- Add more `std::cout` lines to print multiple messages
- Experiment and have fun!