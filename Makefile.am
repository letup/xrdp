ACLOCAL_AMFLAGS = -I m4
AM_DISTCHECK_CONFIGURE_FLAGS = --without-systemdsystemunitdir

EXTRA_DIST = \
  COPYING \
  astyle_config.as \
  bootstrap \
  coding_style.md \
  description-pak \
  design.txt \
  faq-compile.txt \
  faq-general.txt \
  file-loc.txt \
  fontdump \
  install.txt \
  m4 \
  postinstall-pak \
  readme.txt \
  tcutils \
  tests \
  vrplayer \
  xorg

if XRDP_NEUTRINORDP
NEUTRINORDPDIR = neutrinordp
else
NEUTRINORDPDIR =
endif

if XRDP_XRDPVR
XRDPVRDIR = xrdpvr
else
XRDPVRDIR =
endif

if XRDP_RFXCODEC
RFXCODECDIR = librfxcodec
else
RFXCODECDIR =
endif

SUBDIRS = \
  libpainter \
  common \
  vnc \
  rdp \
  xup \
  mc \
  $(NEUTRINORDPDIR) \
  libxrdp \
  $(RFXCODECDIR) \
  xrdp \
  sesman \
  keygen \
  docs \
  instfiles \
  genkeymap \
  xrdpapi \
  pkgconfig \
  $(XRDPVRDIR)
