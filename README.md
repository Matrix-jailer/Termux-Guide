# Practice Termux
![images](https://user-images.githubusercontent.com/66746496/88087571-90a38f00-cba2-11ea-81d0-8741b47742b5.png)

## Download Termux 

Download Termux for your Device

![images (1)](https://user-images.githubusercontent.com/66746496/88103171-14b54100-cbba-11ea-830c-66735e1a4029.png)
**Andorid** [Download](https://www.google.com/url?sa=t&source=web&rct=j&url=https://play.google.com/store/apps/details%3Fid%3Dcom.termux%26hl%3Den&ved=2ahUKEwjK2c_PlN_qAhXK3oUKHf_5DjMQjjgwA3oECAQQAQ&usg=AOvVaw2M6YzJbU8xcF1t0fL_d2rE)
![images (3)](https://user-images.githubusercontent.com/66746496/88103278-37475a00-cbba-11ea-97e8-6037ae13e83b.png)
**PC** [Download](https://sanyodigital.com/termux-for-pc/)


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

**storage permission 🗃️**

Grant Storage Permission
```
termux-setup-storage
```
![IMG_20200721_231206](https://user-images.githubusercontent.com/66746496/88090868-a49dbf80-cba7-11ea-8cc3-00224c7d268d.jpg)

now you can access your Storage and all the folder in it using termux.

**Present Directory 📂**

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

**Create Directory 📁**

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

You can copy files by typing cp the file name and after giving a space you can type the path where you wanna copy the file E.g: cp Word-Generix /sdcard this will copy the Word-Generix to the /sdcard folder.

**Search Package 🔎**

Search for the specific package in termux:
```
pkg search package-name
```
![IMG_20200722_002424](https://user-images.githubusercontent.com/66746496/88097548-be440480-cbb1-11ea-80d1-9b8816631936.jpg)

It will show you all the package related to that package name.

I searched for zip package and got 1 search result.

**All Packages 💯**

List all the available packages in termux:
```
pkg list-all
```
![IMG_20200722_002802](https://user-images.githubusercontent.com/66746496/88097833-3dd1d380-cbb2-11ea-9ef1-04592cd53f15.jpg)

it will show you all the packages that are available in the APT repository of termux.
 
It will show hundred of packages I can't show all of them

**Package Installation**

Install a Package:
```
pkg install package-name
```
![IMG_20200722_003224](https://user-images.githubusercontent.com/66746496/88098242-e1bb7f00-cbb2-11ea-9770-a8ebd4d659d5.jpg)
![IMG_20200722_003215](https://user-images.githubusercontent.com/66746496/88098236-dff1bb80-cbb2-11ea-9054-cb119f798031.jpg)

you can install any package from the list, just type pkg install package-name.

I installed unzip package as an Example...

**Package Uninstallation**

Uninstall a Package:
```
pkg uninstall package-Name
```
![IMG_20200722_003610](https://user-images.githubusercontent.com/66746496/88098539-5e4e5d80-cbb3-11ea-9898-591b24bcf8b3.jpg)

you can uninstall any package from the list, just type pkg uninstall package-name.it will ask you where if you wanna delete the package or not press y and the package will be uninstalled.

In the last command we installed unzip package
With this command we removed it successfully

**Install Python 🐍**

Install Python in termux:
```
pkg install python
```
![IMG_20200722_004050](https://user-images.githubusercontent.com/66746496/88098994-082dea00-cbb4-11ea-8f11-35674bdc0ab9.jpg)

I had already installed

Just type this command and it will be installed in your termux press y if it asks for confirmation.after installing python you can write code and also run your own python scripts. Type python to check if **python** is properly installed or not

**Install Git**

Install Git in termux:
```
pkg install git
```
![IMG_20200722_004433](https://user-images.githubusercontent.com/66746496/88099437-97d39880-cbb4-11ea-8b11-60ac33d92c99.jpg)
![IMG_20200722_004445](https://user-images.githubusercontent.com/66746496/88099422-94401180-cbb4-11ea-8f67-b3f48c740e82.jpg)

Git will allow you to download any project from the github.

**Clone GitHub Tools/Repositories**

Download projects from GitHub repository :
```
git clone Link-of-the-project
```
![IMG_20200722_005158](https://user-images.githubusercontent.com/66746496/88100141-93f44600-cbb5-11ea-83fa-1ecafb30271f.jpg)

If you want to download any project from the git hub you can just use the above just change the Link-of-the-project with your link
e.g: git clone https://github.com/Matrix-jailer/Word-Generix.git

**Open Text-File**

See what's inside a text file:
```
cat file-name
```
![IMG_20200722_005813](https://user-images.githubusercontent.com/66746496/88100779-770c4280-cbb6-11ea-8ae6-ba5730050610.jpg)

Run this command and everything in the text file will be printed on the terminal.
e.g: cat info.txt

**Installed Packages**

List all the installed Packages in termux:
```
dpkg --list
```
![IMG_20200722_010307](https://user-images.githubusercontent.com/66746496/88101271-2fd28180-cbb7-11ea-9eac-55961709d503.jpg)
![IMG_20200722_010223](https://user-images.githubusercontent.com/66746496/88101244-2d702780-cbb7-11ea-8dfe-bd736bc6653b.jpg)

By Using this command You will be able to see all the installed packages in your termux app.

**THE END 🙅‍♂️**

> I know there are Hundreds of things remaining but I included the most common commands 

> If you want to contribute ❤️ just fork and open a pull request

# About Author
```
FOUNDER OF MATRIX SOCIETY 🔍
Coded by Matrix
```
```
Noob Hacker 👨‍💻
Basic Programmer 🔡
Drunk Teacher 🍻
```
### Fork
```
Fork this repository by clicking on the fork button on the top of this page. 
This will create a copy of this repository in your account.
```
### Contact
```
WhatsApp > +923130215090
```
```
Email    > Matrixjailer@gmail.com
```
### Contribution
```
If you want to contribute here 
just fork and open a pull request. 
if you have any suggestions to improve this project 
just open an issue.
Found a Problem in Code ?
Open issue asap :-)
```
### Donate
BITCOIN ADDRESS
```
13Gau2D3gjTfCmx7dKjSyZETDH182ZS8ox
```
