VER=007
ZIP=zip
MKDIR=mkdir
CP=cp
XHAIRS=crosshair1.tga crosshair2.tga crosshair3.tga crosshair4.tga
PK3=xhair_byce_$(VER).pk3
INDIR=~/.warsow-1.0/basewsw

pk3: $(XHAIRS)
	$(MKDIR) -p gfx/hud
	$(CP) $(XHAIRS) gfx/hud
	$(ZIP) -rm $(PK3) gfx

install:
	$(CP) $(PK3) $(INDIR)

all: pk3

default: all
