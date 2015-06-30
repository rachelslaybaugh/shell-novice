---
layout: page
title: The Unix Shell
subtitle: Files and Directories
minutes: 15
---
Use this file structure to complete the challenges below.

<img src="fig/filesystem-challenge.png" alt="Filesystem for Challenge Questions" />

> ## Relative path resolution challenge
>
> If `pwd` displays `/users/thing`, what will `ls ../backup` display?
> 
> 1.  `../backup: No such file or directory`
> 2.  `2012-12-01 2013-01-08 2013-01-27`
> 3.  `2012-12-01/ 2013-01-08/ 2013-01-27/`
> 4.  `original pnas_final pnas_sub`

solution: 4

> ## `ls` reading comprehension challenge
>
> If `pwd` displays `/users/backup`,
> and `-r` tells `ls` to display things in reverse order,
> what command will display:
> 
> ~~~
> pnas-sub/ pnas-final/ original/
> ~~~
> 
> 1.  `ls pwd`
> 2.  `ls -r -F`
> 3.  `ls -r -F /users/backup`
> 4.  Either \#2 or \#3 above, but not \#1.

solution: 4

> ## Default `cd` action challenge
>
> What does the command `cd` without a directory name do?
> 
> 1.  It has no effect.
> 2.  It changes the working directory to `/`.
> 3.  It changes the working directory to the user's home directory.
> 4.  It produces an error message.

solution: 3

> ## Exploring more `ls` arguments challenge
>
> What does the command `ls` do when used with the `-s` and `-h`
> arguments?

solution: 
-s = size [print the allocated size of each file, in blocks]

-h = human-reqadable  [with -l, print sizes in human readable format (e.g., 1K 234M 2G)]
