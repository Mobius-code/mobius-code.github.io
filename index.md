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

### commonly used commands
`cat`
concatenate and print files

`chmod`
change file modes

`chown`
change file owner and group

`chroot`
change root directory

`cksum`
display file checksums and block counts

`cp`
copy files

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
