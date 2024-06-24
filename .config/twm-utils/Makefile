PREFIX ?= /usr

all:
	@echo Please run \'make install\' to start the installation

install:
	@install -Dm755 twm_scrollup $(DESTDIR)$(PREFIX)/bin/twm_scrollup
	@install -Dm755 twm_scrolldown $(DESTDIR)$(PREFIX)/bin/twm_scrolldown
	@install -Dm755 twm_movetows1 $(DESTDIR)$(PREFIX)/bin/twm_movetows1
	@install -Dm755 twm_movetows2 $(DESTDIR)$(PREFIX)/bin/twm_movetows2
	@install -Dm755 twm_movetows3 $(DESTDIR)$(PREFIX)/bin/twm_movetows3
	@install -Dm755 twm_movetows4 $(DESTDIR)$(PREFIX)/bin/twm_movetows4
	@install -Dm755 twm_movetows5 $(DESTDIR)$(PREFIX)/bin/twm_movetows5
	@echo Installation is complete
	@echo Add the following command in your \'.twmrc\' file:
	@echo ' '
	@echo '	### BUTTON4&5 (Mouse/Touchpad Scrolling) FUNCTION ###'
	@echo '	Button4		=	: root		: f.exec "twm_scrollup"'
	@echo '	Button5		=	: root		: f.exec "twm_scrolldown"'
	@echo ' '
	@echo '	## Workspace Switch'
	@echo '	"1"     = m4    : all   : f.exec "vdesk 1 ; notify-send 'Workspace 1' &"'
	@echo '	"2"     = m4    : all   : f.exec "vdesk 2 ; notify-send 'Workspace 2' &"'
	@echo '	"3"     = m4    : all   : f.exec "vdesk 3 ; notify-send 'Workspace 3' &"'
	@echo '	"4"     = m4    : all   : f.exec "vdesk 4 ; notify-send 'Workspace 4' &"'
	@echo '	"5"     = m4    : all   : f.exec "vdesk 5 ; notify-send 'Workspace 5' &"'
	@echo ' '
	@echo '	## Move Window to Workspace'
	@echo '	"1"	= m4|s	: w	: f.exec "twm_movetows1 &"'
	@echo '	"2"	= m4|s	: w	: f.exec "twm_movetows2 &"'
	@echo '	"3"	= m4|s	: w	: f.exec "twm_movetows3 &"'
	@echo '	"4"	= m4|s	: w	: f.exec "twm_movetows4 &"'
	@echo '	"5"	= m4|s	: w	: f.exec "twm_movetows5 &"'
	@echo ' '
	@echo If it already exists then you can skip this step
	@echo For more information see https://github.com/diws1/twm-utils

uninstall:
	@rm -f $(DESTDIR)$(PREFIX)/bin/twm_scrollup\
		$(DESTDIR)$(PREFIX)/bin/twm_scrolldown\
	        $(DESTDIR)$(PREFIX)/bin/twm_movetows1\
	        $(DESTDIR)$(PREFIX)/bin/twm_movetows2\
		$(DESTDIR)$(PREFIX)/bin/twm_movetows3\
		$(DESTDIR)$(PREFIX)/bin/twm_movetows4\
	        $(DESTDIR)$(PREFIX)/bin/twm_movetows5
	@echo twm-utils is no longer installed






