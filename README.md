# C - Hello Build System

This repository contains notes, code snippets, and experiments related to the build system in C programming language. My
personal goal is to become more comfortable building C projects using a build system.

## Why a Build System?

Build systems were created to automate the process of building source code into an executable. When the first version of
the C programming language was released back in 1972 there was no need for a build system. Software development was much
more straightforward than it is today. The software was simpler, development teams were small specialized groups, and there
were fewer tools (dependencies) to manage.

After a few years, some challenges started to emerge. When building the software, developers had to manually compile the
source code, link the object files, and run the tests. This process was time-consuming, error-prone, and not scalable. To
overcome these challenges, the `make` build system was created.

### Why does C not have a built-in build system?

Originally C didn't intend to have a built-in build system. The C programming language is a **language** and not a
build system nor a package manager. The C programming language was designed to be simple, efficient, and portable.


