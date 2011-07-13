pack:
	rm -f multi.odt
	cd package_odt ; find . -name .svn -prune -or -name "*~" -or  -print | zip -@ ../multi.odt
	unzip -l multi.odt

install: pack
	mkdir -p /tmp/odt
	cat multi.odt >| /tmp/odt/multi.odt
