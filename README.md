# CPPND: Capstone Snake Game Example

This is a starter repo for the Capstone project in the [Udacity C++ Nanodegree Program](https://www.udacity.com/course/c-plus-plus-nanodegree--nd213). The code for this repo was inspired by [this](https://codereview.stackexchange.com/questions/212296/snake-game-in-c-with-sdl) excellent StackOverflow post and set of responses.

<img src="snake_game.gif"/>
<img src="suliman.png"/>

The Capstone Project gives you a chance to integrate what you've learned throughout this program. This project will become an important part of your portfolio to share with current and future colleagues and employers.

In this project, you can build your own C++ application or extend this Snake game, following the principles you have learned throughout this Nanodegree Program. This project will demonstrate that you can independently create applications using a wide range of C++ features.

## Dependencies for Running Locally
* cmake >= 3.7
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* SDL2 >= 2.0
  * All installation instructions can be found [here](https://wiki.libsdl.org/Installation)
  * Note that for Linux, an `apt` or `apt-get` installation is preferred to building from source.
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory in the top level directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./SnakeGame`.

## Rubric Points

## Rubric Points

### Loops, Functions, I/O
1. A variety of control structures are used in the project.
	The project code is clearly organized into functions.
**Done**

2. The project reads data from an external file or writes data to a file as part of the necessary operation of the program.
**Done**

3. The project accepts input from a user as part of the necessary operation of the program.
**Done**

### Object Oriented Programming
1. The project code is organized into classes with class attributes to hold the data, and class methods to perform tasks.
**Done**

2. All class data members are explicitly specified as public, protected, or private.
**Done**

3. All class members that are set to argument values are initialized through member initialization lists.
**Done**

4. All class member functions document their effects, either through function names, comments, or formal documentation. Member functions do not change program state in undocumented ways.
**Done**

5. Appropriate data and functions are grouped into classes. Member data that is subject to an invariant is hidden from the user. State is accessed via member functions.
**Done**

6. Inheritance hierarchies are logical. Composition is used instead of inheritance when appropriate. Abstract classes are composed of pure virtual functions. Override functions are specified.
**Done**

7. One function is overloaded with different signatures for the same function name.
**Done**

8. One member function in an inherited class overrides a virtual base class member function.
**Done**

9. One function is declared with a template that allows it to accept a generic parameter.
**Done**

### Memory Management
1. At least two variables are defined as references, or two functions use pass-by-reference in the project code.
**Done**

2. At least one class that uses unmanaged dynamically allocated memory, along with any class that otherwise needs to modify state upon the termination of an object, uses a destructor.
**Done**

3. The project follows the Resource Acquisition Is Initialization pattern where appropriate, by allocating objects at compile-time, initializing objects when they are declared, and utilizing scope to ensure their automatic destruction.
**Done**

4. For all classes, if any one of the copy constructor, copy assignment operator, move constructor, move assignment operator, and destructor are defined, then all of these functions are defined.
**Done**

5. For classes with move constructors, the project returns objects of that class by value, and relies on the move constructor, instead of copying the object.
**Done**

6. The project uses at least one smart pointer: unique_ptr, shared_ptr, or weak_ptr. The project does not use raw pointers.
**Done**

### Concurrency
1. The project uses multiple threads in the execution.
**Done**

2. A promise and future is used to pass data from a worker thread to a parent thread in the project code.
**Done**

3. A mutex or lock (e.g. std::lock_guard or `std::unique_lock` is used to protect data that is shared across multiple threads in the project code.
**Done**

4. A std::condition_variable is used in the project code to synchronize thread execution.
**Done**
