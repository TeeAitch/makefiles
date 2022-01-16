
CC=clang
CFLAGS=-g -Wall 
CLEAN=hello *.ilk *.pdb *.h.gch *.o  *.exe

all: hello

%.o: %.c %.h 
	$(CC) $(CFLAGS) $^
	
clean: 
	del $(CLEAN)