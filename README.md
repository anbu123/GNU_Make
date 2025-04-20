# GNU_Make
This repo is for my learning purpose

Day 1: Basic of Make

Target - Output file (Ex: App.exe or main.o)
Prerequisites - main.c 
receipes - Actual command that excutes series cmds to build 

Example :

main.o : main.c
	arm-none-eabi-gcc main.c -o main.o
	
we can simplify the commands using variables. Ex : CC = arm-none-eabi-gcc so that $(CC) will be replaced later.

After adding CC variables - File will look like this

Example:
main.o : main.c
	$(CC) main.c -o main.o
	


