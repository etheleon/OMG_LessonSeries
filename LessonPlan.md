# LESSON PLAN

# Introduction

* Whats a raspberry PI
* Whats a OS
* What is LINUX
 * CLI vs GUI
* X86_64 vs ARM CPU architecture

# DEMO using CLI
raspberry connected with MONITOR and KEYBOARD (MOUSE optional)

# PART 1 - Connection
SSH :: (Wesley)
* What is SSH
* remote access of your raspberry PI


# Part 2 - Directory Structure 
Moving round the CLI


# PART 2 - Connecting and controlling LED with PI GPIO

## Enable GPUIO 
 - Config file (editing with TEXTeditor: eg NANO)
 - u

## User permissions
* why run `sudo apt-get`
 * from adafruit tutorial (lesson 4: GPIO setup)

Sudo apt-get install (pythong gpuio module)

## Practical: Raspberry LED 

# PART 3

communicating with another raspberry PI thru SSH


### Equipment

| Quantity | Description                                                          |
|          | Jumpper cables                                                       |
|          | Raspberry PI                                                         |
|          | Ethernet Cables                                                      |
|          | Convertors for laptops without ethernet ports                        |
|          | MONITOR                                                              |
|          | KEYBOARD                                                             |
|          | ethepad with the class links ahead of time + chat+ help links        |
|          | SD cards with image set up that will do the blinking lights exercise |
|          | pi with accuators to SSH into to control                             |
|          | LEDS                                                                 |
|          | PI Camera (optional)                                                 |
|          | Sticky notes for postits                                             |



NOTES by jookhai
=====

COMPUTER PROGRAMMING SERIES - EMBEDDED LINUX 101
(3 hours × 2 sessions)
Conducted By : Mr Wesley Goi
Format       : Workshop
Location     : Prototyping Lab @ National Design Centre

With embedded platforms like the Raspberry Pi, ODROID and Beaglebone becoming increasing popular and cheaper - more hardware developers are jumping onto the embedded Linux bandwagon.

Understand what Linux is all about, some basic shell commands for navigation, permissions and directories, installing packages as well as hardware I/O in this hands-on workshop!

In this workshop, you will …

- Understand the components of an Embedded System
-  Understand what is an Operating System, and what it does
- Know the history of Linux, and understand the advantages of using Linux for an embedded application
- Understand the file directory structure in Linux (e.g. ~, /, /dev, /etc, /usr)
- Practise using some basic shell commands (e.g. cd, rm, top, ls, ll) to navigate in the Linux shell environment
- Understand how to use the apt package manager to add, update and remove software packages
- Understand permissions, users and groups in Linux (e.g. sudo, root)
- Understand the re-direction and pipe operators in Linux (i.e. >, |)
- Practise doing simple hardware I/O operations on the Raspberry Pi
- Understand how authentication keys work, and the Secure Shell (ssh) method of remote Linux system administration

=====

COMPUTER PROGRAMMING SERIES - FUNDAMENTALS OF BASH SCRIPTING
(3 hours × 1 session)
Conducted By : Mr Wesley Goi
Format       : Workshop
Location     : Prototyping Lab @ National Design Centre

Shell scripting is a widely practised means of carrying out scheduled and procedural tasks in Linux. Be it data logging, routine administration or launching a set of programs and interfacing with hardware - a basic understanding of shell scripting is essential for working with an embedded Linux system.

In this workshop, you will …

- Know the difference between the sh and bash shells
- Know the syntax intrinsics of BASH scripting
- Understand how to (1) Implement basic control flow (i.e. conditionals and loops) (2) Perform file read/write operations (3) Conduct OS-specific operations (e.g. kill process, system shut-down, list connected USB devices) - in a BASH scripting context

=====

COMPUTER PROGRAMMING SERIES - FUNDAMENTALS OF REVISION CONTROL & GIT
(3 hours × 1 session)
Conducted By : Mr Wesley Goi
Format       : Workshop
Location     : Prototyping Lab @ National Design Centre

With embedded platforms like the Raspberry Pi, ODROID and Beaglebone becoming increasing popular and cheaper - more hardware developers are jumping onto the embedded Linux bandwagon.

Understand what Linux is all about, some basic shell commands for navigation, permissions and directories, installing packages as well as hardware I/O in this hands-on workshop!

In this workshop, you will …

- Re-visit the features of a Distributed Version Control System (DVCS), and how it facilitates effective backup and collaboration
- Explore the command line (shell environment) as well as Graphical User Interface (GUI) front-ends to Git
- Practice creating a Git repository as well as branches
- Practice using git init to set up a fresh repository
- Understand staging and committing, as well as good practices relating to these and commit messages
- Understand what branching is all about, and how it can facilitate team collaboration on a code base
- Practice merging code and resolving conflicts, using git diff
- Learn more about .gitconfig and .gitignore, and how to ensure that Git does not interfere with binary files (e.g. microcontroller HEX files, pictures)
