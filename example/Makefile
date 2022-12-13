.POSIX:
.SUFFIXES:
.SUFFIXES: .c .o .a60

MARST_LDFLAGS = -static  -L../lib -lsvd -lalgol -lm
CFLAGS = -Og -g
MARST = marst
M = \
svd\
minifit\

all: $M
.c:; $(CC) $(CFLAGS) $< $(MARST_LDFLAGS) $(LDFLAGS) -o $@
.a60.c:; $(MARST) $< -o $@

clean:; rm -f $M $(M:=.c)
