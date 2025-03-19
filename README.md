# USACO-Boilerplate-Generator
A fast and configurable boilerplate generator for any USACO problem.

## Default config.txt
```
[Input]
# ask to confirm details
confirm_details = yes
# clear screen to improve readability
clear_screen = yes
# always ask for commands?
copy_commands = yes

[File Generator]
# folder to insert problems
problem_folder = ../problems/
# create a nested folder to store the problem and input (recommended)
create_folder = yes

# for problems that use the newer standard input
stdin_boilerplate = boilerplate-new.txt
# for problems that use default file based input
file_boilerplate = boilerplate-old.txt

# custom command to copy
copy_command = cd problems/{filename}
```
