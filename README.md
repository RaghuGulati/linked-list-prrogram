# linked-list-prrogram

## Makefile

### Compile


### Run


### Clean


## Manual compilation and run

### Solution1

First go to directory src/1a using command:

      cd src/1a/
      It has two files namely: a4q1a_int.c and a4q1a_char.c

#### Compile

      gcc a4q1a_int.c -o a4q1aint
      This will make an executable file named a4q1aint

      gcc a4q1a_char.c -o a4q1achar
      This will make an executable file named a4q1achar

#### Run

      ./a4q1aint cmd.txt
      ./a4q1aint
      (This will ask the commands from user and user can end giving input using ctrl+D)

      ./a4q1achar cmd.txt
      ./a4q1achar
      (Similar as ./a4q1aint)
      
      The commands available are:
      
       - a = append with syntax: 
            a key value for a4q1a_int.c
            a string for a4q1a_int  
       - p = push similar to a but the command will contain p instead of a
       - rem_first 
       - rem_last
       - rem_small
       - rem_large
       - empty
       - size 
       - print_all 
       - print_sort

