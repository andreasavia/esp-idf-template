# _Project Title_

## Contents

The project **project_title** contains one source file in C language [main.c](main/main.c). The file is located in folder [main](main).

ESP-IDF projects are built using CMake. The project build configuration is contained in `CMakeLists.txt`
files that provide set of directives and instructions describing the project's source files and targets
(executable, library, or both). 

Below is short explanation of remaining files in the project folder.

```
├── CMakeLists.txt             To be update with project details 
├── main
│   ├── CMakeLists.txt
│   └── main.c
└── README.md                  This is the file you are currently reading
```
Additionally, the sample project contains Makefile and component.mk files, used for the legacy Make based build system. 
They are not used or needed when building with CMake and idf.py.

## Development Environment

To configure the laptop with the required development environment, it is recommended to use VS Code and the Espressif IDF extension. 

Setting up the workspace in VS Code for the current project, requires only the following steps:

* Install the Espressif IDF Extension in VS Code [link](https://github.com/espressif/vscode-esp-idf-extension/blob/59a99375c36c2d72e1f78ed477627ea8a4976c14/docs/tutorial/install.md)
* Clone the repository _add git repo url_
* Open the repository folder in VS Code
* Launch 'ESP-IDF: Add vscode configuration folder'

To build, flash, monitor and debug the project using the extension, see the [VS Code Espressif IDF Onboarding](https://github.com/espressif/vscode-esp-idf-extension/blob/HEAD/docs/ONBOARDING.md).

Alternatively the following [ESP-IDF Getting Started Guide](https://idf.espressif.com/) explains how to configure, build and flash the project by using directly the `idf.py` commands.
