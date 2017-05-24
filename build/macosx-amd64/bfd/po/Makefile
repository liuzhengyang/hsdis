# Makefile for program source directory in GNU NLS utilities package.
# Copyright (C) 1995, 1996, 1997 by Ulrich Drepper <drepper@gnu.ai.mit.edu>
# Copyright (C) 2001-2015 Free Software Foundation, Inc.
#
# This file may be copied and used freely without restrictions.  It can
# be used in projects which are not available under the GNU Public License
# but which still want to provide support for the GNU gettext functionality.
# Please note that the actual code is *not* freely available.

PACKAGE = bfd
VERSION = 2.26

SHELL = /bin/sh


srcdir = /Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/po
top_srcdir = /Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd
VPATH = /Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/po
top_builddir = ..

prefix = /usr/local
exec_prefix = ${prefix}
datadir = $(prefix)/
localedir = $(datadir)/locale
gnulocaledir = $(prefix)/share/locale
gettextsrcdir = $(prefix)/share/gettext/po
subdir = po

DESTDIR =

INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
MKINSTALLDIRS = /Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/../mkinstalldirs

CC = gcc
GENCAT = 
GMSGFMT = PATH=../src:$$PATH :
MSGFMT = :
XGETTEXT = PATH=../src:$$PATH :
MSGMERGE = PATH=../src:$$PATH msgmerge

DEFS = -DHAVE_CONFIG_H
CFLAGS = -fPIC -O
CPPFLAGS = 

INCLUDES = -I.. -I$(top_srcdir)/intl

COMPILE = $(CC) -c $(DEFS) $(INCLUDES) $(CPPFLAGS) $(CFLAGS) $(XCFLAGS)

SOURCES = cat-id-tbl.c
POFILES =  $(srcdir)/fr.po $(srcdir)/tr.po $(srcdir)/ja.po $(srcdir)/es.po $(srcdir)/sv.po $(srcdir)/da.po $(srcdir)/zh_CN.po $(srcdir)/ro.po $(srcdir)/rw.po $(srcdir)/vi.po $(srcdir)/fi.po $(srcdir)/id.po $(srcdir)/ru.po $(srcdir)/uk.po
GMOFILES =  $(srcdir)/fr.gmo $(srcdir)/tr.gmo $(srcdir)/ja.gmo $(srcdir)/es.gmo $(srcdir)/sv.gmo $(srcdir)/da.gmo $(srcdir)/zh_CN.gmo $(srcdir)/ro.gmo $(srcdir)/rw.gmo $(srcdir)/vi.gmo $(srcdir)/fi.gmo $(srcdir)/id.gmo $(srcdir)/ru.gmo $(srcdir)/uk.gmo
DISTFILES = ChangeLog Makefile.in.in SRC-POTFILES.in BLD-POTFILES.in $(PACKAGE).pot \
stamp-cat-id $(POFILES) $(GMOFILES) $(SOURCES)

