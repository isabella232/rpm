# Makefile for rpm scripts.

include $(top_srcdir)/rpm.am
AM_CFLAGS = @RPMCFLAGS@

CLEANFILES =

EXTRA_DIST = \
	brp-compress brp-python-bytecompile brp-java-gcjcompile \
	brp-strip brp-strip-comment-note brp-python-hardlink \
	brp-strip-static-archive brp-elfperms \
	check-files check-prereqs \
	check-buildroot check-rpaths check-rpaths-worker \
	find-debuginfo.sh find-lang.sh \
	perl.prov perl.req pythondistdeps.py \
	rpmdb_dump rpmdb_load \
	rpm.daily rpm.log rpm.supp rpm2cpio.sh \
	tgpg vpkg-provides.sh \
	find-requires find-provides \
	find-requires.php find-provides.php \
	ocamldeps.sh \
	pkgconfigdeps.sh libtooldeps.sh \
	fontconfig.prov script.req

rpmconfig_SCRIPTS = \
	brp-compress brp-python-bytecompile brp-java-gcjcompile \
	brp-strip brp-strip-comment-note brp-python-hardlink \
	brp-strip-static-archive brp-elfperms \
	check-files check-prereqs \
	check-buildroot check-rpaths check-rpaths-worker \
	find-lang.sh find-requires find-provides \
	perl.prov perl.req pythondistdeps.py \
	pkgconfigdeps.sh libtooldeps.sh \
	ocamldeps.sh \
	fontconfig.prov script.req \
	rpmdb_dump rpmdb_load \
	rpm2cpio.sh tgpg

rpmconfig_DATA = \
	rpm.daily rpm.log rpm.supp

