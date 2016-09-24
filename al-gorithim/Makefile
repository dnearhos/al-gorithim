CXXFLAGS =	-O2 -g -Wall -fmessage-length=0

OBJS =		al-gorithim.o

LIBS =

TARGET =	al-gorithim

$(TARGET):	$(OBJS)
	$(CXX) -o $(TARGET) $(OBJS) $(LIBS)

all:	$(TARGET)

clean:
	rm -f $(OBJS) $(TARGET)
