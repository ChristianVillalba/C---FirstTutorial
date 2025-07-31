# C# First Tutorial

First contact with C# programming language

## Description

Notes from the turtorial: [C# Tutorial For Beginners - Learn C# Basics in 1 Hour ](https://www.youtube.com/watch?v=gfkTfcpWqAY).

## Notes: 
* **C & C++** programming languages when compiled, the compiler translates our code into **native code** from the machine on which it was running.
In other words, the code written in an OS with an specific arquitecture, won't work in other OSs or other hardwares.
* **C#** doesn't translate directly into the machine it is written, but in an *Intermadiate Language* (**IL**) independent of the computer on which it's running.
Then it's translated into Native Code using a **Common Language Runtime** (**CLR**)
* **CLR:** application in memeory that translates IL code into machine code (native code).    
This process is called just-in-time compilation(**JIT**) 
* This allows to code without having to worry about compiling for different machines (as long as its CLR can run our app) 

* Architecutre of .NET Apps
	* Classes: building blocks that provides functionality
	* A class is a countainer with data (Attributes) and functions (methods)
	* As the number of classes grows, we will need **namespaces** to organize them.
	* **Namespaces**: countainer for related classes
	* As the number of namespaces grows, we need **Assambly** (DLL or EXE)
	* **Assambly**: countainer for related namespaces
		* It's a file on a disk, it can be:
		* EXE: executable
		* DLL: Dynamically linked library
	* When compiling an app, the compiler builds one or more assamblies depending on how you parition your code 

* Example: console application
	* Don't have GUI 
	* Visual c# > windows > console application


## Getting Started

### Dependencies

* Describe any prerequisites, libraries, OS version, etc., needed before installing program.
* ex. Windows 10

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Author

Christian Villalba      
Following the tuturial created by: [Programming With Mosh](https://www.youtube.com/@programmingwithmosh)       

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments
* [C# Tutorial For Beginners - Learn C# Basics in 1 Hour ](https://www.youtube.com/watch?v=gfkTfcpWqAY)
* [awesome-readme](https://github.com/matiassingers/awesome-readme)