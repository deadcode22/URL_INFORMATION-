# URL_INFORMATION-
## Prerequisites 
**WebChecker** is built with Python 3 and has been tested on MacOS so far.

## Installing WebChecker
To install **WebChecker** on your machine, run the following commands on your terminal:
```
git clone https://github.com/deadcode22/URL_INFORMATION-
cd URL_INFORMATION-
bash install.sh
python3 WebChecker.py -h

```

## Using WebChecker
**WebChecker** runs in terminal and can be used both with or without terminal arguments. The arguments it accepts are:
- `-u` or `--url` to specify the targeted URL
- `-b` or `--brute` to discover directories using bruteforce

Command example using arguments:
```
python3 WebChecker.py -u https://scoala.buzz/ -b /Users/laptop/Desktop/Wordlists/directories.txt 
```

Where `directories.txt` is a simple wordlist which contains the following lines (in this case):
```
login
cpanel
archive
resources
email
wp-content
admin
.httaccess
.httaccess1
passwd
passwords
intranet
```
*Note that you can use any other wordlist (ie. [dnsmap.txt](https://github.com/Blkzer0/Wordlists/blob/master/dnsmap.txt "dnsmap.txt")). Just specify the path to the file after `-b`*

If used withoth the `--url` switch, the program will prompt the user to enter the target website manually:
```
python3 WebChecker.py -u YOUR URL
```

## Support Telegram Channel : [Telegram Dead Code](https://t.me/Black_Code_22)