# Note - the following line gets processed by bfd/configure and amended
# to contain the full list of source dir POTFILES.
SRC-POTFILES = \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/aix386-core.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/aix5ppc-core.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/aout-adobe.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/aout-arm.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/aout-cris.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/aout-ns32k.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/aout-sparcle.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/aout-target.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/aout-tic30.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/aout0.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/aout32.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/aout64.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/aoutf1.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/aoutx.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/archive.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/archive64.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/archures.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/armnetbsd.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/bfd.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/bfdio.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/bfdwin.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/binary.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/bout.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cache.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cf-i386lynx.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cf-sparclynx.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cisco-core.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-alpha.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-apollo.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-arm.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-aux.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-bfd.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-go32.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-h8300.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-h8500.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-i386.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-i860.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-i960.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-m68k.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-m88k.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-mips.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-rs6000.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-sh.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-sparc.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-stgo32.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-svm68k.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-tic30.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-tic4x.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-tic54x.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-tic80.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-u68k.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-w65.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-we32k.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-x86_64.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-z80.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff-z8k.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coff64-rs6000.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coffcode.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coffgen.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cofflink.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/coffswap.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/compress.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/corefile.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-aarch64.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-alpha.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-arc.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-arm.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-avr.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-bfin.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-cr16.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-cr16c.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-cris.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-crx.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-d10v.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-d30v.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-dlx.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-epiphany.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-fr30.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-frv.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-ft32.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-h8300.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-h8500.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-hppa.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-i370.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-i386.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-i860.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-i960.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-ia64.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-iamcu.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-ip2k.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-iq2000.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-k1om.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-l1om.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-lm32.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-m10200.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-m10300.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-m32c.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-m32r.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-m68hc11.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-m68hc12.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-m68k.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-m88k.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-m9s12x.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-m9s12xg.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-mcore.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-mep.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-metag.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-microblaze.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-mips.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-mmix.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-moxie.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-msp430.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-mt.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-nds32.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-nios2.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-ns32k.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-or1k.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-pdp11.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-pj.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-plugin.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-powerpc.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-rl78.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-rs6000.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-rx.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-s390.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-score.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-sh.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-sparc.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-spu.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-tic30.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-tic4x.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-tic54x.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-tic6x.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-tic80.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-tilegx.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-tilepro.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-v850.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-v850_rh850.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-vax.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-visium.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-w65.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-we32k.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-xc16x.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-xgate.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-xstormy16.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-xtensa.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-z80.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/cpu-z8k.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/demo64.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/dwarf1.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/dwarf2.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/ecoff.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/ecofflink.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/ecoffswap.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf-attrs.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf-bfd.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf-eh-frame.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf-hppa.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf-ifunc.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf-linux-psinfo.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf-m10200.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf-m10300.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf-nacl.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf-strtab.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf-vxworks.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-am33lin.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-arc.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-arm.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-avr.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-bfin.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-cr16.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-cr16c.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-cris.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-crx.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-d10v.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-d30v.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-dlx.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-epiphany.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-fr30.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-frv.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-ft32.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-gen.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-h8300.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-hppa.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-hppa.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-i370.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-i386.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-i860.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-i960.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-ip2k.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-iq2000.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-lm32.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-m32c.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-m32r.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-m68hc11.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-m68hc12.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-m68hc1x.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-m68k.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-m88k.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-mcore.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-mep.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-metag.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-microblaze.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-mips.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-moxie.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-msp430.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-mt.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-nds32.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-nios2.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-or1k.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-pj.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-ppc.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-rl78.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-rx.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-s390.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-score.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-score7.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-sh-symbian.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-sh.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-sh64-com.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-sh64.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-sparc.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-spu.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-tic6x.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-tilegx.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-tilepro.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-v850.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-vax.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-visium.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-xc16x.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-xgate.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-xstormy16.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32-xtensa.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf32.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf64-alpha.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf64-gen.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf64-hppa.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf64-hppa.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf64-ia64-vms.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf64-mips.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf64-mmix.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf64-ppc.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf64-s390.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf64-sh64.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf64-sparc.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf64-tilegx.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf64-x86-64.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elf64.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elfcode.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elfcore.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elflink.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elfn32-mips.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elfxx-aarch64.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elfxx-ia64.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elfxx-mips.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elfxx-sparc.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/elfxx-tilegx.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/epoc-pe-arm.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/epoc-pei-arm.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/format.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/freebsd.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/genlink.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/go32stub.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/hash.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/hp300bsd.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/hp300hpux.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/hpux-core.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/i386aout.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/i386bsd.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/i386dynix.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/i386freebsd.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/i386linux.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/i386lynx.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/i386mach3.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/i386msdos.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/i386netbsd.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/i386os9k.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/ieee.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/ihex.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/init.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/irix-core.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/libaout.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/libbfd.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/libbfd.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/libcoff.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/libecoff.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/libhppa.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/libieee.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/libnlm.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/liboasys.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/libpei.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/libxcoff.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/linker.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/lynx-core.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/m68k4knetbsd.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/m68klinux.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/m68knetbsd.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/m88kmach3.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/m88kopenbsd.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/mach-o-i386.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/mach-o-x86-64.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/mach-o.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/mach-o.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/merge.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/mipsbsd.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/mmo.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/netbsd.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/newsos3.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/nlm-target.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/nlm.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/nlm32-alpha.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/nlm32-i386.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/nlm32-ppc.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/nlm32-sparc.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/nlm32.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/nlm64.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/nlmcode.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/nlmswap.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/ns32k.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/ns32knetbsd.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/oasys.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/opncls.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/osf-core.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pc532-mach.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pdp11.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pe-arm-wince.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pe-arm.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pe-i386.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pe-mcore.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pe-mips.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pe-ppc.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pe-sh.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pe-x86_64.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pef-traceback.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pef.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pef.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pei-arm-wince.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pei-arm.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pei-i386.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pei-ia64.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pei-mcore.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pei-mips.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pei-ppc.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pei-sh.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/pei-x86_64.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/peicode.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/plugin.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/ppcboot.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/reloc.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/reloc16.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/riscix.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/rs6000-core.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/sco5-core.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/section.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/simple.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/som.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/som.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/sparclinux.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/sparclynx.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/sparcnetbsd.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/srec.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/stab-syms.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/stabs.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/sunos.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/syms.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/targets.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/tekhex.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/trad-core.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/vax1knetbsd.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/vaxbsd.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/vaxnetbsd.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/verilog.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/versados.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/version.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/vms-alpha.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/vms-lib.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/vms-misc.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/vms.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/xcofflink.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/xsym.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/xsym.h \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/xtensa-isa.c \
	/Users/liuzhengyang/Code/opensource/openjdk/jdk8/hotspot/src/share/tools/hsdis/binutils-2.26/bfd/xtensa-modules.c 

