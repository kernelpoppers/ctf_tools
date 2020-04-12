# CTF Tools
Primarily for tools used to solve CTF challenges

### Contributing

As you learn how to use new tools that could be useful for CTF's please add them here

### Things you may want to consider adding with your contribution
* Short details of the challenge it helped solve
* Command line arguments and how you used them
* Use links for useful webpages instead of their homepage
* Anything else you think could be helpful

## All Around Tools
- [CyberChef](https://gchq.github.io/CyberChef/) - All around usage tool for transforming data
- [Wireshark](https://www.wireshark.org/) - Analyze the network dumps.

## PWN
## Interactions
- [pwntools](http://docs.pwntools.com/en/stable/) - Python library for interacting with challenges, has extensions for python 2.7 and 3+
    - Has modules for ssh, nc, gdb, loading binaries for rop and disassembly
    - Used in most writeups or the code for writeups relating to pwning
### Debuggers and Extensions
- [GDB](https://www.gnu.org/software/gdb/) - The GNU project debugger
- [GEF](https://gef.readthedocs.io/en/master/) - GDB Enhanced Features GDB plugin that is like PEDA but all source is in one file and is better
- [PEDA](https://github.com/longld/peda) - GDB plugin (only python2.7)

### Disasemblers/Decompilers
- [Binary Ninja](https://binary.ninja/) - Binary analysis framework
- [Ghidra](https://ghidra-sre.org/) - Open Source suite of reverse engineering tools.  Similar to IDA Pro.
- [Hopper](http://www.hopperapp.com/) - Reverse engineering tool (disassembler) for OSX and Linux
- [IDA Pro](https://www.hex-rays.com/products/ida/) - Most used Reversing software
- [Jadx](https://github.com/skylot/jadx) - Decompile Android files
- [Java Decompilers](http://www.javadecompilers.com) - An online decompiler for Java and Android APKs
- [Krakatau](https://github.com/Storyyeller/Krakatau) - Java decompiler and disassembler
- [radare2](https://github.com/radare/radare2) - A portable reversing framework

### Exploits
- [DLLInjector](https://github.com/OpenSecurityResearch/dllinjector) - Inject dlls in processes
- [libformatstr](https://github.com/hellman/libformatstr) - Simplify format string exploitation.
- [Metasploit](http://www.metasploit.com/) - Penetration testing software
  - [Cheatsheet](https://www.comparitech.com/net-admin/metasploit-cheat-sheet/)
- [one_gadget](https://github.com/david942j/one_gadget) -  A tool to find the one gadget `execve('/bin/sh', NULL, NULL)` call
  - `gem install one_gadget`
- [Pwntools](https://github.com/Gallopsled/pwntools) - CTF Framework for writing exploits
- [Qira](https://github.com/BinaryAnalysisPlatform/qira) - QEMU Interactive Runtime Analyser
- [ROP Gadget](https://github.com/JonathanSalwan/ROPgadget) - Framework for ROP exploitation
- [V0lt](https://github.com/P1kachu/v0lt) - Security CTF Toolkit

## Web
### Proxy
- [BurpSuite]() - A graphical tool to testing website security. 
- [OWASP ZAP](https://www.owasp.org/index.php/Projects/OWASP_Zed_Attack_Proxy_Project) - Intercepting proxy to replay, debug, and fuzz HTTP requests and responses

### Other
- [SQLMap](https://github.com/sqlmapproject/sqlmap) - Automatic SQL injection and database takeover tooli
- [W3af](https://github.com/andresriancho/w3af) -  Web Application Attack and Audit Framework.
- [XSSer](http://xsser.sourceforge.net/) - Automated XSS testor
- Nikto - Open Source (GPL) web server scanner which performs comprehensive tests against web servers
- [JSONBee](https://github.com/zigoo0/JSONBee) - A ready to use JSONP endpoints to help bypass content security policy of different websites.
- [Google CSP Evaluator](https://csp-evaluator.withgoogle.com) - CSP Evaluator allows developers and security experts to check if a Content Security Policy (CSP) serves as a strong mitigation against cross-site scripting attacks.

## Networking
- [Bettercap](https://github.com/bettercap/bettercap) - Framework to perform MITM (Man in the Middle) attacks.
- [Wireshark](https://www.wireshark.org/) - Analyze the network dumps.
- [tshark](https://www.wireshark.org/docs/man-pages/tshark.html) - Analyze dumps from the commandline.
- [NetworkMiner](https://www.netresec.com/?page=NetworkMiner) - Nice auto gui for Network Traffic Analysis. Good for finding files and sessions.

## Cryptography
- [FeatherDuster](https://github.com/nccgroup/featherduster) - An automated, modular cryptanalysis tool
- [Hash Extender](https://github.com/iagox86/hash_extender) - A utility tool for performing hash length extension attacks
- [PkCrack](https://www.unix-ag.uni-kl.de/~conrad/krypto/pkcrack.html) - A tool for Breaking PkZip-encryption
- [fcrackzip](http://manpages.ubuntu.com/manpages/trusty/man1/fcrackzip.1.html) - a Free/Fast Zip Password Cracker
- [RSACTFTool](https://github.com/Ganapati/RsaCtfTool) - A tool for recovering RSA private key with various attack
- [RSATool](https://github.com/ius/rsatool) - Generate private key with knowledge of p and q
- [XORTool](https://github.com/hellman/xortool) - A tool to analyze multi-byte xor cipher

## Stegonagraphy
- [Stego Checklist](https://georgeom.net/StegOnline/checklist) - Checklist for solving stego challenges
- [StegOnline](https://georgeom.net/StegOnline/upload) - Stego solver
- [steghide](https://github.com/StefanoDeVuono/steghide) - hides and extracts data from files.
- [stegdetect](https://linux.die.net/man/1/stegdetect) - Runs statistical tests to determine if steganographic content is present and tries to figure out how.
- [Binwalk](https://github.com/ReFirmLabs/binwalk) - Can be used to search a given binary image for embedded files and executable code.
- [foremost](https://tools.kali.org/forensics/foremost) - Navy's version of Binwalk (may catch something binwalk misses)
- [stegsolve](https://github.com/zardus/ctf-tools/tree/master/stegsolve) - Can be used to find hidden information in files
    - Used to solve a hackthebox stego challenge
- [zsteg](https://github.com/zed-0xff/zsteg) - Can be used to find steganography in png and bmp files
    - Used during affinity CTF to find hidden information
- [stegoveritas](https://github.com/bannsec/stegoVeritas) - Similar to zsteg
    - Used during affinity CTF to find hidden information

## Forensics
- [volatility](https://github.com/volatilityfoundation/volatility) - Common forensics tool for system memory dumps (can be finiky)
- [pspy](https://github.com/DominicBreuker/pspy) - Low privilege process snooper

## OSINT/Trivia
- [Google dorking](https://securitytrails.com/blog/google-hacking-techniques) - Using google to find things you shouldn't.
- [Shodan](https://www.shodan.io/) - Online webscanner service (note you do not have permission to view actual services; BE CAREFUL)
- [Censys](https://censys.io/) - Online scanner for websites and certificates

## Misc
- [Webhook Tester](https://webhook.site) - Useful for getting web requests to a public site without creating one
- [wiggle](https://wigle.net/) - Online wardriving site. Gives access to wifi network information across the contry
    - used on NCL past 2 seasons



##### Inspiration from https://github.com/apsdehal/awesome-ctf
