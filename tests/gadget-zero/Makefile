GZ_ALL := $(wildcard Makefile.*)

all: $(GZ_ALL:=.all)
clean: $(GZ_ALL:=.clean)

%.all:
	$(MAKE) -f $* all
%.clean:
	$(MAKE) -f $* clean