# Note - the following line gets processed by bfd/configure and amended
# to contain the full list of build dir POTFILES.
BLD-POTFILES = \
	../bfd_stdint.h \
	../bfdver.h \
	../elf32-aarch64.c \
	../elf32-ia64.c \
	../elf32-target.h \
	../elf64-aarch64.c \
	../elf64-ia64.c \
	../elf64-target.h \
	../peigen.c \
	../pepigen.c \
	../pex64igen.c \
	../targmatch.h 

CATALOGS = 
CATOBJEXT = 
INSTOBJEXT = 

.SUFFIXES:
.SUFFIXES: .c .o .po .pox .gmo .mo .msg .cat

.c.o:
	$(COMPILE) $<

.po.pox:
	$(MAKE) $(PACKAGE).pot
	$(MSGMERGE) $< $(srcdir)/$(PACKAGE).pot -o $*.pox

.po.mo:
	$(MSGFMT) -o $@ $<

.po.gmo:
	file=`echo $* | sed 's,.*/,,'`.gmo \
	  && rm -f $$file && $(GMSGFMT) -o $$file $<

.po.cat:
	sed -f ../intl/po2msg.sed < $< > $*.msg \
	  && rm -f $@ && $(GENCAT) $@ $*.msg


all: all-no

all-yes: $(CATALOGS) # $(PACKAGE).pot
all-no:

$(srcdir)/$(PACKAGE).pot: $(SRC-POTFILES) $(BLD-POTFILES)
	$(XGETTEXT) --default-domain=$(PACKAGE) \
	  --directory=$(top_srcdir) \
	  --add-comments --keyword=_ --keyword=N_ \
	  --msgid-bugs-address=bug-binutils@gnu.org \
	  --files-from=$(srcdir)/SRC-POTFILES.in 
	$(XGETTEXT) --default-domain=$(PACKAGE) \
	  --directory=.. \
	  --directory=. \
	  --add-comments --keyword=_ --keyword=N_ \
	  --join-existing \
	  --msgid-bugs-address=bug-binutils@gnu.org \
	  --files-from=$(srcdir)/BLD-POTFILES.in
	rm -f $(srcdir)/$(PACKAGE).pot
	mv $(PACKAGE).po $(srcdir)/$(PACKAGE).pot

$(srcdir)/cat-id-tbl.c: stamp-cat-id; @:
$(srcdir)/stamp-cat-id: $(PACKAGE).pot
	rm -f cat-id-tbl.tmp
	sed -f ../intl/po2tbl.sed $(srcdir)/$(PACKAGE).pot \
		| sed -e "s/@PACKAGE NAME@/$(PACKAGE)/" > cat-id-tbl.tmp
	if cmp -s cat-id-tbl.tmp $(srcdir)/cat-id-tbl.c; then \
	  rm cat-id-tbl.tmp; \
	else \
	  echo cat-id-tbl.c changed; \
	  rm -f $(srcdir)/cat-id-tbl.c; \
	  mv cat-id-tbl.tmp $(srcdir)/cat-id-tbl.c; \
	fi
	cd $(srcdir) && rm -f stamp-cat-id && echo timestamp > stamp-cat-id


