# bash-commands
This script contains the most commonly used bash commands, and shourtcuts

# variable 

local variable
--------------
my_var = 5

echo $my_var

or

alias ls='ls -l'


golbal variable
---------------
cd home/user/bin

touch my_file

write any command in file like: 

echo "bura haradi? $PWD"

make scripts executable (execution permissions):

chmod +x my_file  

or:
add alias ls='ls -l' command in .bashrc file


# copy  

cp

cp -r  Copy directory


# move and rename 

mv

mv -r  Move and rename directory


# remove 

rm

rm -r  Remove directory

rmdir  Remove directory



# search tools 

ctrl+r : Show last use of a command

'*' : Useing for any unit of each character exsist

'?' : Useing for one unit of each character exsist

example:

ls h*

ls f*e

find . -(i)name ""  -type d -size +100M 

which python: Show directory path of current python package

whereis python: Show directory path of all python packages



# history 

history

history | tail -4 : shows 4 last history

history | grep alias : show use of any cammand like "alias" in history



 # bash script

touch newcommand

nano newcommand # write any command in newcommand file like,

chmod +x newcommand #make scripts executable (execution permissions) 

./newcommand 


example of python code in bash:
-------------------------------
for i in 1 2 3;do python -c "x=$i;y=2;print(x+y)"; done

 

# svae output of command to file:

'>'   #appends output to a file or creates the file if it doesn't exist

'>>'  #overwrites the file if it exists or creates it if it doesn't exist


# view files in bash 

cat

cat file1 | grep "hesam" 

cat file1 | grep "hesam" -n

less: #similar to cat but show one page of datas

head: #similar to cat but show one page of head of datas

tail -4 :  #similar to cat but show 4 last line of datas



# Create empty directory and file 

mkdir   Directory

touch   File



# hot keys 

ctrl+d Exit from curent bash

ctrl+l Clean page

ctrl+r Show last use of a command



# root accsses 

su

sudo 



# other 

reboot

sleep 10s

echo

pwd

wildcards

