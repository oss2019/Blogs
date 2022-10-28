# Linux

## What  is Linux?

Linux is the most commonly used open source operating system, Unix-like operating system based on the Linux kernel.
It was first released on 17th September 1991, by **Linus Torvalds**.
Computer hardware and software can communicate with each other thanks to an operating system.

## Structure of Linux Operating System.

Linux operating system has following components:
1.  **Kernel**
    The foundation of the operating system is the Linux kernel. It creates a channel of communication for hardware and software. Additionally, it controls system resources. Its four duties are as follows:

    - __Device Management__: Numerous equipment, including the CPU, a memory device, sound cards, graphic cards, and others, are connected to a system. Device drivers, which are required for a kernel to control devices, are where a kernel keeps all the information linked to all of its connected devices. As a result, the kernel is aware of a device's capabilities and how to effectively utilise them. All of the gadget communication is also controlled by it. All devices must abide by the regulations set out by the kernel.    
    - __Memory Management__: The management of memory is another task that the kernel must perform. The kernel monitors the amount of used and free memory and ensures that programmes shouldn't use virtual memory addresses to interfere with one another's access to data.
    - __Process Management__: Prior to managing CPU to other processes, the management kernel allots sufficient time and prioritizes each process. It also deals with ownership and security details.
    - __Handling system calls__: Programmers can create queries or ask the kernel to complete tasks by handling system calls.

2.  **System Libraries**:
    System libraries are specialized applications that facilitate access to the functionality of the kernel. To execute a task, the kernel must be triggered, which is done by the apps. However, since each kernel has a unique set of system calls, programmes must be aware of how to use them. A common library of methods has been created by programmers to interface with the kernel. These standards are supported by all operating systems, and they are then translated into system calls specific to that operating system.

    _Glibc_ _(GNU C library)_ is the most used system library for Linux.

3.  **System Tools**:
    The utility tools included with the Linux operating system are typically straightforward commands. It is software that was created by the GNU project and released under its open source license, making it freely accessible to everyone.

    You may access your files, edit and manipulate the data in your directories and files, change the placement of files, and do a lot more with the aid of commands.

4.  **Development Tools**:
    Your operating system is up and running with the aforementioned three elements. You do, however, have extra tools and libraries to upgrade your system. Programmers create these extra tools and libraries, which collectively are referred to as the toolchain. A toolchain is a crucial development tool that programmers utilize to create a functional application.

5.  **End User Tools**:
    For a user, a system is distinctive thanks to these finishing tools. Although the operating system does not need end tools, a user does.


## Why should anyone use Linux?
Following are some features which answers the above question:

-  *Multiuser capability*: The same system resources, such as RAM, the hard drive, etc., are accessible by several users. But in order to function, they must utilize several terminals.
  
-  *Multitasking*: By wisely allocating the CPU time, several tasks may be carried out at once.
  
-  *Portability*: It's not always more portable if it can fit on a memory card or pen drive or has a smaller file size. It indicates that it supports a variety of hardware kinds.

-  *Security*: It provides security in three ways namely authenticating (by assigning password and login    ID), authorization (by assigning permission to read, write and execute) and encryption (converts file into an unreadable format).

-  *Live CD/USB*: Almost all Linux distros provide live CD/USB so that users can run/try it without installing it.

-  *Support's customized keyboard*: As it is used worldwide, hence supports different languages keyboards.

-  *Application support*: It has its own software repository from where users can download and install many applications.

-  *File System*: Provides hierarchical file system in which files and directories are arranged.

-  *Open Source*: Linux code is freely available to all and is a community based development project.


## How to use Linux ?
Linux may be used both from the terminal and through an interactive user interface (Command Line Interface). Although the user interfaces of various distributions vary significantly, practically all commands behave identically across all of them. Using the terminal, launch Linux by pressing "CTRL+ALT+T." Additionally, click the programme button in the bottom left corner of your desktop to learn more about its features.
