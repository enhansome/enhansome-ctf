# Awesome CTF with stars

A curated list of [Capture The Flag](https://en.wikipedia.org/wiki/Capture_the_flag#Computer_security) (CTF) frameworks, libraries, resources, softwares and tutorials. This list aims to help starters as well as seasoned CTF players to find everything related to CTFs at one place.

### Contributing

Please take a quick look at the [contribution guidelines](https://github.com/apsdehal/ctf-tools/blob/master/CONTRIBUTING.md) ⭐ 11,818 | 🐛 66 | 🌐 JavaScript | 📅 2024-07-22 first.

#### *If you know a tool that isn't present here, feel free to open a pull request.*

### Why?

It takes time to build up collection of tools used in CTF and remember them all. This repo helps to keep all these scattered tools at one place.

### Contents

* [Awesome CTF](#awesome-ctf)
  * [Create](#create)
    * [Forensics](#forensics)
    * [Platforms](#platforms)
    * [Steganography](#steganography)
    * [Web](#web)
  * [Solve](#solve)
    * [Attacks](#attacks)
    * [Bruteforcers](#bruteforcers)
    * [Cryptography](#crypto)
    * [Exploits](#exploits)
    * [Forensics](#forensics-1)
    * [Networking](#networking)
    * [Reversing](#reversing)
    * [Services](#services)
    * [Steganography](#steganography-1)
    * [Web](#web-1)

* [Resources](#resources)
  * [Operating Systems](#operating-systems)
  * [Starter Packs](#starter-packs)
  * [Tutorials](#tutorials)
  * [Wargames](#wargames)
  * [Websites](#websites)
  * [Wikis](#wikis)
  * [Writeups Collections](#writeups-collections)

# Create

*Tools used for creating CTF challenges*

* [Kali Linux CTF Blueprints](https://www.packtpub.com/eu/networking-and-servers/kali-linux-ctf-blueprints) - Online book on building, testing, and customizing your own Capture the Flag challenges.

## Forensics

*Tools used for creating Forensics challenges*

* [Dnscat2](https://github.com/iagox86/dnscat2) ⭐ 3,963 | 🐛 98 | 🌐 PHP | 📅 2024-03-14 - Hosts communication through DNS.
* [Kroll Artifact Parser and Extractor (KAPE)](https://learn.duffandphelps.com/kape) - Triage program.
* [Magnet AXIOM](https://www.magnetforensics.com/downloadaxiom) - Artifact-centric DFIR tool.
* [Registry Dumper](http://www.kahusecurity.com/posts/registry_dumper_find_and_dump_hidden_registry_keys.html) - Dump your registry.

## Platforms

*Projects that can be used to host a CTF*

* [CTFd](https://github.com/isislab/CTFd) ⭐ 6,813 | 🐛 427 | 🌐 Python | 📅 2026-08-27 - Platform to host jeopardy style CTFs from ISISLab, NYU Tandon.
* [FBCTF](https://github.com/facebook/fbctf) ⚠️ Archived - Platform to host Capture the Flag competitions from Facebook.
* [SecGen](https://github.com/cliffe/SecGen) ⭐ 2,795 | 🐛 37 | 🌐 Python | 📅 2026-08-28 - Security Scenario Generator. Creates randomly vulnerable virtual machines.
* [RootTheBox](https://github.com/moloch--/RootTheBox) ⭐ 1,129 | 🐛 69 | 🌐 Python | 📅 2026-04-24 - A Game of Hackers (CTF Scoreboard & Game Manager).
* [Mellivora](https://github.com/Nakiami/mellivora) ⭐ 451 | 🐛 29 | 🌐 PHP | 📅 2023-12-21 - A CTF engine written in PHP.
* [PicoCTF](https://github.com/picoCTF/picoCTF) ⚠️ Archived - The platform used to run picoCTF. A great framework to host any CTF.
* [Haaukins](https://github.com/aau-network-security/haaukins) ⭐ 198 | 🐛 20 | 🌐 Go | 📅 2026-08-06- A Highly Accessible and Automated Virtualization Platform for Security Education.
* [echoCTF.RED](https://github.com/echoCTF/echoCTF.RED) ⭐ 150 | 🐛 26 | 🌐 PHP | 📅 2026-09-01 - Develop, deploy and maintain your own CTF infrastructure.
* [NightShade](https://github.com/UnrealAkama/NightShade) ⭐ 127 | 🐛 7 | 🌐 JavaScript | 📅 2017-05-28 - A simple security CTF framework.
* [PyChallFactory](https://github.com/pdautry/py_chall_factory) ⭐ 117 | 🐛 0 | 🌐 Python | 📅 2025-08-19 - Small framework to create/manage/package jeopardy CTF challenges.
* [OpenCTF](https://github.com/easyctf/openctf) ⭐ 85 | 🐛 11 | 🌐 Python | 📅 2023-02-16 - CTF in a box. Minimal setup required.
* [HackTheArch](https://github.com/mcpa-stlouis/hack-the-arch) ⭐ 73 | 🐛 17 | 🌐 Ruby | 📅 2023-03-08 - CTF scoring platform.
* [MotherFucking-CTF](https://github.com/andreafioraldi/motherfucking-ctf) ⭐ 52 | 🐛 0 | 🌐 Python | 📅 2019-05-29 - Badass lightweight plaform to host CTFs. No JS involved.
* [Scorebot](https://github.com/legitbs/scorebot) ⭐ 51 | 🐛 3 | 🌐 Python | 📅 2017-09-23 - Platform for CTFs by Legitbs (Defcon).

## Steganography

*Tools used to create stego challenges*

Check solve section for steganography.

## Web

*Tools used for creating Web challenges*

*JavaScript Obfustcators*

* [Metasploit JavaScript Obfuscator](https://github.com/rapid7/metasploit-framework/wiki/How-to-obfuscate-JavaScript-in-Metasploit) ⭐ 38,927 | 🐛 605 | 🌐 Ruby | 📅 2026-09-01
* [Uglify](https://github.com/mishoo/UglifyJS) ⭐ 13,381 | 🐛 45 | 🌐 JavaScript | 📅 2024-11-22

# Solve

*Tools used for solving CTF challenges*

## Attacks

*Tools used for performing various kinds of attacks*

* [Bettercap](https://github.com/bettercap/bettercap) ⭐ 19,920 | 🐛 44 | 🌐 Go | 📅 2026-08-13 - Framework to perform MITM (Man in the Middle) attacks.
* [Yersinia](https://github.com/tomac/yersinia) ⭐ 867 | 🐛 29 | 🌐 C | 📅 2023-09-15 - Attack various protocols on layer 2.

## Crypto

*Tools used for solving Crypto challenges*

* [RSACTFTool](https://github.com/Ganapati/RsaCtfTool) ⭐ 7,108 | 🐛 3 | 🌐 Python | 📅 2026-08-12 - A tool for recovering RSA private key with various attack.
* [RSATool](https://github.com/ius/rsatool) ⭐ 1,657 | 🐛 2 | 🌐 Python | 📅 2026-07-20 - Generate private key with knowledge of p and q.
* [XORTool](https://github.com/hellman/xortool) ⭐ 1,488 | 🐛 3 | 🌐 Python | 📅 2025-05-21 - A tool to analyze multi-byte xor cipher.
* [Hash Extender](https://github.com/iagox86/hash_extender) ⭐ 1,212 | 🐛 10 | 🌐 C | 📅 2025-01-27 - A utility tool for performing hash length extension attacks.
* [FeatherDuster](https://github.com/nccgroup/featherduster) ⭐ 1,137 | 🐛 28 | 🌐 Python | 📅 2021-12-02 - An automated, modular cryptanalysis tool.
* [padding-oracle-attacker](https://github.com/KishanBagaria/padding-oracle-attacker) ⭐ 217 | 🐛 7 | 🌐 TypeScript | 📅 2023-02-03 - A CLI tool to execute padding oracle attacks.
* [CyberChef](https://gchq.github.io/CyberChef) - Web app for analysing and decoding data.
* [PkCrack](https://www.unix-ag.uni-kl.de/~conrad/krypto/pkcrack.html) - A tool for Breaking PkZip-encryption.
* [QuipQuip](https://quipqiup.com) - An online tool for breaking substitution ciphers or vigenere ciphers (without key).

## Bruteforcers

*Tools used for various kind of bruteforcing (passwords etc.)*

* [John The Jumbo](https://github.com/magnumripper/JohnTheRipper) ⭐ 13,576 | 🐛 514 | 🌐 C | 📅 2026-08-01 - Community enhanced version of John the Ripper.
* [Patator](https://github.com/lanjelot/patator) ⭐ 3,927 | 🐛 36 | 🌐 Python | 📅 2025-05-20 - Patator is a multi-purpose brute-forcer, with a modular design.
* [Nozzlr](https://github.com/intrd/nozzlr) ⭐ 65 | 🐛 2 | 🌐 Python | 📅 2023-01-11 - Nozzlr is a bruteforce framework, trully modular and script-friendly.
* [Hashcat](https://hashcat.net/hashcat/) - Password Cracker
* [Hydra](https://tools.kali.org/password-attacks/hydra) - A parallelized login cracker which supports numerous protocols to attack
* [John The Ripper](http://www.openwall.com/john/) - Password Cracker.
* [Ophcrack](http://ophcrack.sourceforge.net/) - Windows password cracker based on rainbow tables.
* [Turbo Intruder](https://portswigger.net/research/turbo-intruder-embracing-the-billion-request-attack) - Burp Suite extension for sending large numbers of HTTP requests

## Exploits

*Tools used for solving Exploits challenges*

* [Pwntools](https://github.com/Gallopsled/pwntools) ⭐ 13,669 | 🐛 118 | 🌐 Python | 📅 2026-08-30 - CTF Framework for writing exploits.
* [ROP Gadget](https://github.com/JonathanSalwan/ROPgadget) ⭐ 4,473 | 🐛 15 | 🌐 Python | 📅 2026-06-24 - Framework for ROP exploitation.
* [Qira](https://github.com/BinaryAnalysisPlatform/qira) ⭐ 4,070 | 🐛 69 | 🌐 C | 📅 2022-07-02 - QEMU Interactive Runtime Analyser.
* [one\_gadget](https://github.com/david942j/one_gadget) ⭐ 2,346 | 🐛 1 | 🌐 Ruby | 📅 2026-09-01 -  A tool to find the one gadget `execve('/bin/sh', NULL, NULL)` call.
  * `gem install one_gadget`
* [DLLInjector](https://github.com/OpenSecurityResearch/dllinjector) ⭐ 502 | 🐛 1 | 🌐 C++ | 📅 2013-01-07 - Inject dlls in processes.
* [V0lt](https://github.com/P1kachu/v0lt) ⚠️ Archived - Security CTF Toolkit.
* [libformatstr](https://github.com/hellman/libformatstr) ⭐ 346 | 🐛 5 | 🌐 Python | 📅 2021-11-02 - Simplify format string exploitation.
* [Metasploit](http://www.metasploit.com/) - Penetration testing software.
  * [Cheatsheet](https://www.comparitech.com/net-admin/metasploit-cheat-sheet/)

## Forensics

*Tools used for solving Forensics challenges*

* [Volatility](https://github.com/volatilityfoundation/volatility) ⚠️ Archived - To investigate memory dumps.
* [Fibratus](https://github.com/rabbitstack/fibratus) ⭐ 2,536 | 🐛 42 | 🌐 Go | 📅 2026-09-01 - Tool for exploration and tracing of the Windows kernel.
* [DVCS Ripper](https://github.com/kost/dvcs-ripper) ⭐ 1,785 | 🐛 11 | 🌐 Perl | 📅 2024-07-19 - Rips web accessible (distributed) version control systems.
* [USBRip](https://github.com/snovvcrash/usbrip) ⚠️ Archived - Simple CLI forensics tool for tracking USB device artifacts (history of USB events) on GNU/Linux.
* [Creddump](https://github.com/moyix/creddump) ⭐ 287 | 🐛 6 | 🌐 Python | 📅 2019-05-08 - Dump windows credentials.
* [Shellbags](https://github.com/williballenthin/shellbags) ⭐ 161 | 🐛 3 | 🌐 Python | 📅 2023-01-31 - Investigate NT\_USER.dat files.
* [Aircrack-Ng](http://www.aircrack-ng.org/) - Crack 802.11 WEP and WPA-PSK keys.
  * `apt-get install aircrack-ng`
* [Audacity](http://sourceforge.net/projects/audacity/) - Analyze sound files (mp3, m4a, whatever).
  * `apt-get install audacity`
* [Bkhive and Samdump2](http://sourceforge.net/projects/ophcrack/files/samdump2/) - Dump SYSTEM and SAM files.
  * `apt-get install samdump2 bkhive`
* [CFF Explorer](http://www.ntcore.com/exsuite.php) - PE Editor.
* [Exif Tool](http://www.sno.phy.queensu.ca/~phil/exiftool/) - Read, write and edit file metadata.
* [Extundelete](http://extundelete.sourceforge.net/) - Used for recovering lost data from mountable images.
* [Foremost](http://foremost.sourceforge.net/) - Extract particular kind of files using headers.
  * `apt-get install foremost`
* [Fsck.ext4](http://linux.die.net/man/8/fsck.ext3) - Used to fix corrupt filesystems.
* [Malzilla](http://malzilla.sourceforge.net/) - Malware hunting tool.
* [NetworkMiner](http://www.netresec.com/?page=NetworkMiner) - Network Forensic Analysis Tool.
* [PDF Streams Inflater](http://malzilla.sourceforge.net/downloads.html) - Find and extract zlib files compressed in PDF files.
* [Pngcheck](http://www.libpng.org/pub/png/apps/pngcheck.html) - Verifies the integrity of PNG and dump all of the chunk-level information in human-readable form.
  * `apt-get install pngcheck`
* [ResourcesExtract](http://www.nirsoft.net/utils/resources_extract.html) - Extract various filetypes from exes.
* [Snow](https://sbmlabs.com/notes/snow_whitespace_steganography_tool) - A Whitespace Steganography Tool.
* [Wireshark](https://www.wireshark.org) - Used to analyze pcap or pcapng files

*Registry Viewers*

* [OfflineRegistryView](https://www.nirsoft.net/utils/offline_registry_view.html) - Simple tool for Windows that allows you to read offline Registry files from external drive and view the desired Registry key in .reg file format.
* [Registry Viewer®](https://accessdata.com/product-download/registry-viewer-2-0-0) - Used to view Windows registries.

## Networking

*Tools used for solving Networking challenges*

* [Masscan](https://github.com/robertdavidgraham/masscan) ⭐ 25,963 | 🐛 414 | 🌐 C | 📅 2026-04-23 - Mass IP port scanner, TCP port scanner.
* [Nipe](https://github.com/GouveaHeitor/nipe) ⭐ 2,388 | 🐛 15 | 🌐 Perl | 📅 2026-06-27 - Nipe is a script to make Tor Network your default gateway.
* [Monit](https://linoxide.com/monitoring-2/monit-linux/) - A linux tool to check a host on the network (and other non-network activities).
* [Nmap](https://nmap.org/) - An open source utility for network discovery and security auditing.
* [Wireshark](https://www.wireshark.org/) - Analyze the network dumps.
  * `apt-get install wireshark`
* [Zeek](https://www.zeek.org) - An open-source network security monitor.
* [Zmap](https://zmap.io/) - An open-source network scanner.

## Reversing

*Tools used for solving Reversing challenges*

* [Jadx](https://github.com/skylot/jadx) ⭐ 50,301 | 🐛 442 | 🌐 Java | 📅 2026-08-31 - Decompile Android files.
* [radare2](https://github.com/radare/radare2) ⭐ 24,702 | 🐛 824 | 🌐 C | 📅 2026-09-01 - A portable reversing framework.
* [BinWalk](https://github.com/devttys0/binwalk) ⭐ 14,298 | 🐛 93 | 🌐 Rust | 📅 2026-08-11 - Analyze, reverse engineer, and extract firmware images.
* [Z3](https://github.com/Z3Prover/z3) ⭐ 12,627 | 🐛 56 | 🌐 C++ | 📅 2026-09-01 - A theorem prover from Microsoft Research.
* [Pwndbg](https://github.com/pwndbg/pwndbg) ⭐ 10,822 | 🐛 227 | 🌐 Python | 📅 2026-09-01 - A GDB plugin that provides a suite of utilities to hack around GDB easily.
* [Objection](https://github.com/sensepost/objection) ⭐ 9,356 | 🐛 56 | 🌐 Python | 📅 2026-07-23 - Runtime Mobile Exploration.
* [Angr](https://github.com/angr/angr) ⭐ 9,054 | 🐛 706 | 🌐 Python | 📅 2026-09-01 - platform-agnostic binary analysis framework.
* [GEF](https://github.com/hugsy/gef) ⭐ 8,332 | 🐛 14 | 🌐 Python | 📅 2026-08-20 - GDB plugin.
* [Androguard](https://github.com/androguard/androguard) ⭐ 6,222 | 🐛 45 | 🌐 Python | 📅 2026-08-13 - Reverse engineer Android applications.
* [PEDA](https://github.com/longld/peda) ⭐ 6,148 | 🐛 76 | 🌐 Python | 📅 2024-07-29 - GDB plugin (only python2.7).
* [Triton](https://github.com/JonathanSalwan/Triton/) ⭐ 4,279 | 🐛 40 | 🌐 C++ | 📅 2026-08-31 - Dynamic Binary Analysis (DBA) framework.
* [PINCE](https://github.com/korcankaraokcu/PINCE) ⭐ 3,075 | 🐛 6 | 🌐 Python | 📅 2026-08-24 - GDB front-end/reverse engineering tool, focused on game-hacking and automation.
* [Plasma](https://github.com/joelpx/plasma) ⭐ 3,071 | 🐛 15 | 🌐 Python | 📅 2021-08-31 - An interactive disassembler for x86/ARM/MIPS which can generate indented pseudo-code with colored syntax.
* [Krakatau](https://github.com/Storyyeller/Krakatau) ⭐ 2,248 | 🐛 25 | 🌐 Rust | 📅 2026-04-07 - Java decompiler and disassembler.
* [Barf](https://github.com/programa-stic/barf-project) ⭐ 1,452 | 🐛 17 | 🌐 Python | 📅 2019-11-24 - Binary Analysis and Reverse engineering Framework.
* [cwe\_checker](https://github.com/fkie-cad/cwe_checker) ⭐ 1,353 | 🐛 29 | 🌐 Rust | 📅 2026-08-20 - cwe\_checker finds vulnerable patterns in binary executables.
* [demovfuscator](https://github.com/kirschju/demovfuscator) ⭐ 764 | 🐛 3 | 🌐 C++ | 📅 2025-05-04 - A work-in-progress deobfuscator for movfuscated binaries.
* [Apk2Gold](https://github.com/lxdvs/apk2gold) ⭐ 700 | 🐛 18 | 🌐 Shell | 📅 2024-03-05 - Yet another Android decompiler.
* [PinCTF](https://github.com/ChrisTheCoolHut/PinCTF) ⭐ 505 | 🐛 8 | 🌐 Python | 📅 2020-04-12 - A tool which uses intel pin for Side Channel Analysis.
* [Uncompyle](https://github.com/gstarnberger/uncompyle) ⚠️ Archived - Decompile Python 2.7 binaries (.pyc).
* [Boomerang](https://github.com/BoomerangDecompiler/boomerang) ⭐ 405 | 🐛 38 | 🌐 C++ | 📅 2020-12-28 - Decompile x86/SPARC/PowerPC/ST-20 binaries to C.
* [ctf\_import](https://github.com/docileninja/ctf_import) ⭐ 114 | 🐛 1 | 🌐 C | 📅 2016-12-13 – run basic functions from stripped binaries cross platform.
* [ApkTool](http://ibotpeaches.github.io/Apktool/) - Android Decompiler.
* [Binary Ninja](https://binary.ninja/) - Binary analysis framework.
* [BinUtils](http://www.gnu.org/software/binutils/binutils.html) - Collection of binary tools.
* [Frida](https://github.com/frida/) - Dynamic Code Injection.
* [GDB](https://www.gnu.org/software/gdb/) - The GNU project debugger.
* [Ghidra](https://ghidra-sre.org/) - Open Source suite of reverse engineering tools.  Similar to IDA Pro.
* [Hopper](http://www.hopperapp.com/) - Reverse engineering tool (disassembler) for OSX and Linux.
* [IDA Pro](https://www.hex-rays.com/products/ida/) - Most used Reversing software.
* [Java Decompilers](http://www.javadecompilers.com) - An online decompiler for Java and Android APKs.
* [Pin](https://software.intel.com/en-us/articles/pin-a-dynamic-binary-instrumentation-tool) - A dynamic binary instrumentaion tool by Intel.
* [WinDbg](http://www.windbg.org/) - Windows debugger distributed by Microsoft.
* [Xocopy](http://reverse.lostrealm.com/tools/xocopy.html) - Program that can copy executables with execute, but no read permission.

*JavaScript Deobfuscators*

* [Detox](http://relentless-coding.org/projects/jsdetox/install) - A Javascript malware analysis tool.
* [Revelo](http://www.kahusecurity.com/posts/revelo_javascript_deobfuscator.html) - Analyze obfuscated Javascript code.

*SWF Analyzers*

* [RABCDAsm](https://github.com/CyberShadow/RABCDAsm) ⭐ 457 | 🐛 4 | 🌐 D | 📅 2023-03-31 - Collection of utilities including an ActionScript 3 assembler/disassembler.
* [Swftools](http://www.swftools.org/) - Collection of utilities to work with SWF files.
* [Xxxswf](https://bitbucket.org/Alexander_Hanel/xxxswf) -  A Python script for analyzing Flash files.

## Services

*Various kind of useful services available around the internet*

* [CSWSH](http://cow.cat/cswsh.html) - Cross-Site WebSocket Hijacking Tester.
* [Request Bin](https://requestbin.com/) - Lets you inspect http requests to a particular url.

## Steganography

*Tools used for solving Steganography challenges*

* [SmartDeblur](https://github.com/Y-Vladimir/SmartDeblur) ⭐ 2,412 | 🐛 13 | 🌐 C++ | 📅 2019-04-02 - Used to deblur and fix defocused images.
* [Zsteg](https://github.com/zed-0xff/zsteg/) ⭐ 1,620 | 🐛 6 | 🌐 Ruby | 📅 2026-01-28 - PNG/BMP analysis.
* [StegCracker](https://github.com/Paradoxis/StegCracker) ⚠️ Archived - Steganography brute-force utility to uncover hidden data inside files.
* [stegextract](https://github.com/evyatarmeged/stegextract) ⭐ 133 | 🐛 2 | 🌐 Shell | 📅 2023-05-21 - Detect hidden files and text in images.
* [AperiSolve](https://aperisolve.fr/) - Aperi'Solve is a platform which performs layer analysis on image (open-source).
* [Convert](http://www.imagemagick.org/script/convert.php) - Convert images b/w formats and apply filters.
* [Exif](http://manpages.ubuntu.com/manpages/trusty/man1/exif.1.html) - Shows EXIF information in JPEG files.
* [Exiftool](https://linux.die.net/man/1/exiftool) - Read and write meta information in files.
* [Exiv2](http://www.exiv2.org/manpage.html) - Image metadata manipulation tool.
* [Image Steganography](https://sourceforge.net/projects/image-steg/) - Embeds text and files in images with optional encryption. Easy-to-use UI.
* [Image Steganography Online](https://incoherency.co.uk/image-steganography) - This is a client-side Javascript tool to steganographically hide images inside the lower "bits" of other images
* [ImageMagick](http://www.imagemagick.org/script/index.php) - Tool for manipulating images.
* [Outguess](https://www.freebsd.org/cgi/man.cgi?query=outguess+\&apropos=0\&sektion=0\&manpath=FreeBSD+Ports+5.1-RELEASE\&format=html) - Universal steganographic tool.
* [Pngtools](https://packages.debian.org/sid/pngtools) - For various analysis related to PNGs.
  * `apt-get install pngtools`
* [Steganabara](https://www.openhub.net/p/steganabara) -  Tool for stegano analysis written in Java.
* [SteganographyOnline](https://stylesuxx.github.io/steganography/) - Online steganography encoder and decoder.
* [Stegbreak](https://linux.die.net/man/1/stegbreak) - Launches brute-force dictionary attacks on JPG image.
* [Steghide](http://steghide.sourceforge.net/) - Hide data in various kind of images.
* [StegOnline](https://georgeom.net/StegOnline/upload) - Conduct a wide range of image steganography operations, such as concealing/revealing files hidden within bits (open-source).
* [Stegsolve](http://www.caesum.com/handbook/Stegsolve.jar) - Apply various steganography techniques to images.

## Web

*Tools used for solving Web challenges*

* [SQLMap](https://github.com/sqlmapproject/sqlmap) ⭐ 38,337 | 🐛 32 | 🌐 Python | 📅 2026-09-01 - Automatic SQL injection and database takeover tool.
  `pip install sqlmap`
* [Commix](https://github.com/commixproject/commix) ⭐ 5,830 | 🐛 4 | 🌐 Python | 📅 2026-09-01 - Automated All-in-One OS Command Injection and Exploitation Tool.
* [W3af](https://github.com/andresriancho/w3af) ⭐ 4,901 | 🐛 2,031 | 🌐 Python | 📅 2023-02-22 -  Web Application Attack and Audit Framework.
* [Raccoon](https://github.com/evyatarmeged/Raccoon) ⭐ 4,010 | 🐛 14 | 🌐 Python | 📅 2026-04-21 - A high performance offensive security tool for reconnaissance and vulnerability scanning.
* [BurpSuite](https://portswigger.net/burp) - A graphical tool to testing website security.
* [Hackbar](https://addons.mozilla.org/en-US/firefox/addon/hackbartool/) - Firefox addon for easy web exploitation.
* [OWASP ZAP](https://www.owasp.org/index.php/Projects/OWASP_Zed_Attack_Proxy_Project) - Intercepting proxy to replay, debug, and fuzz HTTP requests and responses
* [Postman](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop?hl=en) - Add on for chrome for debugging network requests.
* [XSSer](http://xsser.sourceforge.net/) - Automated XSS testor.

# Resources

*Where to discover about CTF*

## Operating Systems

*Penetration testing and security lab Operating Systems*

* [Android Tamer](https://androidtamer.com/) - Based on Debian.
* [BackBox](https://backbox.org/) - Based on Ubuntu.
* [BlackArch Linux](https://blackarch.org/) - Based on Arch Linux.
* [Fedora Security Lab](https://labs.fedoraproject.org/security/) - Based on Fedora.
* [Kali Linux](https://www.kali.org/) - Based on Debian.
* [Parrot Security OS](https://www.parrotsec.org/) - Based on Debian.
* [Pentoo](http://www.pentoo.ch/) - Based on Gentoo.
* [URIX OS](http://urix.us/) - Based on openSUSE.
* [Wifislax](http://www.wifislax.com/) - Based on Slackware.

*Malware analysts and reverse-engineering*

* [Flare VM](https://github.com/fireeye/flare-vm/) ⭐ 8,983 | 🐛 28 | 🌐 PowerShell | 📅 2026-06-23 - Based on Windows.
* [REMnux](https://remnux.org/) - Based on Debian.

## Starter Packs

*Collections of installer scripts, useful tools*

* [CTF Tools](https://github.com/zardus/ctf-tools) ⭐ 9,511 | 🐛 12 | 🌐 Nix | 📅 2026-08-12 - Collection of setup scripts to install various security research tools.
* [LazyKali](https://github.com/jlevitsk/lazykali) ⭐ 50 | 🐛 4 | 🌐 Shell | 📅 2016-09-04 - A 2016 refresh of LazyKali which simplifies install of tools and configuration.

## Tutorials

*Tutorials to learn how to play CTFs*

* [MIPT CTF](https://github.com/xairy/mipt-ctf) ⭐ 283 | 🐛 0 | 🌐 Python | 📅 2021-12-26 - A small course for beginners in CTFs (in Russian).
* [CTF Field Guide](https://trailofbits.github.io/ctf/) - Field Guide by Trails of Bits.
* [CTF Resources](http://ctfs.github.io/resources/) -  Start Guide maintained by community.
* [How to Get Started in CTF](https://www.endgame.com/blog/how-get-started-ctf) - Short guideline for CTF beginners by Endgame
* [Intro. to CTF Course](https://www.hoppersroppers.org/courseCTF.html) - A free course that teaches beginners the basics of forensics, crypto, and web-ex.
* [IppSec](https://www.youtube.com/channel/UCa6eh7gCkpPo5XXUDfygQQA) - Video tutorials and walkthroughs of popular CTF platforms.
* [LiveOverFlow](https://www.youtube.com/channel/UClcE-kVhqyiHCcjYwcpfj9w) - Video tutorials on Exploitation.

## Wargames

*Always online CTFs*

* [ROP Wargames](https://github.com/xelenonz/game) ⭐ 28 | 🐛 0 | 🌐 CSS | 📅 2017-09-11 - ROP Wargames.
* [Gracker](https://github.com/Samuirai/gracker) ⭐ 13 | 🐛 0 | 🌐 Groovy | 📅 2011-11-16 - Binary challenges having a slow learning curve, and write-ups for each level.
* [Backdoor](https://backdoor.sdslabs.co/) - Security Platform by SDSLabs.
* [Crackmes](https://crackmes.one/) - Reverse Engineering Challenges.
* [CryptoHack](https://cryptohack.org/) - Fun cryptography challenges.
* [echoCTF.RED](https://echoctf.red/) - Online CTF with a variety of targets to attack.
* [Exploit Exercises](https://exploit-exercises.lains.space/) - Variety of VMs to learn variety of computer security issues.
* [Exploit.Education](http://exploit.education) - Variety of VMs to learn variety of computer security issues.
* [Hack The Box](https://www.hackthebox.eu) - Weekly CTFs for all types of security enthusiasts.
* [Hack This Site](https://www.hackthissite.org/) - Training ground for hackers.
* [Hacker101](https://www.hacker101.com/) - CTF from HackerOne
* [Hacking-Lab](https://hacking-lab.com/) - Ethical hacking, computer network and security challenge platform.
* [Hone Your Ninja Skills](https://honeyourskills.ninja/) - Web challenges starting from basic ones.
* [IO](http://io.netgarage.org/) - Wargame for binary challenges.
* [Microcorruption](https://microcorruption.com) - Embedded security CTF.
* [Over The Wire](http://overthewire.org/wargames/) - Wargame maintained by OvertheWire Community.
* [PentesterLab](https://pentesterlab.com/) - Variety of VM and online challenges (paid).
* [PicoCTF](https://2019game.picoctf.com) - All year round ctf game. Questions from the yearly picoCTF competition.
* [PWN Challenge](http://pwn.eonew.cn/) - Binary Exploitation Wargame.
* [Pwnable.kr](http://pwnable.kr/) - Pwn Game.
* [Pwnable.tw](https://pwnable.tw/) - Binary wargame.
* [Pwnable.xyz](https://pwnable.xyz/) - Binary Exploitation Wargame.
* [Reversin.kr](http://reversing.kr/) - Reversing challenge.
* [Ringzer0Team](https://ringzer0team.com/) - Ringzer0 Team Online CTF.
* [Root-Me](https://www.root-me.org/) - Hacking and Information Security learning platform.
* [SANS HHC](https://holidayhackchallenge.com/past-challenges/) - Challenges with a holiday theme
  released annually and maintained by SANS.
* [SmashTheStack](http://smashthestack.org/) - A variety of wargames maintained by the SmashTheStack Community.
* [Viblo CTF](https://ctf.viblo.asia) - Various amazing CTF challenges, in many different categories. Has both Practice mode and Contest mode.
* [VulnHub](https://www.vulnhub.com/) - VM-based for practical in digital security, computer application & network administration.
* [W3Challs](https://w3challs.com) - A penetration testing training platform, which offers various computer challenges, in various categories.
* [WebHacking](http://webhacking.kr) - Hacking challenges for web.

*Self-hosted CTFs*

* [Juice Shop CTF](https://github.com/bkimminich/juice-shop-ctf) ⭐ 476 | 🐛 6 | 🌐 TypeScript | 📅 2026-04-16 - Scripts and tools for hosting a CTF on [OWASP Juice Shop](https://www.owasp.org/index.php/OWASP_Juice_Shop_Project) easily.
* [Damn Vulnerable Web Application](http://www.dvwa.co.uk/) - PHP/MySQL web application that is damn vulnerable.

## Websites

*Various general websites about and on CTF*

* [Awesome CTF Cheatsheet](https://github.com/uppusaikiran/awesome-ctf-cheatsheet#awesome-ctf-cheatsheet-) ⭐ 140 | 🐛 0 | 📅 2025-04-29 - CTF Cheatsheet.
* [CTF Time](https://ctftime.org/) - General information on CTF occuring around the worlds.
* [Reddit Security CTF](http://www.reddit.com/r/securityctf) - Reddit CTF category.

## Wikis

*Various Wikis available for learning about CTFs*

* [ISIS Lab](https://github.com/isislab/Project-Ideas/wiki) ⭐ 384 | 🐛 64 | 📅 2013-06-28 - CTF Wiki by Isis lab.
* [OpenToAll](https://github.com/OpenToAllCTF/Tips) ⭐ 153 | 🐛 1 | 📅 2019-10-05 - CTF tips by OTA CTF team members.
* [Bamboofox](https://bamboofox.github.io/) - Chinese resources to learn CTF.
* [bi0s Wiki](https://teambi0s.gitlab.io/bi0s-wiki/) - Wiki from team bi0s.
* [CTF Cheatsheet](https://uppusaikiran.github.io/hacking/Capture-the-Flag-CheatSheet/) - CTF tips and tricks.

## Writeups Collections

*Collections of CTF write-ups*

* [pwntools writeups](https://github.com/Gallopsled/pwntools-write-ups) ⭐ 528 | 🐛 14 | 🌐 Python | 📅 2016-10-05 - A collection of CTF write-ups all using pwntools.
* [HackThisSite](https://github.com/HackThisSite/CTF-Writeups) ⭐ 263 | 🐛 0 | 🌐 Python | 📅 2021-05-21 - CTF write-ups repo maintained by HackThisSite team.
* [Smoke Leet Everyday](https://github.com/smokeleeteveryday/CTF_WRITEUPS) ⭐ 192 | 🐛 0 | 🌐 Python | 📅 2017-10-08 - CTF write-ups repo maintained by SmokeLeetEveryday team.
* [Mzfr](https://github.com/mzfr/ctf-writeups/) ⭐ 124 | 🐛 0 | 🌐 Python | 📅 2022-07-13 - CTF competition write-ups by mzfr
* [0e85dc6eaf](https://github.com/0e85dc6eaf/CTF-Writeups) ⭐ 105 | 🐛 0 | 🌐 C | 📅 2020-02-25 - Write-ups for CTF challenges by 0e85dc6eaf
* [CTFTime Scrapper](https://github.com/abdilahrf/CTFWriteupScrapper) ⭐ 39 | 🐛 0 | 🌐 Python | 📅 2017-04-15 - Scraps all writeup from CTF Time and organize which to read first.
* [SababaSec](https://github.com/SababaSec/ctf-writeups) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2026-04-17 - A collection of CTF write-ups by the SababaSec team
* [Captf](http://captf.com/) - Dumped CTF challenges and materials by psifertex.
* [CTF write-ups (community)](https://github.com/ctfs/) - CTF challenges + write-ups archive maintained by the community.
* [Shell Storm](http://shell-storm.org/repo/CTF/) - CTF challenge archive maintained by Jonathan Salwan.

### LICENSE

CC0 :)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-01._
