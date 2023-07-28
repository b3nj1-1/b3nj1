---
layout: page
title: Research
---

## Under construction 


```bash
FIND(1)                                        General Commands Manual                                        FIND(1)

NAME
       find - search for files in a directory hierarchy

SYNOPSIS
       find [-H] [-L] [-P] [-D debugopts] [-Olevel] [starting-point...] [expression]

DESCRIPTION
       This manual page documents the GNU version of find.  GNU find searches the directory tree rooted at each given
       starting-point by evaluating the given expression from left to right, according to  the  rules  of  precedence
       (see  section OPERATORS), until the outcome is known (the left hand side is false for and operations, true for
       or), at which point find moves on to the next file name.  If no starting-point is specified, `.' is assumed.

       If you are using find in an environment where security is important (for example if you are using it to search
       directories  that  are  writable by other users), you should read the `Security Considerations' chapter of the
       findutils documentation, which is called Finding Files and comes with findutils.  That document also  includes
       a  lot  more  detail and discussion than this manual page, so you may find it a more useful source of informa‐
       tion.

OPTIONS
       The -H, -L and -P options control the treatment of symbolic links.  Command-line arguments following these are
       taken  to  be  names of files or directories to be examined, up to the first argument that begins with `-', or
       the argument `(' or `!'.  That argument and any following arguments are taken to be the expression  describing
       what is to be searched for.  If no paths are given, the current directory is used.  If no expression is given,
       the expression -print is used (but you should probably consider using -print0 instead, anyway).

       This manual page talks about `options' within the expression list.  These options  control  the  behaviour  of
       find  but  are  specified immediately after the last path name.  The five `real' options -H, -L, -P, -D and -O
```
