---
name: Kevin Marcelo-Castillo
semester: Fall 2023
course: CIS 106 Linux Fundamentals
---

# Week Report 8

## What is VIM? 
VIM is a command-line text editor that is based on Vi. VIM stands for "vi improved".

## What is nano?
nano is a small and user-friendly command-line text editor that has features, such as opening multiple text files and line numbering.

## How to start and quit VIM
The command `vim` starts VIM. To quit VIM, go to the command mode by pressing `:` and type `:q!` to quit VIM without saving the file.

## Different VIM modes
**Insert mode:** used for writing text. To enter insert mode, input `i` 
**Normal mode:** used for manipulating text. To enter normal mode, input `esc` or `ctrl + c`
**Command mode:** used to enter vim commands. To enter command mode, input `:`
**Visual mode:** used to navigate through text. To enter visual mode, input `v`
**Select mode:** similar to visual mode
**Ex-mode:** similar to command mode

## How to insert text in VIM 
In vim, press `i` to enter insert mode and input text.

## How to save a file in VIM
In vim, press `:` to enter the command mode and input `:w` to save the file. To save the file and quit vim, input `:wq!`

## How to search for a word inside VIM
To search for a word inside vim forward, input `/ + word you are looking for`. To search backwards, input `? + word you are looking for` Inputting the letter n will repeat the search for the next word.
**Example:** `/pizza`, `?pizza`

## How to delete text in VIM
The command `dw` deletes the current word. `dd` deletes the line under the cursor. `d + /word` deletes until the word is given.