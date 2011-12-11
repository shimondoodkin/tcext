tcext - Quick Extension Creation Script for Tiny Core Linux
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

I wanted to make it easy to create extensions
So more people will be able to do it
Also I wanted that people will provide inside the extensions
A tutorial how to make an extension

This script makes your life simpler
Now you have time to Describe your work, Reread the extention info, and Make more extensions

Written by Shimon Doodkin helpmepro1@gmail.com doodkin.com

Contributors:
 You here - fork and modify https://github.com/shimondoodkin/tcext/
 
Lisence: MIT


usage:
when no argument present, all tasks are done one after another.
tcext init - crates tcext.info and shows an editor with the file
tcext script - a shorthand to exports arch 486 flags... , when you do the ./configure and make manualy
tcext configure OPTIONS - does flags, and ./configure \$OPTIONS --prefix=/usr/local
tcext make - does flags and make
tcext install - does make install into a /tmp/pkg folder and puts the file.tcz in ./tcout folder
additional:
tcext flags - a shorthand to exports arch 486 flags... , when you do the ./configure and make manualy
tcext build ARGS- does ./configure \$ARGS && tcext mak
tcext deps - calculate dependencies in current folder
tcext installhalf - does make install into a /tmp/pkg folder and copis tcfiles/* to /tmp/pkg
tcext installfinish - allows split into sub pagages,it packages and puts the file.tcz in ./tcout folder
tcext help - show this message
tbd:
tcext submit
