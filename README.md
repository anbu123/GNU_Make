# GNU_Make

# 🛠️ GNU Make: Learning Repo

### 📅 Day 1: Basics of Make

This repository is for learning how `make` works.

---

## 🧩 What is a Makefile?

A **Makefile** automates the process of building executables. It uses **rules** that describe how to build targets from source files.

---

## 📦 Rule Structure

A basic rule in a Makefile looks like this:

## Day 1: Basic of Make
Target - Output file (Ex: App.exe or main.o)
Prerequisites - main.c 
receipes - Actual command that excutes series cmds to build 

### Example :

```make 
main.o : main.c
	arm-none-eabi-gcc main.c -o main.o
	
 we can simplify the commands using variables. 

Example:
main.o : main.c
	$(CC) main.c -o main.o
	


