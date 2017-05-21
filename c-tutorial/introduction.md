# Introduction to C

This document is an introduction to the C language and how to get started
programming in C. If you are new to programming and C, then this is a good
starting point for you.

## What you will need

TBD

## Hello world

Many (most?) programming tutorials start off with a program that allows just
prints a message to the screen. Being very simple, this allows us to make sure
that we are able to write, compile and run the code without having to worry
about the complexities of the C language.

So here is the code. Type it in exactly as you see it and save the file as
*hello.c*.

```C
#include <stdio.h>

int main()
{
  printf("Hello world!\n");
  return 0;
}
```

## Compiling under GNU/Linux

In order to compile under GNU/Linux you can type the following:

    % gcc hello.c

If there were no errors, you should end up with an executable file called 
*a.out*. To run this file, simply type the following.

    % ./a.out
    Hello world!

If you got errors when trying to compile, skip down to the section or errors
below.

You might not want your output file to be called a.out in which case you
have to specify the name of the file to the C compiler. This can be done
with the *-o* flag.

    % gcc -o hello hello.c
    
This will give you the output file *hello*.

## Errors 

Getting errors from time to time is part of life. Being a good C programmer
does not mean making errors. But a more experienced programmer has the skills
and tools at their disposal to quickly detect and fix and error, while a
beginner may be stuck and not know how to proceed. So let us look at errors,
how to find them and fix them.

There are several sources of errors. When the compiler detects an error it
will signal this with an error message. In the beginning, these messages
will be your only guide to finding and fixing the bug.

TBC
