# 20230929-template

CPP project template

**.vscode** > **tasks.json** contains the compiler setup for **gcc** and **clang** to compile all .cpp files within the project

**main.cpp** checks whether or not the current compiler can use **C++ 20** (using <=>, absent in previous versions)

**c_cpp_properties.json** contains VSCode C++ extension settings file. Uses **C++ 20** standard