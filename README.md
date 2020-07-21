# Practice Termux
![images](https://user-images.githubusercontent.com/66746496/88087571-90a38f00-cba2-11ea-81d0-8741b47742b5.png)

**What is Termux ?**

**Termux** is an Android terminal 
emulator and **Linux** environment app 
that works directly with 
no rooting or setup required. 
A minimal base system is installed 
automatically - additional packages 
are available using the APT **package manager**. 

**What can Termux Do ?**

**Termux** is a terminal emulator for **Android**. 
It can be considered to be more like a Linux 
distribution than just a terminal application 
due to a large number of available packages 
such as clang, FFmpeg, OpenSSH, Python, Vim.

**What is Termux API ?**

This is an app exposing Android **API**
to command line usage and scripts or programs. 
When developing or packaging, 
note that this app needs to be signed 
with the same key as the main **Termux** app 
for permissions to work 

(only the main **Termux** app are 
allowed to call the **API** methods in this app)

**Where are Termux files Stored ?**

The default directory is: */data/data/com. termux/files/home* .
Since Termux supports bash commands, 
user can run pwd to print current working directory.

**Termux Commands**

> Let's talk about basic commands of termux
> You will get the complete idea about termux

```
•Learn all Termux Basic to Advanced Commands
•Because it is necessary to learn the basic before anything
•You can execute these commands in a sequence to practice and know your self 
•how these commands work on termux.
```

**Update and Upgrade**

Update all the packages and dependencies installed on the system:
```
apt update && apt upgrade
```

![IMG_20200721_230710](https://user-images.githubusercontent.com/66746496/88090411-fd208d00-cba6-11ea-86ef-e48972c0170e.jpg)

If any update is available it will ask you on the terminal if you want to upgrade or not, press Y if you want the update

**storage permission**

Grant Storage Permission
```
termux-setup-storage
```
![IMG_20200721_231206](https://user-images.githubusercontent.com/66746496/88090868-a49dbf80-cba7-11ea-8cc3-00224c7d268d.jpg)

now you can access your Storage and all the folder in it using termux.

**Present Directory**

Know Which directory you are in:
```
pwd
```
![IMG_20200721_231550](https://user-images.githubusercontent.com/66746496/88091182-25f55200-cba8-11ea-8097-3c1ba8bbc9a0.jpg)

This command will tell you, your present working directory

**List**

List all the files and directories:
```
ls
```
![IMG_20200721_231919](https://user-images.githubusercontent.com/66746496/88091558-a6b44e00-cba8-11ea-9842-f20d57906270.jpg)

this command will show you the folder and files in your current working directory.

**Access/Enter Directory**

Move forward in directories:
```
cd storage   #storage as an example
```
![IMG_20200721_232301](https://user-images.githubusercontent.com/66746496/88091940-280be080-cba9-11ea-829f-5077ef09cd06.jpg)

cd command allows you to move in a folder just type cd and the folder name you wanna move here I am moving in storage.

**Last Directory ( Backwards )**

Move backward in directories:
```
cd ..      # for 1 step back
cd ../..   # for 2 step back
```
![IMG_20200721_233101](https://user-images.githubusercontent.com/66746496/88092679-4a522e00-cbaa-11ea-90a6-8f7023820f32.jpg)

by typing cd ..(between cd and .. we have to put space) you will go back in the directory you were in.

**Terminal Clear**

Clear Screen:
```
clear
```
![IMG_20200721_233518](https://user-images.githubusercontent.com/66746496/88093040-de23fa00-cbaa-11ea-92a6-1a044b95fa3d.jpg)

by typing clear in the termux you can clear all the previous results.

**Create Directory**

Create a folder or a directory:
```
mkdir [ folder name ]  # without []
```
![IMG_20200721_233958](https://user-images.githubusercontent.com/66746496/88093499-85a12c80-cbab-11ea-890a-0062889ae9d6.jpg)

Mkdir Stand for make directory. Type mkdir and give a space and type folder name and press enter.
I created a **newfolder** name directory with this command **mkdir newfolder** and then I used **ls** to see the directory

**Remove Directory 🗑️**

Delete a folder or a directory:
```
rmdir folderName
```
![IMG_20200721_234504](https://user-images.githubusercontent.com/66746496/88093985-3c051180-cbac-11ea-85c4-906608b238b5.jpg)
Please use this command with caution.This command will remove a folder and all the files and folders within it.This command is useful when you want to delete any project downloaded from Github.

In the last command we created a directory named **newfolder** and with this command we removed that **directory** successfully

**Copy**

Copy a file from one directory to another directory:
```
cp file-name file-path
```
![IMG_20200721_235301](https://user-images.githubusercontent.com/66746496/88094660-5e4b5f00-cbad-11ea-84af-2d287dbee7dd.jpg)

You can copy files by typing cp the file name and after giving a space you can type the path where you wanna copy the file E.g: cp Word-Generix /storage/shared this will copy the Word-Generix to the storage/shared folder.

**Search Package 🔎**

Search for the specific package in termux:
```
pkg search package-name
```
