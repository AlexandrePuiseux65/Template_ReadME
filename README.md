# Generation of Calibration File 

[![forthebadge](https://forthebadge.com/images/badges/powered-by-coffee.svg)

The use of this project is to create, with some data frame (excel), to build a usable calibration file, safe and easy to use.
It's mainly a part of a toolchain, which have the main goal of helping developers build and upgrade some future project. 

## Hierarchy

To update it, you can use these command :

```shell
C:\Users\alexandre.puiseux>cd C:/link/of/the/project
C:\Work\CF\GenerateHexFromExcel>tree /f /a > structure_arborescence.txt
```
* [Hierarchy](structure_arborescence.txt)  - Structure of the project

## Utilization

You can compile it in any IDE in can of any modification that need to occur.
But you can also execte it in the cmd with 3 may :

### 1- Testing execution
```shell
C:\Users\alexandre.puiseux> pyhton C:/link/of/the/root.py
```
This code will use 1 argument, and lanch the main_IDE, whicpip insa is mainly use to test an modify the code.
This way it use the excel file containe in the project and it will put the generated file in the exempleOfHexFile'file.

### 2- Use execution
```shell
C:\Users\alexandre.puiseux> pyhton C:/link/of/the/root.py C:/link/of/the/excel/file.xlsm fistAddress sizeOfData defaultValues excelSheet
```
The code will this time created a new Calibration File of the excel file you wich, next to it. This way, the code can also be use in the cmd, or it can be call and use in any other code (Php, JavaScript, ect...).  

### 3- Help
```shell
C:\Users\alexandre.puiseux> pyhton C:/link/of/the/root.py -h
```
In last, you can also see the command and more information on how to use this code by use the argument -h or -help.

## Start

This program containe a executable file of the name "createHexFile.exe". 
It has the following path : 
```
C:\...\GenerateCalibration\build\exe.win-amd64-3.7\createHexFile.exe
```
## Build with

* [Pyhton.py](https://www.python.org/) - Python (back-end)
* [Visual Studio Code](https://code.visualstudio.com/) - IDE

## Contributing

I'd like to thank my internship supervisor Jossri JEBABLI for his advice and help during this internship, which enabled me to become a better developer.
* **Jossri JEBABLI** (https://www.linkedin.com/in/yosri-jebabli-74384a14/?originalSubdomain=fr)

## Versions

**Last version :** 1.0

## Author

* **Alexandre Puiseux** _alias_[@AlexandrePuiseux65](https://github.com/AlexandrePuiseux65)

## License

In the context of the workpackage 5, this tool was developed for the OP'nSoft division of the Plastic Omnium group. For additional information, please refer to the license provided.

[LICENSE](LICENSE.md)

![Alt Text](https://media.giphy.com/media/3orif4LwcbQhWZVsze/giphy.gif)
