# ######################################################################
# #
# # CISC 4080 (Computer Algorithms)
# # Spring, 2018
# #
# # Project 2: Comparing Polynomial Multiplication Algorithms
# #
# # This is the Makefile.
# #
# # Author: A. G. Werschulz
# # Date:   8 February 2018
# #
# ######################################################################

# if you want to use a debugger, add a "-g" flag to the next line
CXXFLAGS=-Wall -Wno-sign-compare -std=c++1z 

main: main.o Polynomial.o Polynomial.h random.o
	g++ -o main $(CXXFLAGS) main.o Polynomial.o random.o

main.o: main.cc 

Polynomial.o: Polynomial.cc Polynomial.h

random.o: random.cc random.h

clean:
	@/bin/rm -f *~ \#*\# core* main *.o
