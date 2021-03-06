# service/Makefile
CC = gcc
TARGET = echo

all: echo

echo:
	$(CC) $(TARGET).c -z execstack -fno-stack-protector -o $(TARGET)

clean:
	rm $(TARGET)
