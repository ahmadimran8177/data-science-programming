# C++ Code change Auto Watcher

Do not type the same command many times for running c++ files. Instead run this script once.
This project provides a simple setup for automatically compiling and running C++ code whenever changes are made to the source files (`.cpp` and `.h`). It uses `nodemon` to watch for file changes and execute the compilation and run commands.

## Getting Started

1. **Prerequisites:**

   - Ensure you have g++ (GNU C++ Compiler) installed on your system.
   - Node.js and npm (Node Package Manager) are required for running the scripts. You can download them from [nodejs.org](nodejs.org).

2. **Installation:**

   - Clone this repository:
     ```bash
     git clone https://github.com/ahmad-imran-dev/data-science-programming.git
     ```
   - Navigate to the project directory:
     ```bash
     cd data-science-programming
     ```
   - Install the dependencies:
     ```bash
     npm install
     ```

## Usage

Compiles the `main.cpp` file and creates an executable file named `output`. Then, it runs the `output` file. This command watch for file changes. If the main.cpp file changes then the code will be automatically executed instead of typing the command many times.

```bash
npm run watch
```
#### Contributions

Contributions are welcome!  Please feel free to submit pull requests.