# xx86 Documentation 
Welcome to CRX xx86 Documentation.
---
# Introducing xx86
-
The CRX xx86 computer architecture is a CISC (Complex something). Our architecture was designed specifically for our CRX986-1400 and CRX986-1400 processors.
---
# Basics commands
The low-level language designed for x86 is not Assembly. Assembly only has support for x86. We use the Barassembly + C language. A powerful language.

`add` it's command of **sum**. Basically, it's used to perform complex or simple sums.
Example:
```Barssembly
mov ex, ax
mov ax, 13
mov ex, 1
add ax ex, bx
exib "The result of 13+1 is: "+bx
```
## Explanation of new commands:
-
`exib` It prints to the screen, but you need to configure the BIOS/UEFI to display text; otherwise, when using `exib` it displays literally garbage.
`mov ax, <number>` Apparently (and yes), this command creates an internal variable with numbers based on the register.
`add ax ex, bx` It adds 13 + 1, and `exib` shows the result (in this case: "The result of 13+1 is 14").
--
Finish the documentation after 
