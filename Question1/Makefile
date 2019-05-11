SHELL = /bin/bash
srcfiles := $(shell echo src/{00..10}.txt)

src/XXXXXX
        @[ -d src ] || mkdir src
        echo $* > XXXXXX

destXXXXXX: srcXXXXXX
        @[ -d dest ] || mkdir dest
        cp XXXXXX

destfiles := $(patsubst src/XXXXXX.txt,dest/XXXXXX.txt,$(srcfiles))
destination: $(destfiles)
pack:
	tar -cvf pack.tar  dest
all: destination pack


clean:
	rm -rf src
	rm -rf dest
	rm -f pack.tar




