# Introduction to Debugging in IDE

## Learning Objectives
- Know how to debug a Java application
- Understand breakpoints
- Understand the debugger console
- Know how to evaluate code fragments

## Task
As an introduction to debugging:
- watch the following video: [Intro to Debugging video](https://youtu.be/ErVZrVWZrko)


Answer the following questions:
1. What is the purpose of a breakpoint?  --- this is the entry point to the debugger. 
2. Does the line of code on a breakpoint run when you start debugging?  --- it will run as normal until it gets to that point, then pause and launch the debugger before it runs this line.
3. How do we debug the next line of code?  --- highlight/select the test we'd like to debug, then right click and select "Debug 'nameOfTest()'".
4. What does the step into command do?  --- this switches into the method highlighted in blue in the debugger and pauses at the top of that method. 
5. What is the difference between evaluate expression and evaluate code fragment?  --- evaluate expression allows you to run a method and be able to see the result, whereas evaluate code fragment allows you to run multiple methods/lines of code with temp variables etc and see the result of that (keeps temp variables alive until you exit the Fragment window).