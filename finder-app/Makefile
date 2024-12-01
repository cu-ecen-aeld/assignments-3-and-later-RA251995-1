CC?=$(CROSS_COMPILE)gcc 
CCFLAGS?=-Wall

all:
	$(CC) $(CCFLAGS) -c -o writer.o writer.c
	$(CC) $(LDFLAGS) -I/ writer.o -o writer

clean:
	rm -f *.o writer *.elf *.map