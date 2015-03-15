# LESSON PLAN:: COMPUTER PROGRAMMING SERIES - EMBEDDED LINUX 101

NOTE: missing are the pipe and read/write from/to STDOUT and STDERR
```
#pipes stdout to outputfile
somescript.sh > outputfile

#pipes stderr into outputfile
somescript.sh 2> outputfile 

#accepts contents of inputfile and outputs stdout to outputfile
somescript.sh <(cat inputfile) > outputfile
cat inputfile |somescript.sh  > outputfile

#Piping
somescript.sh | somescript2.sh > some file
```

# Introduction

* What is a raspberry PI
* What is a OS
* What is LINUX
 * Brief history
  * Linus Kernal
 * CLI vs GUI
* X86_64 vs ARM CPU architecture

# DEMO using CLI

RaspberryPI connected via HDMI to MONITOR and KEYBOARD (w MOUSE optional)

# PART 1 - Connecting with ur PI remotely

Wesley
* What is SSH
* Why remote logins make sense for embedded systems
* Security ISSUES
  * Password login vs Passwordless login with `ssh-keygen` and `id_rsa.pub`.

**Suggestion** include fixing of IP address and short section on finding your IP address (windows and mac)


# Part 2 - Directory Structure of Linux

* Directory structures

| Folder | explanation |
| `/dev` |             |
| `/etc` |             |
| `/usr` |             |

useful commands like `tree`, etc.

* moving about in the filesystem

Use [explain shell](explainshell.com)

| Command | Explanation      |
| cd      | move into folder |
| ls      |                  |
| ln      | link             |
| rm      |                  |
| mv      | rename/move      |
| etc     |                  |

# PART 3 - Connecting and controlling LED with PI GPIO

## Enabling GPUIO

| Skill             | Task               | Comments                                                                                                                                                            |
| Using TextEditors | Config file        | Although it would be best to teach nano, it might be wiser to just start off with vi since `git commit` and `git merge` messages are going to be call vi by default |
| Permissions       | run `sudo apt-get` | from adafruit tutorial (lesson 4: GPIO setup), talk about the advantages and more of the disadvantages of using superuser mode; how commands staring with `#` and `$` mean different things and why tutorials online usually add the former in front of their commands                                                                                                                                                                     |


1. Similarly learn how to remove software using apt-get `purge` vs `uninstall`
2. run the following command `sudo apt-get install` for (pythong gpuio module)
3. Adding sources to ur package list? the debian src
4. difference bet <package>-dev  and plain <package>

## Setting up the hardware

Breadboard, leds

# PART 4 - IoT Communicating with between raspberry PIs remotely thru the web

Up to now, only shows how to connect to the PI with it still tethered to the laptop via an ethernet cable.

# Equipment

| Quantity | Description                                                          |
| ----     | ----                                                                 |
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

Please feel free to add.
