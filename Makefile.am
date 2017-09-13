EXTRA_DIST = \
	EvoPop-0.7 \
	LICENSE \
	CREDITS \
	README.md

xsessiondir = $(datadir)/xsessions

themedir = $(datadir)/icons

install-data-hook:
	$(MKDIR_P) $(DESTDIR)$(themedir)
	cp -Rv EvoPop-0.7 $(DESTDIR)$(themedir)/.

uninstall-hook:
	test -e $(DESTDIR)$(themedir)/EvoPop-0.7 && rm -rfv $(DESTDIR)$(themedir)/EvoPop-0.7