install: install-exec install-data
install-exec:
install-info:
install-html:
install-pdf:
install-data: install-data-no
install-data-no: all
install-data-yes: all
	if test -r $(MKINSTALLDIRS); then \
	  $(MKINSTALLDIRS) $(DESTDIR)$(datadir); \
	else \
	  $(top_srcdir)/mkinstalldirs $(DESTDIR)$(datadir); \
	fi
	@catalogs='$(CATALOGS)'; \
	for cat in $$catalogs; do \
	  cat=`basename $$cat`; \
	  case "$$cat" in \
	    *.gmo) destdir=$(gnulocaledir);; \
	    *)     destdir=$(localedir);; \
	  esac; \
	  lang=`echo $$cat | sed 's/\$(CATOBJEXT)$$//'`; \
	  dir=$(DESTDIR)$$destdir/$$lang/LC_MESSAGES; \
	  if test -r $(MKINSTALLDIRS); then \
	    $(MKINSTALLDIRS) $$dir; \
	  else \
	    $(top_srcdir)/mkinstalldirs $$dir; \
	  fi; \
	  if test -r $$cat; then \
	    $(INSTALL_DATA) $$cat $$dir/$(PACKAGE)$(INSTOBJEXT); \
	    echo "installing $$cat as $$dir/$(PACKAGE)$(INSTOBJEXT)"; \
	  else \
	    $(INSTALL_DATA) $(srcdir)/$$cat $$dir/$(PACKAGE)$(INSTOBJEXT); \
	    echo "installing $(srcdir)/$$cat as" \
		 "$$dir/$(PACKAGE)$(INSTOBJEXT)"; \
	  fi; \
	  if test -r $$cat.m; then \
	    $(INSTALL_DATA) $$cat.m $$dir/$(PACKAGE)$(INSTOBJEXT).m; \
	    echo "installing $$cat.m as $$dir/$(PACKAGE)$(INSTOBJEXT).m"; \
	  else \
	    if test -r $(srcdir)/$$cat.m ; then \
	      $(INSTALL_DATA) $(srcdir)/$$cat.m \
		$$dir/$(PACKAGE)$(INSTOBJEXT).m; \
	      echo "installing $(srcdir)/$$cat as" \
		   "$$dir/$(PACKAGE)$(INSTOBJEXT).m"; \
	    else \
	      true; \
	    fi; \
	  fi; \
	done
	if test "$(PACKAGE)" = "gettext"; then \
	  if test -r $(MKINSTALLDIRS); then \
	    $(MKINSTALLDIRS) $(DESTDIR)$(gettextsrcdir); \
	  else \
	    $(top_srcdir)/mkinstalldirs $(DESTDIR)$(gettextsrcdir); \
	  fi; \
	  $(INSTALL_DATA) $(srcdir)/Makefile.in.in \
			  $(DESTDIR)$(gettextsrcdir)/Makefile.in.in; \
	else \
	  : ; \
	fi

# Define this as empty until I found a useful application.
installcheck:

uninstall:
	catalogs='$(CATALOGS)'; \
	for cat in $$catalogs; do \
	  cat=`basename $$cat`; \
	  lang=`echo $$cat | sed 's/\$(CATOBJEXT)$$//'`; \
	  rm -f $(DESTDIR)$(localedir)/$$lang/LC_MESSAGES/$(PACKAGE)$(INSTOBJEXT); \
	  rm -f $(DESTDIR)$(localedir)/$$lang/LC_MESSAGES/$(PACKAGE)$(INSTOBJEXT).m; \
	  rm -f $(DESTDIR)$(gnulocaledir)/$$lang/LC_MESSAGES/$(PACKAGE)$(INSTOBJEXT); \
	  rm -f $(DESTDIR)$(gnulocaledir)/$$lang/LC_MESSAGES/$(PACKAGE)$(INSTOBJEXT).m; \
	done
	rm -f $(DESTDIR)$(gettextsrcdir)/po-Makefile.in.in

