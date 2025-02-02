# GREENWHISPER

## Description:

This is a simple shell script that extracts certain strings from a file, these could be hidden encoded messages in a jpg, to IPV4 addresses from an ELF, I decided to create this to save a lot of time when attempting Steganography challenges.<br />

<b>[+] Author:</b> xakep<br />
<b>[+] Language:</b> Bash<br />
<b>[+] OS:</b> Linux<br />

## HTTP Extraction:
![alt text](https://i.imgur.com/oZynx0V.gif "Greenwhisper HTTP")

<b>MD5 Extraction:</b> - https://i.imgur.com/9rxJEaQ.gif


## Requirements:

[+] strings<br />
[+] xxd<br />
[+] egrep<br />
[+] exiftool<br />

## Searches for:

[+] IPV4 Addresses<br />
[+] MD5 Hashes<br />
[+] HTTP/HTTPS/FTP URL's<br />
[+] Groestlcoin Addresses<br />
[+] Email Addresses<br />
[+] ASCII Words, such as domains/hostnames/words in general<br />
[+] Base64 Encoded strings<br />
[+] An array of integers<br />
[+] Binary strings<br />

## Creates:
[+] Exif data pulled from the file<br />
[+] Hex dump of the file for manual analysis<br />
[+] Determines what type of file it is<br />

## Install:

```
$ git clone https://github.com/xakepnz/GREENWHISPER.git
```

```
$ cd GREENWHISPER
```

```
$ chmod +x greenwhisper
```

## Debian/Ubuntu Install:

```
$ git clone https://github.com/xakepnz/GREENWHISPER.git
```

```
$ cd GREENWHISPER
```

```
$ chmod +x greenwhisper && chmod +x install.sh
```

```
$ ./install.sh
```

## Usage:

```
$ ./greenwhisper my-file.jpg
```

<b>Optional:</b>

```
$ sudo cp greenwhisper /bin/
```

```
$ greenwhisper /steg-challenges/hidden.png
```
