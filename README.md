# xx86 Documentation
Welcome to the CRX xx86 Documentation.

---

# Introducing xx86
The CRX xx86 computer architecture is a CISC (Complex Instruction Set Computing) system. Our architecture was designed specifically for the CRX986-1400 and CRX986-1400 processors.

---

# Basic Commands
The low-level language designed for xx86 is not standard Assembly. Assembly only supports x86. We use Barassembly + C, a powerful hybrid language.

`add` is the **addition** command. It’s used to perform simple or complex sums.  

Example:
```Barssembly
mov ex, ax
mov ax, 13
mov ex, 1
add ax ex, bx
exib "The result of 13+1 is: "+bx
```
Explanation of new commands

exib prints text to the screen. You need to configure the BIOS/UEFI to display text; otherwise, exib may output unreadable characters.

mov ax, <number> initializes an internal variable in the register with the specified number.

add ax ex, bx adds the values in ax and ex and stores the result in bx. In the example above, exib outputs: "The result of 13+1 is: 14".



---

Additional Commands

sub ax bx, cx – Subtracts the value in bx from ax and stores the result in cx.

mul ax bx, dx – Multiplies ax by bx and stores the result in dx.

div ax bx, dx – Divides ax by bx and stores the quotient in dx.

jmp <label> – Jumps to a specific label in the code.

cmp ax bx – Compares ax and bx and sets flags for conditional operations.



---

Notes

Always initialize your registers before performing arithmetic operations.

Ensure your BIOS/UEFI is configured correctly for text output when using exib.

Barassembly + C allows mixing high-level logic with low-level instructions for flexible programming.



---

Example Program

mov ax, 10
mov bx, 5
add ax bx, cx
exib "10 + 5 = " + cx

sub ax bx, dx
exib "10 - 5 = " + dx

This program demonstrates addition and subtraction with register storage and text output.


---

Conclusion

The CRX xx86 architecture and Barassembly + C language provide a powerful environment for low-level programming with enhanced control over hardware. Understanding the basic commands and register operations is the first step to mastering this system.
BUT, the documentation doesn't end here. It's just a glimpse of what's to come soon.
# All pages
→ [Home Page](https://github.com/AlanbusMaker/xx86_docs)
[How crx-cc works](https://github.com/AlanbusMaker/xx86_docs/blob/main/howcrxccworks.md)
[How to make a GUI in Barssembly xx86](https://github.com/AlanbusMaker/xx86_docs/howmakegui.md)

