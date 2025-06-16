flags=-02 -Wall -std=c2x
.PHONY: all clean
all: clean PROJECTNAME
PROJECTNAME: PROJECTNAME.o
	gcc $^ -o $@ $(flags)
PROJECTNAME.o: PROJECTNAME.c PROJECTNAME.h
	gcc $(flags) -c $<
clean:
	rm -rf *.o PROJECTNAME
	
