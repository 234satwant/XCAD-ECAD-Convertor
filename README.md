XCAD-ECAD-Convertor
===================
Steps to compile:

bison -d task.y

flex task.l

g++ task.tab.c lex.yy.c -lfl -o task

A file named "output" will be created when contains the converted file.
