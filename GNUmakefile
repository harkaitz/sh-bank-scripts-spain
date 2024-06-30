.POSIX:
.SUFFIXES:
.PHONY: all clean install check
PROJECT   =hledger-scripts-pgc
VERSION   =1.0.0
PREFIX    =/usr/local

all:
clean:
install:
check:
## -- BLOCK:license --
install: install-license
install-license: 
	mkdir -p $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
	cp COPYING $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
## -- BLOCK:license --
## -- BLOCK:sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/hledger-pgc      $(DESTDIR)$(PREFIX)/bin
	cp bin/bbva-h           $(DESTDIR)$(PREFIX)/bin
	cp bin/hlnk-empresa     $(DESTDIR)$(PREFIX)/bin
## -- BLOCK:sh --
