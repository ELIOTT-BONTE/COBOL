This repo is made as an aggregation of COBOL projects, to demonstrate COBOL proficiency

To run cobol programs, it is necessary to have a COBOL compiler.
Linux users can use the command

sudo apt insall gnucobol

to obtain one.

A .cbl program is compiled as an executable like such

cobc -x -o nameOfExecutable NAME_OF_COBOL_PROGRAM.cbl

executing the resultin executable is done, as traditionally in Linux

./nameOfExecutable