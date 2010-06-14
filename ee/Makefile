EE_LIB = ../lib/libps2gdbStub.a
EE_OBJS = ps2gdbStub.o gdb-low.o
EE_CFLAGS += -g

all: $(EE_LIB)

clean:
	rm -f $(EE_LIB) $(EE_OBJS)

include $(PS2SDK)/samples/Makefile.pref
include $(PS2SDK)/samples/Makefile.eeglobal
