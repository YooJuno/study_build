OBJS=main.o apple.o banana.o
TARGET=app.out
 
all: $(TARGET)
  
clean:
	rm -f *.o
	rm -f $(TARGET)
 
$(TARGET): $(OBJS)
	$(CC) -o $@ $(OBJS)
  
main.o: apple.h banana.h main.c
apple.o: apple.h apple.c
banana.o: banana.h banana.c