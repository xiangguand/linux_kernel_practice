obj-m := passing_simple_count.o

all:
	make -C /lib/modules/`uname -r`/build M=${PWD} modules

clean:
	make -C /lib/modules/`uname -r`/build M=${PWD} clean



