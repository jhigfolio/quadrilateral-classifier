# quadrilateral-classifier

## How to run:
1. Clone this repo and navigate into it via a terminal of your choice. 
2. Use the provided Makefile to run execute different testing methods:
  * make - compiles the quadrilateral classifier into an executable called detectShape, which we can use to run the program and test it
  * make test - tests the classifier for code coverage by running a pre-defined series of (invalid) quadrilaterals through the program and tracking which branches of code were executed
  * make coverage - shows the code coverage
  * make prepare_fuzz - sets up the environment for fuzzing (only needs to be run once, even after cleaning)
  * make fuzzer - runs the fuzzer as described above.
  * make clean - cleans up all the files produced from fuzzing (there will be a lot of them)
