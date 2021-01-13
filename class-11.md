# Error Handling and Debugging


JavaScript can be hard to learn and everyone makes
mistakes when writing it. This chapter will help you learn
how to find the errors in your code. It will also teach you how
to write scripts that deal with potential errors gracefully.
When you are writing JavaScript, do not expect to write it perfectly the first time.

Programming is like problem solving: you are given a puzzle and not only do you have to solve it, but you also need to create the instructions that allow the computer to solve it. too. When writing a long script, nobody gets everything right in their first attempt. The error messages that a browser gives look cryptic at first, but they can help you determine what went wrong in your JavaScript and how to fix it. In this chapter you will learn about:
## HE CONSOLE & DEV TOOLS
Tools built into the browser that help you hunt for errors.
## 9 ERROR HANDLING & DEBUGGING COMMON PROBLEMS
Common sources of errors, and how to solve them.
## HANDLING ERRORS
How code can deal with potential errors gra cefully.

# ORDER OF EXECUTION

To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run:

# EXECUTION CONTEXTS

The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope.