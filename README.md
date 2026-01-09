2nd project of machine architecure course
Python is used in the grading system for the written code
my written code is in the following files:
bits.c
input.txt

can be ran through the terminal after compiling with the make file
info for make is within file, but pasted here for convenience
->make                          # build all programs'
->make all                      # makes bitwise & puzzlebox 
->make test                     # makes test-bitwise test-puzzlebox // runs written code & compares to answers
->make bitwise                  # compiles my written code
->make bitwise test             # compare written codes result to answer, outputs differences
->make puzzlebox                # compiles my written code
->make puzzlebox test           # compare written codes result to answer, outputs differences

since puzzlebox is simply asking for a hash to pass all the test, all that is needed for that portion
is the correct reverse engineered hash by analyzing 'puzzlebox.c'

bits.c has a list of TODO items. Each item is a simple operation with a list of restrictions
to challenge the coder to use bitwise operations to their advantage

REQUIRES to be ran on linux, or a linux container