check: all

cat-id-tbl.o: ../intl/libgettext.h

html dvi pdf ps info tags TAGS ID:

mostlyclean:
	rm -f core core.* *.pox $(PACKAGE).po *.old.po cat-id-tbl.tmp
	rm -fr *.o

clean: mostlyclean

distclean: clean
	rm -f Makefile Makefile.in *.mo *.msg *.cat *.cat.m
	rm -f SRC-POTFILES BLD-POTFILES 

maintainer-clean: distclean
	@echo "This command is intended for maintainers to use;"
	@echo "it deletes files that may require special tools to rebuild."
	rm -f $(GMOFILES) SRC-POTFILES.in BLD-POTFILES.in

distdir = ../$(PACKAGE)-$(VERSION)/$(subdir)
dist distdir: update-po $(DISTFILES)
	dists="$(DISTFILES)"; \
	for file in $$dists; do \
	  ln $(srcdir)/$$file $(distdir) 2> /dev/null \
	    || cp -p $(srcdir)/$$file $(distdir); \
	done

update-po: Makefile
	$(MAKE) $(PACKAGE).pot
	PATH=`pwd`/../src:$$PATH; \
	cd $(srcdir); \
	catalogs='$(CATALOGS)'; \
	for cat in $$catalogs; do \
	  cat=`basename $$cat`; \
	  lang=`echo $$cat | sed 's/\$(CATOBJEXT)$$//'`; \
	  mv $$lang.po $$lang.old.po; \
	  echo "$$lang:"; \
	  if $(MSGMERGE) $$lang.old.po $(PACKAGE).pot -o $$lang.po; then \
	    rm -f $$lang.old.po; \
	  else \
	    echo "msgmerge for $$cat failed!"; \
	    rm -f $$lang.po; \
	    mv $$lang.old.po $$lang.po; \
	  fi; \
	done

SRC-POTFILES: SRC-POTFILES.in
	( if test 'x$(srcdir)' != 'x.'; then \
	    posrcprefix='$(top_srcdir)/'; \
	  else \
	    posrcprefix="../"; \
	  fi; \
	  rm -f $@-t $@ \
	    && (sed -e '/^#/d' \
	            -e '/^[ 	]*$$/d' \
		    -e "s@.*@	$$posrcprefix& \\\\@" < $(srcdir)/$@.in \
		| sed -e '$$s/\\$$//') > $@-t \
	    && chmod a-w $@-t \
	    && mv $@-t $@ )

BLD-POTFILES: BLD-POTFILES.in
	  ( rm -f $@-t $@ \
	    && (sed -e '/^#/d' \
	            -e '/^[ 	]*$$/d' \
		    -e "s@.*@	../& \\\\@" < $(srcdir)/$@.in \
		| sed -e '$$s/\\$$//') > $@-t \
	    && chmod a-w $@-t \
	    && mv $@-t $@ )

SRC-POTFILES.in: # ../Makefile
	cd .. && $(MAKE) po/SRC-POTFILES.in

BLD-POTFILES.in: # ../Makefile
	cd .. && $(MAKE) po/BLD-POTFILES.in

# Note - The presence of SRC-POTFILES and BLD-POTFILES as dependencies
# here breaks the implementation of the 'distclean' rule for maintainers.
# This is because if 'make distclean' is run in the BFD directory, the
# Makefile there will be deleted before 'distclean' is made here, and so
# the dependency SRC-POTFILES -> SRC-POTFILES.in -> ../Makefile cannot
# be satisfied.
#
# The SRC-POTFILES and BLD-POTFILES dependencies cannot be removed,
# however since it is necessary that these files be built during
# *configure* time, so that configure can insert them into the
# po/Makefile that it is creating, so that the Makefile will have
# the correct dependencies.
Makefile: Make-in ../config.status SRC-POTFILES BLD-POTFILES
	cd .. \
	  && CONFIG_FILES=$(subdir)/Makefile.in:$(subdir)/Make-in \
	     CONFIG_HEADERS= $(SHELL) ./config.status

# Tell versions [3.59,3.63) of GNU make not to export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
