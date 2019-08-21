# [Make](https://en.wikipedia.org/wiki/Make_(software))

is a build automation tool that creates executables from sources, with recipe specified in a special file named **`Makefile`**. You write simple tutorial of how your program should be build. Then user of your software needs to run just one command to install it. 

When project is simple you can manually enter commands for few files to compile and maybe link them. But when projects become larger, it saves a lot of typing time, just run make, no need to repeat yourself([DRY]([https://en.wikipedia.org/wiki/Don%27t_repeat_yourself](https://en.wikipedia.org/wiki/Don't_repeat_yourself))).

# Resources

1. Very useful and descriptive introduction [tutorial](https://gist.github.com/isaacs/62a2d1825d04437c6f08)
2. [Tutorial](https://makefiletutorial.com/) that covers most used functionality 
3. [Compiling, Linking and Building C++ applications](https://www3.ntu.edu.sg/home/ehchua/programming/cpp/gcc_make.html)
4. [Cheat-sheet](https://gist.github.com/evertrol/4b6fd05f3b6be2b331c60638b1af7101) to recap material

# Projects 

Using make is a common practice even in small projects. But nowadays **`Makefile`**s are being generated automatically with CMake. So you can check CMake section [here](CMake.md).