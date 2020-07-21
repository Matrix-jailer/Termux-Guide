#    Practice Termux 
![images](https://user-images.githubusercontent.com/66746496/88087571-90a38f00-cba2-11ea-81d0-8741b47742b5.png)

#### [ + ] What is Termux ?

**Termux** is an Android terminal 
emulator and **Linux** environment app 
that works directly with 
no rooting or setup required. 
A minimal base system is installed 
automatically - additional packages 
are available using the APT **package manager**. 

#### [ + ] What can Termux Do ?

**Termux** is a terminal emulator for **Android**. 
It can be considered to be more like a Linux 
distribution than just a terminal application 
due to a large number of available packages 
such as clang, FFmpeg, OpenSSH, Python, Vim.

#### [ + ] What is Termux API ?

This is an app exposing Android **API**
to command line usage and scripts or programs. 
When developing or packaging, 
note that this app needs to be signed 
with the same key as the main **Termux** app 
for permissions to work 

(only the main **Termux** app are 
allowed to call the **API** methods in this app)

#### [ + ] Where are Termux files Stored ?

The default directory is: */data/data/com. termux/files/home* .
Since Termux supports bash commands, 
user can run pwd to print current working directory.

### Termux Commands

> Let's talk about basic commands of termux
> You will get the complete idea about termux

```
•Learn all Termux Basic to Advanced Commands
•Because it is necessary to learn the basic before anything
•You can execute these commands in a sequence to practice and know your self 
•how these commands work on termux.
```

### Update and Upgrade

Update all the packages and dependencies installed on the system:
```
apt update && apt upgrade
```

