CC?=gcc
STD?=gnu99
CFLAGS+=-fPIC -I /usr/local/include -I .. -Wall -g
OBJ = artwork_internal.o escape.o lastfm.o

%.o: %.c $(DEPS)
	$(CC) -std=$(STD) -c -o $@ $< $(CFLAGS)

all: $(OBJ)

clean:
	rm -v $(OBJ)
