all: clean build
clean:
	rm "${DEST}/open.o" || true
build:
	mkdir "${DEST}" || true
	clang -c -o "${DEST}/open.o" open.m
