PROJECT=sh-debug-helpers
VERSION=1.0.0
PREFIX=/usr/local
all:
clean:
install:

## -- BLOCK:license --
install: install-license
install-license: 
	mkdir -p $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
	cp LICENSE  $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
## -- BLOCK:license --
## -- BLOCK:sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/gdb-h-ssh        $(DESTDIR)$(PREFIX)/bin
	cp bin/dlv-h-attach     $(DESTDIR)$(PREFIX)/bin
	cp bin/gdb-h-attach     $(DESTDIR)$(PREFIX)/bin
	cp bin/ut               $(DESTDIR)$(PREFIX)/bin
	cp bin/dlv-h-ssh        $(DESTDIR)$(PREFIX)/bin
## -- BLOCK:sh --
