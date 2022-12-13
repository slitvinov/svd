.POSIX:
.SUFFIXES:
.SUFFIXES: .c .o .a60

CFLAGS = -Og -g
MARST = marst
L = libsvd.a
O = \
minifit.o\
printreal.o\
svd.o\

$L: $O; ar r $@ $O && ranlib $@
.c.o:; $(CC) $(CFLAGS) $< -c
.a60.c:; $(MARST) $< -o $@
clean:; rm -f $L $O
