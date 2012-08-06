# Interactive C# Shell for Unity3d

## Installation
Import the asset bundle into your project or copy the Mono.CSharp.dll and ConsoleWindow.cs file from this project into your project in an Editor folder.

## Use
Select Window -> Interactive Shell to open the window.

Type "help" to see a list of available commands, otherwise type any valid C# statement or expression.  Some examples of things you can do:

    1 + 2;

    var go = GameObject.FindGameObjectsWithTag("MainCamera");
    go.transform.position = Vector3.zero;

    for(int i = 0; i < 10; i++) { 
            Debug.Log("hello from the shell!"); 
    }

## Shell Commands

### list vars
Lists all variables created within the shell content

### list using
Lists all assemblies currently referenced by a 'using' statement

### help
Print out all available shell commands

### clear
Clear the output text area