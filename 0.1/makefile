SRC = main.cpp
OBJ = $(SRC:.cpp=.o)
CC = g++
CFLAGS = -o
INCLUDES =

run:	build
	./Alphadraft

build:	$(OBJ)
	$(CC) $(SRC) $(CFLAGS) Alphadraft

.cpp.o:
	$(CC) $(CFlAGS) $(INCLUDES) -c $<

clean:	
	rm -f Alphadraft
	rm -f $(OBJ)
