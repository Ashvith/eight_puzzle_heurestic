# Simple 8 puzzle solver implementation in Ruby 💎

This is a very simple implementation of an 8 puzzle solver, that uses the in-bult standard libraries of Ruby to provide a solution

Users are required to place their desired **present_state** (the unsolved state) inside the .rb extension file.

We have also provided a **solution_state** so that custom solutions can be solved too.

Currently, it does not support any input, or output. We will request the user to have either use the online compiler, or stick to JRuby, for lesser hassle. Linux users will be at an advantage, because it will be less painful to execute this file.

>**What to know before using this:**
>
>You are required to have Ruby installed. Any Ruby compiler will do fine too, but we would recommend to install JRuby for quicker setup, and MRI for the stock development environment.
>
>*How to check if Ruby is properly installed or not?*
>
>Try typing ruby -v in any terminal. If it shows an error, either Ruby was not installed properly, or there is some problem with the **PATH** location.
>
>Here, 0 is the equivalent of blank space.
>
>If the batch or shellscript files are not working, change the directory of the terminal to the location of *heurestic.rb*, and try *ruby heurestic.rb*.

>**Note:**
>
>This is not an optimised code, although it may run without any hitch, and there are many ways by which the memory usage can be reduced.
>
>But assuming that we are using negligible resources, and also following the philosophy of "free RAM is wasted RAM", we will not look into that.
>