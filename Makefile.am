
AUTOMAKE_OPTIONS = nostdinc

dist_xdetheme_DATA = \
	theme/theme.ini

dist_wmakertheme_DATA = \
	theme/style

dist_xdeimage_DATA = \
	images/tower_bluesky4.jpg \
	images/tower_field1.jpg \
	images/hoghorns_sillouette6.jpg \
	images/tower_sky2.jpg \
	images/tower_backlit1.jpg \
	images/tower_clouds1.jpg \
	images/tower_sillouette3.jpg \
	images/tower_greysky3.jpg

EXTRA_DIST = \
	images/array_rooftop1.jpg \
	images/hoghorns_sillouette1.jpg \
	images/hoghorns_sillouette2.jpg \
	images/hoghorns_sillouette3.jpg \
	images/hoghorns_sillouette4.jpg \
	images/hoghorns_sillouette5.jpg \
	images/hoghorns_sillouette6.jpg \
	images/hoghorns_sillouette7.jpg \
	images/tower_backlit1.jpg \
	images/tower_backlit2.jpg \
	images/tower_backlit3.jpg \
	images/tower_backlit4.jpg \
	images/tower_bluesky1.jpg \
	images/tower_bluesky2.jpg \
	images/tower_bluesky3.jpg \
	images/tower_bluesky4.jpg \
	images/tower_clouds1.jpg \
	images/tower_clouds2.jpg \
	images/tower_clouds3.jpg \
	images/tower_dusk.jpg \
	images/tower_fence.jpg \
	images/tower_field1.jpg \
	images/tower_field2.jpg \
	images/tower_field3.jpg \
	images/tower_flatsky.jpg \
	images/tower_greysky1.jpg \
	images/tower_greysky2.jpg \
	images/tower_greysky3.jpg \
	images/tower_horns1.jpg \
	images/tower_ring.jpg \
	images/tower_sillouette1.jpg \
	images/tower_sillouette2.jpg \
	images/tower_sillouette3.jpg \
	images/tower_sillouette4.jpg \
	images/tower_sky1.jpg \
	images/tower_sky2.jpg \
	images/tower_sky3.jpg \
	images/tower_sky4.jpg \
	images/tower_sky.jpg \
	images/tower_tree.jpg

install-data-hook:
	mkdir -p $(DESTDIR)$(fluxboxstylesdir)
	ln -s $(basestyle) $(DESTDIR)$(fluxboxstylesdir)/$(style)
	mkdir -p $(DESTDIR)$(blackboxstylesdir)
	ln -s $(basestyle) $(DESTDIR)$(blackboxstylesdir)/$(style)
	mkdir -p $(DESTDIR)$(icewmthemesdir)
	ln -s $(basestyle) $(DESTDIR)$(icewmthemesdir)/$(style)
	mkdir -p $(DESTDIR)$(jwmthemesdir)
	ln -s ../styles/$(basestyle) $(DESTDIR)$(jwmthemesdir)/$(style)
	mkdir -p $(DESTDIR)$(ctwmstylesdir)
	ln -s $(basestyle) $(DESTDIR)$(ctwmstylesdir)/$(style)
	mkdir -p $(DESTDIR)$(vtwmstylesdir)
	ln -s $(basestyle) $(DESTDIR)$(vtwmstylesdir)/$(style)
	mkdir -p $(DESTDIR)$(twmstylesdir)
	ln -s $(basestyle) $(DESTDIR)$(twmstylesdir)/$(style)
	mkdir -p $(DESTDIR)$(pekwmthemesdir)
	ln -s $(basestyle) $(DESTDIR)$(pekwmthemesdir)/$(style)
	mkdir -p $(DESTDIR)$(themedir)
	ln -s ../$(basestyle)/openbox-3 $(DESTDIR)$(themedir)/openbox-3
	mkdir -p $(DESTDIR)$(themedir)
	ln -s ../$(basestyle)/gtk-2.0 $(DESTDIR)$(themedir)/gtk-2.0
	mkdir -p $(DESTDIR)$(wmakerthemedir)
	mkdir -p $(DESTDIR)$(fluxboxbgdir)
	mkdir -p $(DESTDIR)$(blackboxbgdir)
	mkdir -p $(DESTDIR)$(wmakerbgdir)
	mkdir -p $(DESTDIR)$(xdeimagedir)
	for p in $(dist_xdeimage_DATA) ; do \
		f=$$(basename $$p .jpg) ; \
		install -m644 $(top_srcdir)/images/$$f.jpg $(DESTDIR)$(xdeimagedir)/$$f.jpg ; \
		ln -s ../../../images/$(stylesubdir)/$$f.jpg $(DESTDIR)$(wmakerthemedir)/$$f.jpg ; \
		ln -s ../../images/$(stylesubdir)/$$f.jpg $(DESTDIR)$(fluxboxbgdir)/$$f.jpg ; \
		ln -s ../../images/$(stylesubdir)/$$f.jpg $(DESTDIR)$(blackboxbgdir)/$$f.jpg ; \
		ln -s ../../images/$(stylesubdir)/$$f.jpg $(DESTDIR)$(wmakerbgdir)/$$f.jpg ; \
	done
	for f in $(baseprefix)back $(baseprefix)icon $(baseprefix)tbar $(baseprefix)tile ; do \
		ln -s ../../../WindowMaker/Pixmaps/$$f.xpm $(DESTDIR)$(wmakerthemedir)/$$f.xpm ; \
	done

