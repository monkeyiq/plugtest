pack:
	rm -f weekend-hike.odt
	cd package_odt ; zip -D -X -0 ../weekend-hike.odt mimetype && find . -name .svn -prune -or -name mimetype -prune -or -name "*~" -or  -print | zip -D -X -0 -@ ../weekend-hike.odt
	unzip -l weekend-hike.odt

install: pack
	mkdir -p /tmp/odt
	cat weekend-hike.odt >| /tmp/odt/weekend-hike.odt
