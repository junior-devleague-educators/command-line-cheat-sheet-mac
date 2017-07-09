# Command Line Cheat Sheet

## Directories

``` $ cd <directory>```


Change directory to `<directory>`.

```$ cd ..```


Changing or navigating back to parent directory.

```$ ls```


List all the contents of current directory.

```$ ls -a```


List detailed directory contents, including hidden files.

```mkdir <directory>```


Creates a new directory with name `<directory>`. *Replace* `<directory>` *with the name of your new directory.*

```$ pwd``` 


Displays path of current working directory.

```$ rmdir <directory>```


Removes directory only if directory is empty.

```$ rm -r <directory>```


Removes directory and all it's content recursively.


## Files

```$ touch <file>```


Create a new file in current directory.

```$ mv <old-file-name> <new-file-name>```


Rename `<old-file-name>` to `<new-file-name>`.

```$ mv <file> <directory>```


Move `<file>` to `<directory>` possibly overwrititng an existing file.

```$ cp <file> <directory>```


Copy `<file>` to `<directory>` possibly overwrititng an existing file.

```$ cp -r <directory1> <directory2>```


Copy `<directory1>` and its contents to `<directory2>` possibly overwrititng files in an existing directory.

```$ rm <file>```


Delete or Remove `<file>` from current directory.

## Shortcuts

Key/Command | Description
---|---
Tab | Auto-complete files and folder names
Ctrl + A | Go to the beginning of the line you are currently typing on
Ctrl + E | Go to the end of the line you are currently typing on
Ctrl + U | Clear the line before the cursor
Ctrl + K | Clear the line after the cursor
Ctrl + W | Delete the word before the cursor
Ctrl + T | Swap the last two characters before the cursor
Esc + T | Swap the last two words before the cursor
Ctrl + R | Lets you search through previously used commands
Ctrl + L or Command + K or Typing the word 'Clear' | Clears the screen
Ctrl + C | Kill whatever you are running
Ctrl + D | Exit the current shell
up arrow | Last command ran
