# Zip of Death (ZOD)
This is a decompression bomb (also known as zip of death or zip bomb) designed to
crash or render useless the program or system reading it.

It is usually a small file for ease of transport and to avoid suspicion.
However, when the file is unpacked, its contents are more than the system can
handle. It is often employed to disable antivirus software, in order to create
an opening for more traditional viruses.

Rather than hijacking the normal operation of the program, a zip bomb allows the
program to work as intended, but the archive is carefully crafted so that
unpacking it (e.g. by a virus scanner in order to scan for viruses) requires
inordinate amounts of time, disk space or memory.

*Most modern antivirus programs can detect whether a file is a zip bomb, to
avoid unpacking it.*

### `42.zip`
This repository contains the `42.zip` zip bomb, which is a zip file consisting
of 42 kilobytes of compressed data, containing five layers of nested zip files
in sets of 16, each bottom layer archive containing a 4.3 gigabyte
(4 294 967 295 bytes; ~ 3.99 GiB) file for a total of 4.5 petabytes
(4 503 599 626 321 920 bytes; ~ 3.99 PiB) of uncompressed data.

So, if you extract all the files, you will most likely run out of space.

```
16 x       4 294 967 295 bytes =        68 719 476 720 bytes ( 68.7 GB)
16 x      68 719 476 720 bytes =     1 099 511 627 520 bytes (  1.1 TB)
16 x   1 099 511 627 520 bytes =    17 592 186 040 320 bytes ( 17.6 TB)
16 x  17 592 186 040 320 bytes =   281 474 976 645 120 bytes (281.5 TB)
16 x 281 474 976 645 120 bytes = 4 503 599 626 321 920 bytes (  4.5 PB)
```

#### Password
`42`

# This is a new vesion

# ZIPBOMB
2048 yottabyte Zip Bomb

This zip bomb uses overlapping files and recursion to achieve 7 layers with 256 files each, with the last being a 32GB file.

It is only 266 KB on disk.

(overlapping files are broken meaning the zip bomb is "corrupted" but you can still read them at least in Windows.)

If you extract 32-256^7.zip once you will be fine which is why I made 32-256.zip which is 8TB decompressed and if you extract it once you're done for

(file sizes are spoofed so that your OS won't think that you don't have enough disk space)

NOTE: 32-256-zipped.zip contains ONE FILE, 32-256.zip which is the actual bomb being <40 MB in size and decompresses to 8TB

64x4096-Z.zip contains ONE FILE, 64x4096.zip which is 77 MB and is kind of dangerous

(I had to zip it twice because of file size limits)

* 1TB = 1,099,511,627,776 bytes

