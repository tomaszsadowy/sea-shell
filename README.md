
<h1 align="center">
  <img src="https://github.com/user-attachments/assets/4ccd3427-e612-4c64-9e18-bd0ef7046f5b" width=250>
</h1>

<p align="center">
  <i>A Unix-like shell, built in C 🌊</i>
</p> 

## Introduction

**sea shell** is a simple, custom command-line shell written in C. It provides basic shell functionalities such as executing commands, handling pipes, and maintaining a command history through arrow keys. The shell supports built-in commands like `cd`, `echo`, `export`, `pwd`, `unset`, `help`, `exit`, `history`, and `grep`. Additionally, it features autocompletion for these commands using the readline library.
## Installation
1. Clone the git repository using:
   ```sh
   git clone https://github.com/tomaszsadowy/sea-shell.git
   ```
2. Navigate to the directory in your terminal and execute:
   ```sh
   ./sea
   ```
3. You may need to install the readline library if you haven't already:

   On MacOS:
   ```sh
   brew install readline
   ```
   On Windows:
   ```sh
   x
   ```

## Usage

Once the shell is running, you can start typing commands. Here are some basic operations you can perform:

- **Execute Commands**: Type any valid shell command and press Enter.
```sh
> ls -l
```

- **Change Directory**: Use the cd command to change the current directory.
```sh
> pwd
```

- **Print Working Directory**: Use the pwd command to display the current directory.
```sh
> cd /path/to/directory
```

- **Echo Text**: Use the echo command to display a line of text.
```sh
> echo "Hello World!"
```

- **Set Environment Variables**: Use the export command to set environment variables.
```sh
> export VAR=value
```

- **Unset Environment Variables**: Use the unset command to remove environment variables.
```sh
> unset VAR
```

- **Show Command History**: Use the history command OR **Up and Down Arrow Keys** to display the list of previously executed commands.
```sh
> history | Up/Down Arrow Keys
```

- **Search with Grep**: Use the grep command to search for patterns in files.
```sh
> grep "pattern" file.txt
```

- **Exit the Shell**: Use the exit command to exit the shell.
```sh
> exit
```

- **Autocomplete Commands**: Press the Tab key to autocomplete built-in commands.
```sh
> ec[TAB] -> echo
``` 
- **Pipe Commands**: Use the | symbol to pipe the output of one command to another.
```sh
> ls -l | grep "pattern"
``` 
