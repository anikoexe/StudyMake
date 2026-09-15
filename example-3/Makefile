CC = g++
CFLAGS = -Wall -Wextra
SRC = Kazino-Royal.cpp
TARGET = example3

all: $(TARGET)

$(TARGET): $(SRC)
	$(CC) $(CFLAGS) $(SRC) -o $(TARGET)

.PHONY: clean all

clean:
	rm -f $(TARGET) *.o
