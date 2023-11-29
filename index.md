---
layout: page
title: Home
---

**_We love UNIX, Linux, BSD!_**

> "If it can't be coded in C, you don't need it."
> -Some old-school hippie UNIX programmer

`Hello, world` in C
```c
#include <stdio.h>

int main () {
    printf("Hello, world");
    return 0;
}
```

`Hello, world` in C++
```c++
#include <iostream>

int main () {
    std::cout << "Hello, world";
    return 0;
}
```

`Hello, world` in C#
```c#
namespace HelloWorld
{
    class Hello {
        static void Main(string[] args)
        {
            System.Console.WriteLine("Hello, world");

        }
    }
}
```
### Chimera Linux

Chimera uses `doas` by default instead of `sudo`. However, you may install `sudo` for super-user privileges: `apk add sudo`

`chimerautils` are found in `/usr/bin`. Running `apk info -L chimerautils` in your terminal will list all components.

Descriptions are taken verbatim from official manpages and follow the convention of `command;` `description;` `manpage`. Where no manpage exists, see `command --help`.

## chimerautils

### A
`addpart`
see `addpart --help`

`awk`
pattern-directed scanning and processing language; AWK(1)

### B
`b64decode`
base64 decoder; BINTRANS(1)

`b64encode`
base64 encoder; BINTRANS(1)

`base64`
base64 encoder/decoder; BINTRANS(1)

`basename`
return file name or directory portion of pathname; BASENAME(1)

`bintrans`
encode/decode a binary file; BINTRANS(1)

`bzcmp`
compare compressed files; ZDIFF(1)

`bzdiff`
compare compressed files; ZDIFF(1)

`bzegrep`
grep compressed files; ZGREP(1)

`bzfgrep`
grep compressed files; ZGREP(1)

`bzgrep`
grep compressed files; ZGREP(1)

### C
`cat`
concatenate and print files; CAT(1)

`chgrp`
change group; CHGRP(1)

`chmod`
change file modes; CHMOD(1)

`chown`
change file owner or group; CHOWN(1)

`chroot`
change root directory; CHROOT(8)

`cksum`
display file checksums and block counts; CKSUM(1)

`cmp`
compare two files; CMP(1)

`col`
filter reverse line feeds from input; COL(1)

`colrm`
remove columns from a file; COLRM(1)

`column`
columnate lists; COLUMN(1)

`comm`
select or reject lines common to two files; COMM(1)

`cp`
copy files; CP(1)

`csplit`
split files based on context; CSPLIT(1)

`ctrlaltdel`
see `ctrlaltdel --help`

`cut`
cut out selected portions of each line of a file; CUT(1)

# D
date display or set date and time; DATE(1)  
dd convert and copy a file; DD(1)  
delpart see --help
df display free disk space; DF(1)  
diff differential file and directory comparator; DIFF (1)
diff3 3-way differential file comparison; DIFF3(1)  
dir see --help  
dirname return filename or directory portion of pathname; BASENAME(1)  
du display disk usage statistics; DU(1)  

### E
echo write arguments to the standard output; ECHO(1)  
ed THE standard text editor; ED(1) jk  
egrep file pattern searcher; GREP(1)  
env set environment and execute command, or print environment; ENV(1)  
expand expand tabs to spaces, and vice versa; EXPAND(1)  
expr evaluate expression; EXPR (1)  

### F
factor factor a number, generate primes; FACTOR(6)  
fallocate see --help  
false return false value(1)  
fgrep file pattern searcher; GREP(1)  
find walk a file hierarchy; FIND(1)  
flock see --help  
fmt simple text formatter; FMT(1)  
fold fold long lines for finite width output device; FOLD(1)  
fsfreeze suspend access to a filesystem; see --help  

### G
getopt parse command options; GETOPT(1)  
grep file pattern searcher; GREP(1)  
groups show group memberships; GROUPS(1)  
gunzip compression/decompression tool using Lempel-Ziv coding (LZ77); GZIP(1)  
gzcat compression/decompression tool using Lempel-Ziv coding (LZ77); GZIP(1)  
gzexe create auto-decompressing executables; GZEXE(1)  
gzip compression/decompression tool using Lempel-Ziv coding (LZ77); GZIP(1)  

### H
hd ASCII, decimal, hexadecimal, octal dump; HEXDUMP(1)  
head display first lines of a file; HEAD(1)  
hexdump ASCII, decimal, hexadecimal, octal dump; HEXDUMP(1)  
hostid see --help  
hostname set or print name of current host system; HOSTNAME(1)



### W
wall write a message to users; WALL(1)  
wc word, line, character, and byte count; WC (1)  
whereis locate programs; WHEREIS(1)  
which locate a program file in the user's path; WHICH(1)  
who display who is on the system; WHO(1)  
whoami display effective user id; WHOAMI(1)  
write  

### X
xargs construct argument list(s) and execute utility; XARGS(1)  
xzcmp compare compressed files; ZDIFF(1)  
xzdiff compare compressed files; ZDIFF(1)  
xzegrep grep compressed files; ZGREP(1)  
xzfgrep compare compressed files; ZGREP(1)  
xzgrep compare compressed files; ZGREP(1)  

### Y
yes be repetitively affirmative; YES(1) try it!

### Z
zcat compression/decompression tool using Lempel-Ziv coding (LZ77); GZIP(1)  
zcmp compare compressed files; ZDIFF(1)  
zdiff compare compressed files; ZDIFF(1)  
zegrep grep compressed files; ZGREP(1)  
zfgrep grep compressed files; ZGREP(1)  
zforce force gzip files to have a .gz suffix; ZFORCE(1)  
zgrep grep compressed files; ZGREP(1)  
zmore view compressed files; ZMORE(1)  
znew convert compressed files to gzipped files; ZNEW(1)  
zstdegrep grep compressed files; ZGREP(1)  
zstdfgrep grep compressed files; ZGREP(1)  
zstdgrep grep compressed files; ZGREP(1)
