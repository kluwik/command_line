# Awesome command line for master bioinformatics students

<img src='https://github.com/kluwik/command_line/blob/main/img/header.jpg?' width=300>

__Methodology__

This repository provides a methodology and teaching materials for introducing the command line to first-year master's students in bioinformatics who have little or no programming experience. The methodology was implemented in a 6-credit Bioinformatics course at Skoltech, which included two three-hour practical seminars, and received positive feedback from students.

At the start of the course, students are given a tutorial for independent study over a two-week period. Alongside the tutorial, they complete pass/fail quizzes in the LMS covering each topic, allowing them to assess their understanding as they progress.

After completing the first three chapters of the tutorial, students attend the first practical seminar, where they work on hands-on exercises and receive a take-home assignment that requires solving a bioinformatics task using the command line. They then complete the remaining chapters of the tutorial before attending the second seminar, which focuses on shell scripting and automation.

While the tutorial and quizzes are designed to develop and assess knowledge of command-line concepts and commands, the practical seminars and assignments focus on applying these skills to solve realistic bioinformatics problems.

The key component of this methodology is the self-study tutorial. It eliminates the need for a dedicated introductory seminar, allowing students to learn the fundamentals at their own pace and assess their understanding through quizzes. This approach frees up classroom time for hands-on practice and problem-solving activities. If a traditional lecture format better suits your course, a presentation version of the tutorial is also available [here](https://github.com/kluwik/command_line/blob/main/CLI_seminar_version_of_tutorial.pdf).

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

[Practice seminar 1](https://github.com/kluwik/command_line/blob/main/CLI_practice_seminar_1.pdf)
[Practice seminar 2](https://github.com/kluwik/command_line/blob/main/CLI_practice_seminar_2.pdf)

## Home assignment

https://github.com/kluwik/command_line/blob/main/Assignment.md
