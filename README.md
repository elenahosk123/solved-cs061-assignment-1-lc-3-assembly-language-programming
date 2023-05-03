Download Link: https://assignmentchef.com/product/solved-cs061-assignment-1-lc-3-assembly-language-programming
<br>
The purpose of this assignment is to familiarize you with the basics of LC-3 assembly language programming, the SIMPL emulator, and rudimentary debugging.

Your Tasks

Implement the LC-3 program from the image below.

<strong>Note</strong>​: This is similar to, but not ​<em>quite</em>​ the same as, the program you worked on in Lab 1: it uses a DO-WHILE loop to multiply two numbers together.

First (as with all your labs and assignments) go to the Assignment folder in <u>​</u><a href="https://piazza.com/">Piazza</a>​, and download the assignment 1 zip file to your assignments/assn1 folder in your cs account, and unzip it in place.

Type the code from the image into your assn1.asm file ​<em>(again, the registers are assigned differently from your Lab 1 exercise, so </em>​<strong><em>don’t</em></strong>​<em> copy that!)</em>​: geany assn1.asm &amp;

and then launch &amp; run simpl: simpl assn1.asm &amp;

<strong><em>Remember</em></strong>​<em>: whenever you run simpl, you must </em><u>​<em>ALWAYS</em></u>​<em> keep the Text Window open so you can see warnings &amp; error messages from the emulator! </em>

When the emulator opens, place a ​<em><u>breakpoint</u></em>​ at the <u>​beginning</u>​ of the DO-WHILE loop by right-clicking that line of code and selecting “Mark as Breakpoint”.

Lastly, create a table in your .asm file (below the header, above the code) to record the register contents for <u>​<em>each</em></u>​ register (R0 through R7) as you step through the program, as follows:

<ul>

 <li>Before entering the loop (i.e. the first time the program halts at the breakpoint)</li>

 <li>After each iteration of the loop (each subsequent breakpoint halt)</li>

 <li>Note that since your breakpoint is at the start of the loop, the register values after the <em><u>last</u></em><u>​ </u> iteration will just be the values when the program has ended, as suggested by the naming of the last row in the image below.</li>

</ul>

<em>How many rows do you think you will end up with in your table? </em>

Record the table just like the one in the image below ​<em>(but obviously with the actual values from </em>​<strong><em>ALL</em></strong><em> your registers for </em>​<strong><em>ALL</em></strong>​<em> iterations of the loop!) </em>

The following program performs the action:

<strong>R3 &lt;– 12 * 6   ; (i.e. multiply 12 by 6 and write the result into Register 3)</strong>  using the equivalent of a DO-WHILE loop:




<strong> </strong>


