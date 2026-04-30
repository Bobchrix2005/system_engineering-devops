Shell, Init Files, Variables and Expansions
Project Overview

This project is part of the System Engineering & DevOps track. It focuses on understanding how the Linux shell handles:

Environment variables
Local variables
Shell initialization files
Shell expansions

By completing these tasks, you will learn how to customize your shell environment and write more dynamic and powerful Bash scripts.

Learning Objectives

At the end of this project, you should be able to:

Understand and create aliases
Work with environment variables and local variables
Modify and manipulate the PATH
Use shell expansions for arithmetic operations
Configure and use shell initialization files
Write scripts that interact with the shell environment
Repository Structure
system_engineering-devops/
└── 0x03-shell_variables_expansions/
    ├── 0-alias
    ├── 1-hello_you
    ├── 2-path
    ├── 3-paths
    ├── 4-global_variables
    ├── 5-local_variables
    ├── 6-create_local_variable
    ├── 7-create_global_variable
    ├── 8-true_knowledge
    ├── 9-divide_and_rule
    └── 10-love_exponent_breath
Requirements
All scripts must:
Be exactly 2 lines long

Start with:

#!/bin/bash
End with a new line

Scripts must be executable:

chmod +x filename
Tasks Description
0. Alias

Creates an alias:

alias ls="rm *"
1. Hello You

Prints a greeting to the current user:

hello <username>
2. Path to Success

Adds /action to the end of the PATH variable.

3. Count PATH Directories

Counts the number of directories in the PATH.

4. Global Variables

Displays all environment variables.

5. Local Variables

Displays:

Local variables
Environment variables
Functions
6. Create Local Variable

Creates a local variable:

BEST=School
7. Create Global Variable

Creates and exports a global variable:

export BEST=School
8. True Knowledge

Adds 128 to the value of:

TRUEKNOWLEDGE
9. Divide and Rule

Divides:

POWER / DIVIDE
10. Love Exponent Breath

Calculates:

BREATH ^ LOVE
Usage Examples
# Run script
./1-hello_you

# Source script (for environment changes)
source ./2-path
Important Notes

Use source or . when the script modifies the environment:

source script_name
Ensure correct file names and directory structure
Follow all naming conventions strictly (case-sensitive)
