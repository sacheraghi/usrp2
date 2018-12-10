#
# Copyright 2011 Ettus Research LLC
#

all: N200R3 N210R3 N200R4 N210R4 Custom Custom2 Custom3 Custom4
	find -name "*.twr" | xargs grep constraint | grep met

clean:
	rm -rf build*

N200R3:
	make -f Makefile.$@ bin

N210R3:
	make -f Makefile.$@ bin

N200R4:
	make -f Makefile.$@ bin

N210R4:
	make -f Makefile.$@ bin

Custom:
	make -f Makefile.$@ bin

Custom2:
	make -f Makefile.$@ bin

Custom3:
	make -f Makefile.$@ bin


Custom4:
	make -f Makefile.$@ bin

.PHONY: all clean
