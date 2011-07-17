pack:
	rm -f multi.odt
	cd package_odt ; zip -D -X -0 ../multi.odt mimetype && find . -name .svn -prune -or -name "*~" -or -name mimetype -prune -or -name Makefile -prune -or -print | zip  -D -X -0  -@ ../multi.odt
	unzip -l multi.odt

install: pack
	mkdir -p /tmp/odt
	cat multi.odt >| /tmp/odt/multi.odt
