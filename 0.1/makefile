SRC = main.cpp
OBJ = $(SRC:.cpp=.o)
CC = g++
CFLAGS = -o
INCLUDES =

run:	build
	./Alphadrafter

build:	$(OBJ)
	$(CC) $(SRC) $(CFLAGS) Alphadrafter

.cpp.o:
	$(CC) $(CFlAGS) $(INCLUDES) -c $<
