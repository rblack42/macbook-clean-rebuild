# Macbook Clean Rebuild

**Author: [Roie Black](https://rblack42.github.io/macbook-clean-rebuild)**

In my teaching career I taught beginning programmers how to manage their
development machines so their code would be rated as high quality by potential
employers. That means their code was created and managed in an organized
manner, written with attention to things like testing and documentation, and
saved in a source code control system ike *Git*. Of course, I had to run all of
their elvolving code on my own personal development system for grading
purposes. I also had to install a variety of things needed for teaching or
developing new courses. My machine needed to be cleaned up at the end of each
term to get ready for the next term.That meant that my machine was subject to
all kinds of potential

To manage this chaos, I started rebuilding my machine before the start of each
term, after safely archiving all of the student work used in generating their
final grades in my courses. This note documents how i rebuilt my machines from
scratch - a clean install that begins with a freshly formatted hard drive and a
bootable copy of the operating system. After installing the operating system,
all required development tools are installed automatically using *Ansible*. My
goal has always been to minimize the need to human intervention during the
rebuild process. 

My current Mac machines include Pentium-based Macbooks and iMacs, and M1-based
Macbooks. The process detailed here covers both kinds of machines.
 
