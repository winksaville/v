all: v

v: v.c
	cc -w -o v v.c
	./v -o v .

v.c:
	wget https://raw.githubusercontent.com/vlang/vc/master/v.c

test:
	find .. -name '*_test.v' | xargs v {}

clean:
	-rm -f v vc v.c
