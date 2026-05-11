# 0x00-shell_basics

## Project Description

This project introduces the basics of Linux shell navigation and file system operations. It focuses on understanding the current working directory, listing files, handling hidden files, and basic directory navigation using standard Bash commands.

## Learning Objectives

By the end of this project, you should be able to:

* Identify your current working directory
* List files and directories
* Use long format listings
* Display hidden files
* Navigate to the home directory

---

## Tasks

### 0. Where Am I?

* **File:** `0-current_working_directory`
* **Description:** Prints the absolute path of the current working directory.
* **Command used:** `pwd`

### 1. What’s in There?

* **File:** `1-listit`
* **Description:** Displays the contents of the current directory.
* **Command used:** `ls`

### 2. There’s no Place Like Home

* **File:** `2-bring_me_home`
* **Description:** Changes the working directory to the user's home directory.
* **Command used:** `cd`

### 3. The Long Format

* **File:** `3-listfiles`
* **Description:** Displays directory contents in long format.
* **Command used:** `ls -l`

### 4. Hidden Files

* **File:** `4-listmorefiles`
* **Description:** Displays all files including hidden files in long format.
* **Command used:** `ls -la`

---

## Repository Structure

```
system_engineering-devops/
└── 0x00-shell_basics/
    ├── 0-current_working_directory
    ├── 1-listit
    ├── 2-bring_me_home
    ├── 3-listfiles
    └── 4-listmorefiles
```

## Requirements

* Scripts must be executable (`chmod +x file`)
* Scripts must be written in Bash
* No use of advanced scripting beyond basic shell commands

## Usage Example

```bash
$ chmod +x 0-current_working_directory
$ ./0-current_working_directory
/home/user/0x00-shell_basics
```

