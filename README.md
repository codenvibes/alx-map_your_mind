# **MAP YOUR MIND**
# Flowcharts
A flowchart is a visual representation of a process or algorithm that shows the steps in a sequence using symbols and arrows.
## Some commonly used ISO 5807 Flowchart symbols
[Flowchart Symbols](https://drive.google.com/file/d/1B62yypJmnVFTCwjVcQgAuojh9skLT2ws/view?usp=share_link "a title")
## Examples
Let’s think about Foundation task, and include a flowchart example for it: 

The task instructions are as follows: 

Write a function that draws a straight line in the terminal. 
- Prototype: `void print_line(int n);` 
- You can only use `_putchar` function to print 
- Where n is the number of times the character `_` should be printed 
- The line should end with a `\n` 
- If n is 0 or less, the function should only print `\n` 

Okay. Below is what I came up with. 
1.	Set a variable equal n (int `nCopy`) 
2.	Set up a while loop (condition: `nCopy` is greater than 0) 
3.	Print - 
4.	Decrease `nCopy` by 1 
5.	Print `\n` 

Now, using the ISO 5807 symbols from the table above, draw out a flowchart for this function.

[image](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/8/fb82e24f7282c569aed3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230429%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230429T125340Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=e736bbe4530c1c9ed52aee9ed174e7e28c38570b2bc4e78ecb0ffa5735f2b9ef)
## Bonus Info
Some good uses of flowcharts: 
- Create a flowchart before coding a task to either help create or validate pseudo-code 
- Add to a README.md to visually show how your project/process works 
- Use in a presentation to aide audience understanding 
- Your function or process is not working as expected? Create a flowchart of how it CURRENTLY is. Then, walk through the chart with some example input. 

A flowchart can be as high-level or as detailed as you want. For example, you could break the flowchart above down further to include what is happening in memory. You can even create flowcharts from your everyday non-technical experiences. Choosing a movie or a place to eat could be displayed as a flow-chart! 
A helpful tool to create flowcharts is draw.io. There are premade symbols for you to use and your diagrams can be saved to your Google Drive.
# What is pseudocode 
- Pseudo (not genuine; spurious or sham. "We are talking about real journalists and not the pseudo kind"  
Similar: bogus sham phoney imitation artificial mock) 
[https://www.youtube.com/watch?v=PwGA4Lm8zuE&t=5s](https://www.youtube.com/watch?v=PwGA4Lm8zuE&t=5s)
- It is a simpler version of a programming code in plain English before it is implemented in a specific programming language. (A semantic representation of a program in a natural language say English before it is implemented in a specific programming language)  
## How to Write Pseudocode 
Pseudocode doesn’t have a systematic/standard way of being written but here are some suggestions on how to write it: 
1.	Capitalize key commands (IF number is > 10 THEN..)  
2.	Write one statement per line. 
3.	Use indentation & whitespace. 
4.	Be specific. 
5.	Keep it simple: Don’t write pseudocode in a complete programmatic manner: It should be easy for a client to understand so don’t include too many technical terms. 
## Example (Fizz Buzz) 
Write a short program that prints each number from 1 to 20 on a new line. 

For each multiple of 3, print "Fizz" instead of the number.

For each multiple of 5, print "Buzz" instead of the number. 

For numbers which are multiples of both 3 and 5, print "FizzBuzz" instead of the number. 


