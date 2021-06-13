# Stack-Based Buffer Overflows on Linux x86

### overview

Buffer overflows are common vulnerabilities in software applications that can be exploited to achieve remote code execution (RCE) or perform a Denial-of-Service (DoS) attack. These vulnerabilities are caused by insecure coding, resulting in an attacker being able to overrun a program's buffer and overwrite adjacent memory locations, changing the program's execution path and resulting in unintended actions.


 ### Module Summary
 
 This module introduces buffer overflow attacks, principles such as CPU architecture and CPU registers, and walks through the basics of exploit development and shellcode generation. We will also walk through a public exploit proof of concept and cover techniques for preventing these types of attacks.

In this module, we will cover:

-   An introduction to buffer overflows
-   The basics of exploit development
-   Dealing with shellcode length and bad characters
-   Public exploit modification
-   Buffer overflow prevention

This module is broken down into sections with accompanying hands-on exercises to practice each of the tactics and techniques we cover. The module ends with a practical hands-on skills assessment to gauge your understanding of the various topic areas.

As you work through the module, you will see example commands and command output for the various topics introduced. It is worth reproducing as many of these examples as possible to reinforce further the concepts introduced in each section. You can do this in the Pwnbox provided in the interactive sections or your own virtual machine.

You can start and stop the module at any time and pick up where you left off. There is no time limit or "grading," but you must complete all of the exercises and the skills assessment to receive the maximum number of cubes and have this module marked as complete in any paths you have chosen.

The module is classified as "Medium" but assumes a working knowledge of the Linux command line and an understanding of information security fundamentals.

A firm grasp of the following modules can be considered prerequisites for successful completion of this module:

-   Introduction to Networking
-   Linux Fundamentals