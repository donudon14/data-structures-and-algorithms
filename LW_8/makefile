CC=g++
CFLAGS=-c -std=c++14 -Werror -pedantic -Wall -Wextra -O3
LDFLAGS=
LIBS=-lm
SOURCES=LW_8.cpp
OBJECTS=$(SOURCES:.cpp=.o)
EXECUTABLE=LW_8

all: $(SOURCES) $(EXECUTABLE)

$(EXECUTABLE): $(OBJECTS)
	$(CC) $(LDFLAGS) $(OBJECTS) $(LIBS) -o $@

.cpp.o:
	$(CC) $(CFLAGS) $< -o $@

clean:
	rm -frd $(OBJECTS) $(EXECUTABLE)
