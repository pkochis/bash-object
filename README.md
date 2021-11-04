# bash-object
The goal is to create and use objects in bash. The elements of a bash-object are written in bash. Therefore you can use them everywhere, even in cygwin.

## Features
- Classes and objects are implemented
- Classes are organized in a tree structure
- A class can inherit properties from other branches of the tree
- Automatic help system
- Automatic language handler

The package includes some classes and objects to aid development.

## Version
The current stable version is 1.5.0.1 (2021-10-04)

To work, bash version 4.x.x (or above) is required.

## Usage
You can load the obj command into memory: in the **.bashrc** file, type the following line:  
`source <path-to>/obj`
The `obj` command loads other parts of the bash-object if they have not been loaded.

## Help
All operations can be performed via the `obj` command. The necessary information can be found in the help system. The central help system tab can be displayed with the `obj --help` command.
