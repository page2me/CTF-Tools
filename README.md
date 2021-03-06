# Useful CTF Tools
A Repo listing some useful tools for competing in CTF's and scripts used in CTF's.

# Crypto
Tools for Cryptographic challenges

### [CryptoCrack](https://sites.google.com/site/cryptocrackprogram/) (Windows)
A Windows tool for solving many basic ciphers. Supports many forms of substitution and transposition ciphers. Can analyze a ciphertext and guess what cipher was used to generate it.

### [John the Ripper](http://openwall.com/john/) (Kali/Linux)
A tool for cracking password hashes. Has functionality for wordlists, bruteforce, and masks. The [Jumbo Patch](https://github.com/magnumripper/JohnTheRipper) also has tools for zip files and PDF's.

### [quipquip](http://quipqiup.com/) (Website)
A website that can solve simple substitution ciphers.

### [Rumkin](http://rumkin.com/tools/cipher/)  (Website)
A website with a bunch of tools for solving basic ciphers.

### [Yafu](https://sourceforge.net/projects/yafu/) (Windows)
A tool for factoring integers. Very useful for challenges involving RSA and RSA-like algorithms.

# Forensics
Tools for forensic challenges.

### Binwalk (Kali/Linux)
[Link](http://binwalk.org/).
A tool for analyzing binaries. Able to identify different files in a binary.

### File utility (Kali/Linux)
A common Linux utility able to identify many kinds of files.

### [Foremost](http://foremost.sourceforge.net/) (Kali/Linux)
A file carver. Able to extract many different kinds of files from an image.

# Reverse Engineering
Tools for Reverse Engineering challenges

### [GDB](https://sourceware.org/gdb/current/onlinedocs/gdb/) (Kali/Linux)
A tool for debugging applications on linux. Extremely useful for dynamic debugging.

### [Helios](https://github.com/helios-decompiler/Helios) (Linux)
A compilation of multiple java disassemblers and decompilers. Very useful for Java RE.

### [JD-GUI](http://jd.benow.ca/) (Kali/Linux)

A java decompiler with a nice GUI. Cannot decompile Java 8.

### [Radare2](http://www.radare.org/r/) (Kali/Linux)
A tool for disassembling binaries and dynamic debugging. The most full featured free disassembler available. Not for the faint of heart.

### [Uncompyle6](https://github.com/rocky/python-uncompyle6) (Linux)
A compilation of multiple python decompilers. Can decompile python 2.2 to 3.6.

# Steganography
Tools for solving Steganography challenges.

### [Digital Invisible Ink Toolkit](http://diit.sourceforge.net/) (Windows/Linux)
A tool for hiding and extracting messages in images using certain algorithms. Loved by [NCL](http://www.nationalcyberleague.org/) and [Metropolis](http://cyberskyline.com/metropolis-2016/).

### [LSB Toolkit](https://github.com/luca-m/lsb-toolkit) (Linux)
A collection of python utilities for analyzing an image for LSB.

### [Steghide](http://steghide.sourceforge.net/) (Linux)
A Steganography tool able to hide messages in a variety of files.

# Web
Tools for web challenges

### [Burp](https://portswigger.net/burp/) (Kali/Linux)
A large suite of tools for web recon and vulnerability scanning and exploit. Particularly useful for spidering and fuzzing.

### [MXToolBox](https://mxtoolbox.com/) (Website)
A website with a bunch of tools for analyzing a website. Tools include dns lookup, reverse lookup, and basic port scanning.

### [Sqlmap](http://sqlmap.org/) (Kali/Linux)
[Pronounced Sequel-Map](https://english.stackexchange.com/questions/7231/how-is-sql-pronounced). A very powerful SQL injection tool. Extremely useful for non-blind SQLi.
