# Programming concepts with C++
Learn programming concepts using Cpp language.
## Setup environment (Window)
To setup environment we must install some packages : 
### MSYS2
MSYS2 is a collection of tools and libraries providing you with an easy-to-use environment for building, installing and running native Windows software.

Using MSYS2:
```
pacman -Syu
pacman -Su
pacman -Ss gcc
pacman -S mingw-w64-x86_64-gcc
pacman -Ss gdb
pacman -S mingw-w64-x86_64-gdb

gcc --version
g++ --version
gdb --version

``` 

When finish check gcc, g++, gdb version then start in VS code By install c/c++ extension for code debugging.

### first c++ code 
```
#include <iostream>

int main()
{
    int num1 = 20;
    std::cout << "One \n";
    std::cout << "Two \n";
    std::cout << num1+5;
    return 20;
}
```