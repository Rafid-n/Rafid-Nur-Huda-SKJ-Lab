// Makefile
all_mul: multiply
multiply_mul: multiply.cpp
	g++ -o multiply multiply.cpp
dump_mul: multiply
	objdump -d multiply.exe > multiply.asm
clean_mul:
	rm -f multiply multiply.asm
run_mul: multiply
	./multiply
