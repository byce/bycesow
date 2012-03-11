VER=002
PK3=hud_byce_$(VER).pk3
CP=cp
INDIR=~/.warsow-0.6/basewsw

all:
	zip -r $(PK3) fonts gfx huds

default: all

install:
	$(CP) $(PK3) $(INDIR)

clean:
	rm -f $(PK3)
