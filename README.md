# Awesome command line for master bioinformatics students

<img src='https://github.com/kluwik/command_line/blob/main/img/header.jpg?' width=500>

__Methodology__

This repo provides methodology and materials for teaching command line to first-year master bioinformatics students with little or no programming background. The methodology was implemented at Skoltech 6-credit Bioinformatics course (2 three-hour seminars) and recieved positive students feedback.

In the beginning of the course tutorial is shared with students. Students study the tutorial independently at home within two weeks. In parallel with tutorial students complete pass/fail quizzes on each topic of the tutorial in LMS for self-assessment. After completing the first three chapters of the tutorial, the students come to the practice seminar and solve practical exercises and recieve home assignment on completing a task in the command line. Then students complete the rest of the tutorial and come to the second seminar on practicing scripting.

<img src='https://github.com/kluwik/command_line/blob/main/img/command_line_schedule.jpg?' width=500>

## Self-study tutorial

Tutorial is available at https://kluwik.gitbook.io/command-line

<details><summary>Contents</summary>

__Introduction__

- How to work with this tutorial
- About command line
- [Windows users only] Installing Windows Subsystem for Linux
- Log in to a remote server

__Navigation, operations with files and directories__

- Directories, navigation
- Full and relative paths
- Operations with files and directories

__Text search and processing__

- Chaining commands
- Find matching word or pattern: grep
- [Extra] Text processing

__Terminal tricks__

- Filenames expansion
- Running processes in the background: screen
- Setting path to executables: PATH and .bashrc
- [Extra] Connect to server without a password
- [Extra] GUI in terminal: VS Code, Jupyter Lab
- [Extra] Custom commands: aliases

__Scripts__

- Bash scripts basics
- Variables
- Iteration: for-loop
</details>

## Example of questions for quizzes

```bash
What commands will delete an empty directory dir/?

rmdir dir/
rm -rf dir/
rd -rf dir/
rd dir/
rm dir/
```

```
How can one go from /Users/bob/Desktop/work/ to /Users/bob/Desktop/ without typing the path explicitly? 
cd ../
cd ~
cd ./
cd .
cd ..
```

## Practice seminars



## Home assignment

https://github.com/kluwik/command_line/blob/main/Assignment.md
