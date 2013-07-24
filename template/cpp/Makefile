TARGET = __projectname__

CC = g++
CFLAGS = -O3
SRC_DIR = src
INCLUDES = -Iinclude

C = $(CC) $(INCLUDES) $(CFLAGS)

OBJS = __objects__

.SUFFIXES: .cpp .o

all: $(TARGET)

$(TARGET): $(OBJS)
	$(CC) -o $(TARGET) $^

.cpp.o:
	$(C) -c $< -o $@

clean:
	rm $(TARGET)
	rm $(OBJS)
