LDLIBS = -lm

all: caesar rot13

clean:
	rm -f caesar rot13

install: caesar rot13 caesar.6
	mkdir -p ~/.local/bin ~/.local/share/man/man6
	cp caesar rot13 ~/.local/bin
	cp caesar.6 ~/.local/share/man/man6
	cp caesar.6 ~/.local/share/man/man6/rot13.6
