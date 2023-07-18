DESTDIR =
PREFIX  =/usr/local


all:
clean:
install:
update:
## -- install-sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/ltest-c          $(DESTDIR)$(PREFIX)/bin
	cp bin/gdb-h-ssh        $(DESTDIR)$(PREFIX)/bin
	cp bin/dlv-h-attach     $(DESTDIR)$(PREFIX)/bin
	cp bin/dlv-h-ssh        $(DESTDIR)$(PREFIX)/bin
## -- install-sh --
## -- license --
install: install-license
install-license: LICENSE
	mkdir -p $(DESTDIR)$(PREFIX)/share/doc/sh-debug-helpers
	cp LICENSE $(DESTDIR)$(PREFIX)/share/doc/sh-debug-helpers
## -- license --
