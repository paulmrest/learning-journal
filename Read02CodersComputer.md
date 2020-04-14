# The Coder's Computer - Text Editors and the Command Line

## Text Editors

There are three main categories of text editors in regards to coding:
* General editors (not intended for coding)
* Text editors with syntactical annotations and/or assistive functions
* Integrated Development Environments (IDEs)

**General editors** - these are programs like Notepad and Word that are not designed for coding, although they can be used if necessary. Programs like Notepad can be very fast and lightweight, but editors in this class offer no assistance with code. Really, general editors should only be used for coding when nothing else is available. Code written in these editors will need to be compiled elsewhere.

**Text editors with syntactical annotations and/or assistive functions** - there are programs like Sublime Text, BBEdit, and Notepad++, that while still fast and lightweight programs, offer syntactical annotations (color coding, highlighting, etc...) and assistive functions (autocomplete suggestions from prior text, intelligent linking of files that share a folder, file name suggestions, etc..). For creating small projects or if you want complete control over the files in a larger project, these editors can be ideal. You still, generally, need to compile the code elsewhere.

**IDEs** - these are complete development environments, including the text editor, compiler, ability to run the compiled program, and generally, an integrated file management system, testing tools, detailed error reporting, and sometimes "live" compiling that tells you as soon as you write code that won't compile. Examples include Xcode, Visual Studio, and Android Studio. IDEs tend to be large, complex, programs, with steep learning curves, and are frequently optimized for developing for a limited scope of platforms. For dedicated developers in those platforms, these are usually the perferred choice with the power and capabilities they offer offsetting the complexity.

## Command Line

For being able to move quickly around your computer's file structure as a developer, a good grasp of your command line interface is essential. In Windows this is the Command Line (cmd.exe) and in MacOS this is the Terminal.

I will be covering the Terminal in MacOS as that is what I have access to.

**Cheatsheet of commands:**

**ls** - list all files in the current directory (so the current directory might contain ReadMe.txt, and a folder called Utilities)

**cd** - change directory (so extending from the above example, *cd Utilities* will move the current directory to be inside the Utilities folder).

**cd ..** - move up one directory (still using the previous example, after *cd Utilities*, if you then entered *cd ..* you would be back at the original folder - *cd ../..* moves up two directories, and *cd ../../..* up three)

**mkdir** - creates a new folder at the current location names whatever succeeds the command (so *mkdir AwesomeProject* makes a new folder called "AwesomeProject")

**Notes:**
1. To handle a file or folder with spaces, you can use the "\" character. So if you have a folder called "Documents Personal" to cd to that folder, you would enter *cd Documents\ Personal*.
1. To handle special characters like parantheses, you can escape a folder with single quotes. So if the a folder is called "Documents (Personal)", to cd to that folder you would enter *cd 'Documents (Personal)'*. Note that the singles quotes also handle the space.
