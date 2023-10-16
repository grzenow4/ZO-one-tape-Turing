# ZO-one-tape-Turing

Your task is to write a program in Python that translates two-tape Turing machines into one-tape Turing machines.

To play around with Turing machines, you can use the experimental Python visualiser in the attached file. The simulator uses something called "jupyter notebook". [Here](https://jupyter.org/install) are the installation instructions.

More precisely, you should write a Python procedure `eliminateInputTape(machine)`. As a parameter it takes a Turing machine with a read-only input tape and with one working tape. The format of the Turing machine should be as in the file [turingPython.ipynb](turingPython.ipynb). The procedure should return a Turing machine without the read-only input tape (i.e., with `onlyWorkTape` set to `True`).

The new machine should accept the same input words as the original one. Make sure that the generated machine can be executed by the interpreter in [turingPython.ipynb](turingPython.ipynb). Moreover, your solution should not only be correct, but also work in a reasonable time, produce Turing machines working in reasonable time, etc.
