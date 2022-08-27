# Skilstak Boost 2022 week 2

We'll be covering today a handful of tools, philosophies and good ol' learning habits.

### Windows Terminal

We'll be using Windows Terminal from this point since we need to SSH into Windows with Ubuntu server. 

* Easier to use the CLI
* practical

### What's Unix and Linux ?

**Unix** is an operating system, multiuser at Bell labs by AT&T. It's written in C, since the first version was written in assembly and was terribly difficult to code.
Ken Thompson developed the C language(with Dennis Ritchie) so it could develop the next version of  **UNIX**. Ken also developed the B language. Ken later on would become the inventor of 
GO language together with Rob Pike. The UNIX operating system became popular and it allowed the license of the OS, it led to the development of Solaris("Sun Microsystems"),Berkeley Software Distribution(BSD by the University of Berkeley,CA), also Xenix(Microsoft), HP-UX( HP/HPE) and so on.

**Linux** on the other hand was developed by Linus Torvalds in september 17, 1991. It's based on minix, a version unix written by Linus's professor and it didn't exactly made him feel comfortable with that OS, so Linus created his own version of minix( he didn't know the existence of BSD, but anyway). Linux is among the most famous linux/unix based distributions and it's open source.

### What's GNU and who invented Linux ?

GNU is an operating system which is part of the free software movement. It has packages and free software released by third parties. It was created Richard Stallman
in 1984. It's a unix-like system, so it has libraries and dev tools. As I said earlier, linux was invented by Linus Torvalds in 1991, based on minix, a unix-like system.

### How to update the system

You can update a debian based distro using the apt package management. You can also install software by using 'sudo apt install' or 'sudo apt-get install'.

### What's an **inode** ?

An inode is a file data structure that stores information about any Linux file except its name and data. 

### Why is everything a file ?

The unix filesystem is present everywhere, there's always a hierarchy(tree-like) between root, folders and files. If you plug your phone into a Windows OS, you'll 
see the file structure present in your phone.

### What are UNIX/LINUX permissions ?

There's a risk of an user removing, modifying and deleting a crucial file, so Linux has assigned two types of security :

1. Ownership
2. Permission

When it comes to ownership, there's three types of user:

1. User

* The creator of the file, so basically the owner.
2. Group

* A user group can contain multiple-users.  All users belonging to this particular group will have the same access to this file. you could add all users to a group, and assign group permission to file such that only this group members and no one else can read or modify the files.

3. Other

* Someone who doesn't belong to a user, neither a group, so anyone has access to this file.

### commands we should get used to:

* **ls**: we use this to list files
* **ls -a**: it shows all the files including hidden ones
* **pwd** shows the working directory
* **hostname** shows the computer's host
* **cd** stands for current directory and will do the thing it's named after.
* **cd /** will change dir to root dir.
* **cd ~** change dir to home dir.
* **cd ..** will move you to the parent dir, example /home/livingroom/bathroom/sink | /home/livingroom/bathroom
* **apt** it stands for advanced packging tool, used to update, upgrade and manage software packages( for script use apt-get)
* **apt update** updates the sources for the packages
* **apt upgrade** updates packages to the latest version
* **sudo** it's superuser, do it as a root
* **man** to check all availables manuals


