# 🛰️ INTRATABLE // ARSENAL OFENSIVO Y SEGURIDAD OPERATIVA
> **Base de Conocimiento y Módulos Tácticos Clasificados**  
> *Operador:* **intratable** | *Especialidad:* Red Team / DevSecOps / Offensive Automation

---

## 🗂️ ÍNDICE MODULAR
- [⚡ MÓDULO 01: C2 FRAMEWORKS & POST-EXPLOTACIÓN](#-mdulo-01-c2-frameworks--post-explotacin) `(110 herramientas)`
- [🛡️ MÓDULO 02: MALDEV, EVASIÓN EDR/AV & INYECCIÓN](#-mdulo-02-maldev-evasin-edrav--inyeccin) `(45 herramientas)`
- [🇨🇳 MÓDULO 03: ECOSISTEMA OFENSIVO CHINO & AUTOMATIZACIÓN](#-mdulo-03-ecosistema-ofensivo-chino--automatizacin) `(11 herramientas)`
- [🏛️ MÓDULO 04: ACTIVE DIRECTORY, LATERAL MOVEMENT & PIVOTING](#-mdulo-04-active-directory-lateral-movement--pivoting) `(13 herramientas)`
- [🛰️ MÓDULO 05: RECONOCIMIENTO MASIVO, OSINT & BUG BOUNTY](#-mdulo-05-reconocimiento-masivo-osint--bug-bounty) `(47 herramientas)`
- [⚙️ MÓDULO 06: DEVSECOPS, SAST/DAST & SEGURIDAD EN CÓDIGO](#-mdulo-06-devsecops-sastdast--seguridad-en-cdigo) `(13 herramientas)`
- [🐬 MÓDULO 07: HARDWARE HACKING, RF & FLIPPER ZERO](#-mdulo-07-hardware-hacking-rf--flipper-zero) `(13 herramientas)`
- [📜 MÓDULO 08: EXPLOITS CVE, CHEATSHEETS & CERTIFICACIONES](#-mdulo-08-exploits-cve-cheatsheets--certificaciones) `(17 herramientas)`
- [🔬 MÓDULO 09: ANÁLISIS FORENSE (DFIR) & REVERSE ENGINEERING](#-mdulo-09-anlisis-forense-dfir--reverse-engineering) `(14 herramientas)`
- [📦 MÓDULO 10: UTILIDADES Y HERRAMIENTAS DIVERSAS](#-mdulo-10-utilidades-y-herramientas-diversas) `(119 herramientas)`

---

## ⚡ MÓDULO 01: C2 FRAMEWORKS & POST-EXPLOTACIÓN
> Sistemas de Comando y Control (C2), agentes remotos, stagers y post-explotación.

| Repositorio | Descripción | Stars | Lenguaje |
| :--- | :--- | :---: | :---: |
| [Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | AutoGPT is the vision of accessible AI for everyone, to use and to build on. Our mission is to provide the tools, so that you can focus on what matters. | ⭐ `187607` | `Python` |
| [swisskyrepo/PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) | A list of useful payloads and bypass for Web Application Security and Pentest/CTF | ⭐ `81331` | `Python` |
| [aquasecurity/trivy](https://github.com/aquasecurity/trivy) | Find vulnerabilities, misconfigurations, secrets, SBOM in containers, Kubernetes, code repositories, clouds and more | ⭐ `38132` | `Go` |
| [projectdiscovery/nuclei](https://github.com/projectdiscovery/nuclei) | Nuclei is a fast, customizable vulnerability scanner powered by the global security community and built on a simple YAML-based DSL, enabling collaboration to tackle trending vulnerabilities on the internet. It helps you find vulnerabilities in your applications, APIs, networks, DNS, and cloud configurations. | ⭐ `31622` | `Go` |
| [projectdiscovery/katana](https://github.com/projectdiscovery/katana) | A next-generation crawling and spidering framework. | ⭐ `17594` | `Go` |
| [owasp-amass/amass](https://github.com/owasp-amass/amass) | In-depth attack surface mapping and asset discovery | ⭐ `15240` | `Go` |
| [maurosoria/dirsearch](https://github.com/maurosoria/dirsearch) | Web path scanner | ⭐ `14770` | `Python` |
| [projectdiscovery/subfinder](https://github.com/projectdiscovery/subfinder) | Fast passive subdomain enumeration tool. | ⭐ `14520` | `Go` |
| [qazbnm456/awesome-web-security](https://github.com/qazbnm456/awesome-web-security) | ­ƒÉÂ A curated list of Web Security materials and resources. | ⭐ `13833` | `Python` |
| [SawyerHood/draw-a-ui](https://github.com/SawyerHood/draw-a-ui) | Draw a mockup and generate html for it | ⭐ `13584` | `TypeScript` |
| [BishopFox/sliver](https://github.com/BishopFox/sliver) | Adversary Emulation Framework | ⭐ `11927` | `Go` |
| [aboul3la/Sublist3r](https://github.com/aboul3la/Sublist3r) | Fast subdomains enumeration tool for penetration testers | ⭐ `11047` | `Python` |
| [samratashok/nishang](https://github.com/samratashok/nishang) | Nishang - Offensive PowerShell for red team, penetration testing and offensive security. | ⭐ `10127` | `PowerShell` |
| [wireshark/wireshark](https://github.com/wireshark/wireshark) | Read-only mirror of Wireshark's Git repository at https://gitlab.com/wireshark/wireshark. You're welcome to submit pull requests there. | ⭐ `9943` | `C` |
| [bridgecrewio/checkov](https://github.com/bridgecrewio/checkov) | Prevent cloud misconfigurations and find vulnerabilities during build-time in infrastructure as code, container images and open source packages with Checkov by Bridgecrew. | ⭐ `9043` | `Python` |
| [HavocFramework/Havoc](https://github.com/HavocFramework/Havoc) | The Havoc Framework | ⭐ `8514` | `Go` |
| [EmpireProject/Empire](https://github.com/EmpireProject/Empire) | Empire is a PowerShell and Python post-exploitation agent. | ⭐ `7857` | `PowerShell` |
| [projectdiscovery/naabu](https://github.com/projectdiscovery/naabu) | A fast port scanner written in go with a focus on reliability and simplicity. Designed to be used in combination with other tools for attack surface discovery in bug bounties and pentests | ⭐ `6271` | `Go` |
| [DefectDojo/django-DefectDojo](https://github.com/DefectDojo/django-DefectDojo) | Open-Source Unified Vulnerability Management, DevSecOps & ASPM | ⭐ `4968` | `Python` |
| [bitsadmin/wesng](https://github.com/bitsadmin/wesng) | Windows Exploit Suggester - Next Generation | ⭐ `4943` | `Python` |
| [its-a-feature/Mythic](https://github.com/its-a-feature/Mythic) | A collaborative, multi-platform, red teaming framework | ⭐ `4798` | `JavaScript` |
| [TheWover/donut](https://github.com/TheWover/donut) | Generates x86, x64, or AMD64+x86 position-independent shellcode that loads .NET Assemblies, PE files, and other Windows payloads from memory and runs them with parameters | ⭐ `4714` | `C` |
| [jonaslejon/malicious-pdf](https://github.com/jonaslejon/malicious-pdf) | ­ƒÆÇ Generate malicious PDF test files for testing phone-home callbacks, SSRF, XSS, NTLM credential theft, and data exfiltration in PDF viewers, converters, and web applications. Can be used with Burp Collaborator or Interact.sh | ⭐ `4442` | `Python` |
| [guelfoweb/knockpy](https://github.com/guelfoweb/knockpy) | Knock Subdomain Scan | ⭐ `4201` | `Python` |
| [0xsyr0/OSCP](https://github.com/0xsyr0/OSCP) | OSCP Cheat Sheet | ⭐ `3853` | `PowerShell` |
| [codingo/NoSQLMap](https://github.com/codingo/NoSQLMap) | Automated NoSQL database enumeration and web application exploitation tool. | ⭐ `3360` | `Python` |
| [sleuthkit/sleuthkit](https://github.com/sleuthkit/sleuthkit) | The Sleuth Kit┬« (TSK) is a library and collection of command line digital forensics tools that allow you to investigate volume and file system data. The library can be incorporated into larger digital forensics tools and the command line tools can be directly used to find evidence. | ⭐ `3157` | `C` |
| [pwndoc/pwndoc](https://github.com/pwndoc/pwndoc) | Pentest Report Generator | ⭐ `2898` | `JavaScript` |
| [Idov31/Nidhogg](https://github.com/Idov31/Nidhogg) | Windows rootkit for Intel x64 with 25+ features, demonstrating rootkit techniques compatible with all Windows 10 and Windows 11 versions. | ⭐ `2489` | `C++` |
| [d3mondev/puredns](https://github.com/d3mondev/puredns) | Puredns is a fast domain resolver and subdomain bruteforcing tool that can accurately filter out wildcard subdomains and DNS poisoned entries. | ⭐ `2244` | `Go` |
| [bats3c/shad0w](https://github.com/bats3c/shad0w) | A post exploitation framework designed to operate covertly on heavily monitored environments | ⭐ `2176` | `C` |
| [greshake/llm-security](https://github.com/greshake/llm-security) | New ways of breaking app-integrated LLMs | ⭐ `2144` | `Jupyter Notebook` |
| [last-byte/PersistenceSniper](https://github.com/last-byte/PersistenceSniper) | Powershell module that can be used by Blue Teams, Incident Responders and System Administrators to hunt persistences implanted in Windows machines. Official Twitter/X account @PersistSniper. Made with ÔØñ´©Å by @last0x00 and @dottor_morte | ⭐ `2142` | `PowerShell` |
| [shivaya-dav/DogeRat](https://github.com/shivaya-dav/DogeRat) | A multifunctional Telegram based Android RAT without port forwarding. | ⭐ `2041` | `N/A` |
| [r00t-3xp10it/venom](https://github.com/r00t-3xp10it/venom) | venom - C2 shellcode generator/compiler/handler | ⭐ `1963` | `Shell` |
| [0xPugal/One-Liners](https://github.com/0xPugal/One-Liners) | A collection of one-liners for bug bounty hunting. | ⭐ `1629` | `N/A` |
| [sweetsoftware/Ares](https://github.com/sweetsoftware/Ares) | Python botnet and backdoor | ⭐ `1625` | `Python` |
| [moom825/xeno-rat](https://github.com/moom825/xeno-rat) | Xeno-RAT is an open-source remote access tool (RAT) developed in C#, providing a comprehensive set of features for remote system management. Has features such as HVNC, live microphone, reverse proxy, and much much more! | ⭐ `1573` | `C#` |
| [s0md3v/Corsy](https://github.com/s0md3v/Corsy) | CORS Misconfiguration Scanner | ⭐ `1540` | `Python` |
| [outflanknl/C2-Tool-Collection](https://github.com/outflanknl/C2-Tool-Collection) | A collection of tools which integrate with Cobalt Strike (and possibly other C2 frameworks) through BOF and reflective DLL loading techniques. | ⭐ `1418` | `C` |
| [RistBS/Awesome-RedTeam-Cheatsheet](https://github.com/RistBS/Awesome-RedTeam-Cheatsheet) | Red Team Cheatsheet in constant expansion. | ⭐ `1303` | `N/A` |
| [3xpl01tc0d3r/ProcessInjection](https://github.com/3xpl01tc0d3r/ProcessInjection) | This program is designed to demonstrate various process injection techniques | ⭐ `1266` | `C#` |
| [DeimosC2/DeimosC2](https://github.com/DeimosC2/DeimosC2) | DeimosC2 is a Golang command and control framework for post-exploitation. | ⭐ `1161` | `Vue` |
| [loseys/BlackMamba](https://github.com/loseys/BlackMamba) | C2/post-exploitation framework | ⭐ `1158` | `Python` |
| [rodolfomarianocy/OSCP-Tricks](https://github.com/rodolfomarianocy/OSCP-Tricks) | OSCP Preparation Guide - Courses, Tricks, Tutorials, Exercises, Machines | ⭐ `1103` | `N/A` |
| [iphelix/dnschef](https://github.com/iphelix/dnschef) | DNSChef - DNS proxy for Penetration Testers and Malware Analysts | ⭐ `1073` | `Python` |
| [R00tS3c/DDOS-RootSec](https://github.com/R00tS3c/DDOS-RootSec) | Explore RootSec's DDOS Archive, featuring top-tier scanners, powerful botnets (Mirai & QBot) and other variants, high-impact exploits, advanced methods, and efficient sniffers. Ideal for cybersecurity professionals and researchers. | ⭐ `1062` | `C` |
| [hash3liZer/SillyRAT](https://github.com/hash3liZer/SillyRAT) | A Python based RAT ­ƒÉÇ (Remote Access Trojan) for getting reverse shell ­ƒûÑ´©Å | ⭐ `944` | `Python` |
| [tuhin1729/Bug-Bounty-Methodology](https://github.com/tuhin1729/Bug-Bounty-Methodology) | These are my checklists which I use during my hunting. | ⭐ `939` | `HTML` |
| [ahmedkhlief/Ninja](https://github.com/ahmedkhlief/Ninja) | Open source C2 server created for stealth red team operations | ⭐ `840` | `PowerShell` |
| [AdrianVollmer/PowerHub](https://github.com/AdrianVollmer/PowerHub) | A post exploitation tool based on a web application, focusing on bypassing endpoint protection and application whitelisting | ⭐ `833` | `PowerShell` |
| [sensepost/godoh](https://github.com/sensepost/godoh) | ­ƒò│ godoh - A DNS-over-HTTPS C2 | ⭐ `808` | `Go` |
| [SpenserCai/DRat](https://github.com/SpenserCai/DRat) | ÕÄ╗õ©¡Õ┐âÕîûÞ┐£þ¿ïµÄºÕêÂÕÀÑÕàÀ´╝êDecentralized Remote Administration Tool´╝ë´╝îÚÇÜÞ┐çENSÕ«×þÄ░õ║åÚàìþ¢«µûçõ╗ÂÕêåÕÅæþÜäÕÄ╗õ©¡Õ┐âÕîû´╝îÚÇÜÞ┐çTelegramÕ«×þÄ░õ║åµ£ìÕèíþ½»þÜäÕÄ╗õ©¡Õ┐âÕîû | ⭐ `797` | `Go` |
| [b1tg/CVE-2023-38831-winrar-exploit](https://github.com/b1tg/CVE-2023-38831-winrar-exploit) | CVE-2023-38831 winrar exploit generator | ⭐ `784` | `Python` |
| [SaturnsVoid/GoBot2](https://github.com/SaturnsVoid/GoBot2) | Second Version of The GoBot Botnet, But more advanced. | ⭐ `756` | `Go` |
| [blackarrowsec/pivotnacci](https://github.com/blackarrowsec/pivotnacci) | A tool to make socks connections through HTTP agents | ⭐ `726` | `Python` |
| [b23r0/Heroinn](https://github.com/b23r0/Heroinn) | A cross platform C2/post-exploitation framework. | ⭐ `709` | `Rust` |
| [3ct0s/dystopia-c2](https://github.com/3ct0s/dystopia-c2) | Windows Remote Administration Tool that uses Discord, Telegram and GitHub as C2s | ⭐ `699` | `Python` |
| [threatexpress/random_c2_profile](https://github.com/threatexpress/random_c2_profile) | Cobalt Strike random C2 Profile generator | ⭐ `690` | `Python` |
| [MindPatch/scant3r](https://github.com/MindPatch/scant3r) | ScanT3r - Module based Bug Bounty Automation Tool ( use Lotus instead github.com/bugBlocker/lotus ) | ⭐ `684` | `Rust` |
| [Tomiwa-Ot/moukthar](https://github.com/Tomiwa-Ot/moukthar) | Android remote administration tool | ⭐ `681` | `PHP` |
| [eslam3kl/SQLiDetector](https://github.com/eslam3kl/SQLiDetector) | Simple python script supported with BurpBouty profile that helps you to detect SQL injection "Error based" by sending multiple requests with 14 payloads and checking for 152 regex patterns for different databases. | ⭐ `644` | `Clojure` |
| [gl4ssesbo1/Nebula](https://github.com/gl4ssesbo1/Nebula) | Nebula is a cloud C2 Framework, which at the moment offers reconnaissance, enumeration, exploitation, post exploitation on AWS, but still working to allow testing other Cloud Providers and DevOps Components. | ⭐ `634` | `Python` |
| [immunIT/drupwn](https://github.com/immunIT/drupwn) | Drupal enumeration & exploitation tool | ⭐ `616` | `Python` |
| [PushpenderIndia/thorse](https://github.com/PushpenderIndia/thorse) | THorse is a RAT (Remote Administrator Trojan) Generator for Windows/Linux systems written in Python 3. | ⭐ `614` | `Python` |
| [p3nt4/Nuages](https://github.com/p3nt4/Nuages) | A modular C2 framework | ⭐ `546` | `JavaScript` |
| [Getshell/C2](https://github.com/Getshell/C2) | C2-õ©ïõ©Çõ╗úRAT | ⭐ `535` | `N/A` |
| [D3Ext/Hooka](https://github.com/D3Ext/Hooka) | Shellcode loader generator with multiples features | ⭐ `509` | `Go` |
| [RedTeamPentesting/monsoon](https://github.com/RedTeamPentesting/monsoon) | Fast HTTP enumerator | ⭐ `500` | `Go` |
| [enkomio/AlanFramework](https://github.com/enkomio/AlanFramework) | A C2 post-exploitation framework | ⭐ `484` | `Assembly` |
| [machine1337/TelegramRAT](https://github.com/machine1337/TelegramRAT) | Cross Platform Telegram based RAT that communicates via telegram to evade network restrictions | ⭐ `452` | `Python` |
| [BC-SECURITY/Malleable-C2-Profiles](https://github.com/BC-SECURITY/Malleable-C2-Profiles) | Malleable C2 Profiles. A collection of profiles used in different projects using Cobalt Strike & Empire. | ⭐ `412` | `N/A` |
| [cornerpirate/JS2PDFInjector](https://github.com/cornerpirate/JS2PDFInjector) | Inject a JS file into a PDF file. | ⭐ `388` | `Java` |
| [noperator/CVE-2019-18935](https://github.com/noperator/CVE-2019-18935) | RCE exploit for a .NET JSON deserialization vulnerability in Telerik UI for ASP.NET AJAX. | ⭐ `374` | `Python` |
| [morpheuslord/QuadraInspect](https://github.com/morpheuslord/QuadraInspect) | QuadraInspect is an Android framework that integrates AndroPass, APKUtil, and MobFS, providing a powerful tool for analyzing the security of Android applications. | ⭐ `353` | `Python` |
| [JFR-C/Windows-Penetration-Testing](https://github.com/JFR-C/Windows-Penetration-Testing) | Technical notes, AD pentest methodology, list of tools, scripts and Windows commands that are useful for internal penetration tests and assumed breach exercises (red teaming). | ⭐ `329` | `C` |
| [marco-liberale/PasteBomb](https://github.com/marco-liberale/PasteBomb) | PasteBomb C2-less RAT | ⭐ `323` | `Go` |
| [Phype/telnet-iot-honeypot](https://github.com/Phype/telnet-iot-honeypot) | Python telnet honeypot for catching botnet binaries | ⭐ `313` | `Python` |
| [Anteste/WebMap](https://github.com/Anteste/WebMap) | A Python tool used to automate the execution of the following tools : Nmap , Nikto and Dirsearch but also to automate the report generation during a Web Penetration Testing | ⭐ `295` | `Python` |
| [onionj/pyremote](https://github.com/onionj/pyremote) | PyRemote: A Remote Control Framework for Python with Telegram Integration | ⭐ `266` | `Python` |
| [luke-goddard/enumy](https://github.com/luke-goddard/enumy) | Linux post exploitation privilege escalation enumeration | ⭐ `256` | `C` |
| [Ziconius/FudgeC2](https://github.com/Ziconius/FudgeC2) | FudgeC2 - a command and control framework designed for team collaboration and post-exploitation activities. | ⭐ `253` | `Python` |
| [edoardottt/favirecon](https://github.com/edoardottt/favirecon) | Use favicons to improve your target recon phase. Quickly detect technologies, WAF, exposed panels, known services. | ⭐ `250` | `Go` |
| [Nahuel61920/50-Proyectos-en-50-dias](https://github.com/Nahuel61920/50-Proyectos-en-50-dias) | This is a personal challenge to create a mini html-css-javascript project, for 50 days in a row. | ⭐ `227` | `JavaScript` |
| [Enelg52/KittyStager](https://github.com/Enelg52/KittyStager) | KittyStager is a simple stage 0 C2. It is made of a web server to host the shellcode and an implant, called kitten. The purpose of this project is to be able to have a web server and some kitten and be able to use the with any shellcode. | ⭐ `226` | `Go` |
| [D00Movenok/HTMLSmuggler](https://github.com/D00Movenok/HTMLSmuggler) | Ô£ë´©Å HTML Smuggling generator&obfuscator for your Red Team operations | ⭐ `203` | `JavaScript` |
| [farhan3/py-botnet](https://github.com/farhan3/py-botnet) | Educational botnet program to perform a DDoS attack | ⭐ `187` | `Python` |
| [CosmodiumCS/MK01-OnlyRAT](https://github.com/CosmodiumCS/MK01-OnlyRAT) | OnlyRAT is the only RAT you'll ever need. We will be able to use this tool to remotely command and control windows computers.Once installed we will have remote administrative access to our target that we can connect to through Python console on our attacker pc. The onlyrat console has plenty of payloads we can then use on our target. | ⭐ `177` | `Python` |
| [Dump-GUY/EXE-or-DLL-or-ShellCode](https://github.com/Dump-GUY/EXE-or-DLL-or-ShellCode) | Just a simple silly PoC demonstrating executable "exe" file that can be used like exe, dll or shellcode... | ⭐ `168` | `C` |
| [Pericena/Droidjack](https://github.com/Pericena/Droidjack) | Educational Android RAT - Authorized use only in controlled environments. | ⭐ `147` | `Smali` |
| [machine1337/pyFUD](https://github.com/machine1337/pyFUD) | CROSS PLATFORM REMOTE ACCESS TROJAN (RAT) | ⭐ `121` | `Python` |
| [ignis-sec/CVE-2023-38831-RaRCE](https://github.com/ignis-sec/CVE-2023-38831-RaRCE) | An easy to install and easy to run tool for generating exploit payloads for CVE-2023-38831, WinRAR RCE before versions 6.23 | ⭐ `113` | `Python` |
| [1d8/teleRAT](https://github.com/1d8/teleRAT) | Telegram RAT written in Python | ⭐ `110` | `Python` |
| [jg-fisher/botnet](https://github.com/jg-fisher/botnet) | Simple implementation of a distributed SSH system, or botnet. Add bots to the botnet with IP address, host username, and host password. Issue terminal commands to command all bots. | ⭐ `100` | `Python` |
| [dwisiswant0/ipfuscator](https://github.com/dwisiswant0/ipfuscator) | A blazing-fast, thread-safe, straightforward and zero memory allocations tool to swiftly generate alternative IP(v4) address representations in Go. | ⭐ `94` | `Go` |
| [TarlogicSecurity/Arecibo](https://github.com/TarlogicSecurity/Arecibo) | Endpoint for Out-of-Band Exfiltration (DNS & HTTP) | ⭐ `94` | `Python` |
| [codingplanets/ZBOT-Botnet](https://github.com/codingplanets/ZBOT-Botnet) | IRC based botnet developed in C | ⭐ `43` | `C` |
| [G0uth4m/SSH-botnet](https://github.com/G0uth4m/SSH-botnet) | A python tool(automation) for automatically finding SSH servers on the network and adding them to the botnet for mass administration and control. | ⭐ `40` | `Python` |
| [kensh1ro/NimTeleBackdoor](https://github.com/kensh1ro/NimTeleBackdoor) | a simple backdoor in Nim | ⭐ `19` | `Nim` |
| [timebotdon/telegram-c2agent](https://github.com/timebotdon/telegram-c2agent) | POC Telegram C2 agent in NodeJS | ⭐ `17` | `JavaScript` |
| [n0a/mac-address-changer](https://github.com/n0a/mac-address-changer) | Linux/macOS random/vendor MAC-address changer. | ⭐ `16` | `Python` |
| [maapol/hellcat](https://github.com/maapol/hellcat) | A windows backdoor that's use Telegram as a C2 server. | ⭐ `15` | `Go` |
| [idfp/go-stealer](https://github.com/idfp/go-stealer) | Cookie & Logins stealer for Firefox + Chrome, demonstration only | ⭐ `12` | `Go` |
| [MoJoMoon/Deep-Learning-for-Diversity-Inclusion-in-Media](https://github.com/MoJoMoon/Deep-Learning-for-Diversity-Inclusion-in-Media) | Use StyleGAN2 & First Order Motion Model to Generate and Animate faces with Deep Learning for hypothetical use case of the Netflix Platform. | ⭐ `6` | `Jupyter Notebook` |
| [Lemonada/teleBrat](https://github.com/Lemonada/teleBrat) | A simple rat written fully in go using telegram as a C2 | ⭐ `6` | `Go` |
| [taring1337/C2](https://github.com/taring1337/C2) | Botnet C2 | ⭐ `3` | `JavaScript` |
| [G0uth4m/Wordlist-Generator](https://github.com/G0uth4m/Wordlist-Generator) | Simple python3 script to create wordlists for cracking passwords. | ⭐ `3` | `Python` |
| [intratable/OSCP-Tricks-2023](https://github.com/intratable/OSCP-Tricks-2023) | OSCP 2023 Preparation Guide - Courses, Tricks, Tutorials, Exercises, Machines | ⭐ `2` | `N/A` |
| [kraibse/hornet-swarm](https://github.com/kraibse/hornet-swarm) | Originally developed as a school project. Included is a program used to remotely execute scripts and commands. | ⭐ `2` | `HTML` |
| [intratable/PayloadsAllTheThings](https://github.com/intratable/PayloadsAllTheThings) | A list of useful payloads and bypass for Web Application Security and Pentest/CTF | ⭐ `1` | `N/A` |

---

## 🛡️ MÓDULO 02: MALDEV, EVASIÓN EDR/AV & INYECCIÓN
> Syscalls directos, evasión de telemetría/AMSI/ETW, unhooking, shellcodes y crypting.

| Repositorio | Descripción | Stars | Lenguaje |
| :--- | :--- | :---: | :---: |
| [sqlmapproject/sqlmap](https://github.com/sqlmapproject/sqlmap) | Automatic SQL injection and database takeover tool | ⭐ `38553` | `Python` |
| [MatrixTM/MHDDoS](https://github.com/MatrixTM/MHDDoS) | Best DDoS Attack Script  Python3, (Cyber / DDos) Attack With 56 Methods | ⭐ `16765` | `Python` |
| [ayoubfaouzi/al-khaser](https://github.com/ayoubfaouzi/al-khaser) | Public malware techniques used in the wild: Virtual Machine, Emulation, Debuggers, Sandbox detection. | ⭐ `7138` | `C++` |
| [commixproject/commix](https://github.com/commixproject/commix) | Automated ╬æll-in-One OS command injection exploitation tool. | ⭐ `5863` | `Python` |
| [optiv/ScareCrow](https://github.com/optiv/ScareCrow) | ScareCrow - Payload creation framework designed around EDR bypass. | ⭐ `2886` | `Go` |
| [j00ru/windows-syscalls](https://github.com/j00ru/windows-syscalls) | Windows System Call Tables (NT/2000/XP/2003/Vista/7/8/10/11) | ⭐ `2650` | `HTML` |
| [matterpreter/DefenderCheck](https://github.com/matterpreter/DefenderCheck) | Identifies the bytes that Microsoft Defender flags on. | ⭐ `2633` | `C#` |
| [iamj0ker/bypass-403](https://github.com/iamj0ker/bypass-403) | A simple script just made for self use for bypassing 403 | ⭐ `2264` | `Shell` |
| [Mr-Un1k0d3r/EDRs](https://github.com/Mr-Un1k0d3r/EDRs) | Sin descripción | ⭐ `2207` | `C` |
| [phra/PEzor](https://github.com/phra/PEzor) | Open-Source Shellcode & PE Packer | ⭐ `2135` | `C` |
| [jthuraisamy/SysWhispers](https://github.com/jthuraisamy/SysWhispers) | AV/EDR evasion via direct system calls. | ⭐ `2028` | `Assembly` |
| [sarperavci/GoogleRecaptchaBypass](https://github.com/sarperavci/GoogleRecaptchaBypass) | Solve Google reCAPTCHA in less than 5 seconds! ­ƒÜÇ | ⭐ `1883` | `Python` |
| [swisskyrepo/GraphQLmap](https://github.com/swisskyrepo/GraphQLmap) | GraphQLmap is a scripting engine to interact with a graphql endpoint for pentesting purposes. - Do not use for illegal testing ;) | ⭐ `1691` | `Python` |
| [Xacone/BestEdrOfTheMarket](https://github.com/Xacone/BestEdrOfTheMarket) | EDR Lab for Experimentation Purposes | ⭐ `1565` | `C++` |
| [optiv/Freeze](https://github.com/optiv/Freeze) | Freeze is a payload toolkit for bypassing EDRs using suspended processes, direct syscalls, and alternative execution methods | ⭐ `1475` | `Go` |
| [the-robot/sqliv](https://github.com/the-robot/sqliv) | massive SQL injection vulnerability scanner | ⭐ `1232` | `Python` |
| [Ne0nd0g/go-shellcode](https://github.com/Ne0nd0g/go-shellcode) | A repository of Windows Shellcode runners and supporting utilities. The applications load and execute Shellcode using various API calls or techniques. | ⭐ `1197` | `Go` |
| [utkusen/leviathan](https://github.com/utkusen/leviathan) | wide range mass audit toolkit | ⭐ `1041` | `Python` |
| [HyukIsBack/KARMA-DDoS](https://github.com/HyukIsBack/KARMA-DDoS) | DDoS Script (DDoS Panel) with Multiple Bypass ( Cloudflare UAM,CAPTCHA,BFM,NOSEC / DDoS Guard / Google Shield / V Shield / Amazon / etc.. ) | ⭐ `933` | `Python` |
| [arget13/DDexec](https://github.com/arget13/DDexec) | A technique to run binaries filelessly and stealthily on Linux by "overwriting" the shell's process with another. | ⭐ `898` | `Shell` |
| [Sh3lldon/FullBypass](https://github.com/Sh3lldon/FullBypass) | A tool which bypasses AMSI (AntiMalware Scan Interface) and PowerShell CLM (Constrained Language Mode) and gives you a FullLanguage PowerShell reverse shell. | ⭐ `820` | `C#` |
| [HackOvert/AntiDBG](https://github.com/HackOvert/AntiDBG) | A bunch of Windows anti-debugging tricks for x86 and x64. | ⭐ `814` | `C++` |
| [Unknow101/FuckThatPacker](https://github.com/Unknow101/FuckThatPacker) | A simple python packer to easily bypass Windows Defender | ⭐ `639` | `Python` |
| [FourCoreLabs/EDRHunt](https://github.com/FourCoreLabs/EDRHunt) | Scan installed EDRs and AVs on Windows | ⭐ `609` | `Go` |
| [WithSecureLabs/CallStackSpoofer](https://github.com/WithSecureLabs/CallStackSpoofer) | A PoC implementation for spoofing arbitrary call stacks when making sys calls (e.g. grabbing a handle via NtOpenProcess) | ⭐ `598` | `C++` |
| [janoglezcampos/DeathSleep](https://github.com/janoglezcampos/DeathSleep) | A PoC implementation for an evasion technique to terminate the current thread and restore it before resuming execution, while implementing page protection changes during no execution. | ⭐ `542` | `Python` |
| [sh4hin/GoPurple](https://github.com/sh4hin/GoPurple) | Yet another shellcode runner consists of different techniques for evaluating detection capabilities of endpoint security solutions | ⭐ `497` | `Go` |
| [plackyhacker/Shellcode-Encryptor](https://github.com/plackyhacker/Shellcode-Encryptor) | A simple shell code encryptor/decryptor/executor to bypass anti virus. | ⭐ `468` | `C#` |
| [Charlie-belmer/nosqli](https://github.com/Charlie-belmer/nosqli) | NoSql Injection CLI tool, for finding vulnerable websites using MongoDB. | ⭐ `416` | `Go` |
| [D3Ext/maldev](https://github.com/D3Ext/maldev) | Golang library for malware development | ⭐ `404` | `Go` |
| [Binject/go-donut](https://github.com/Binject/go-donut) | Donut Injector ported to pure Go.  For use with https://github.com/TheWover/donut | ⭐ `364` | `Go` |
| [PushpenderIndia/crypter](https://github.com/PushpenderIndia/crypter) | Crypter in Python 3 with advanced functionality, Bypass VM, Encrypt Source with AES & Base64 Encoding - Evil Code is executed by bruteforcing the decryption key, and then executing the decrypted evil code | ⭐ `351` | `Python` |
| [S1lkys/SharpKiller](https://github.com/S1lkys/SharpKiller) | Lifetime AMSI bypass by @ZeroMemoryEx ported to .NET Framework 4.8 | ⭐ `347` | `C#` |
| [mgeeky/UnhookMe](https://github.com/mgeeky/UnhookMe) | UnhookMe is an universal Windows API resolver & unhooker addressing problem of invoking unmonitored system calls from within of your Red Teams malware | ⭐ `347` | `C++` |
| [maximedrn/opensea-automatic-bulk-upload-and-sale](https://github.com/maximedrn/opensea-automatic-bulk-upload-and-sale) | A Selenium Python bot to automatically and bulk upload/ mint and list your NFTs on OpenSea. All metadata compatible, Ethereum and Polygon blockchains supported, reCAPTCHA solvers included. | ⭐ `329` | `Python` |
| [pracsec/AmsiBypassHookManagedAPI](https://github.com/pracsec/AmsiBypassHookManagedAPI) | A new AMSI Bypass technique using .NET ALI Call Hooking. | ⭐ `195` | `PowerShell` |
| [ph4nt0mbyt3/Darkside](https://github.com/ph4nt0mbyt3/Darkside) | C# AV/EDR Killer using less-known driver (BYOVD) | ⭐ `188` | `C#` |
| [abdulkadir-gungor/HtmlSmuggling](https://github.com/abdulkadir-gungor/HtmlSmuggling) | HTML smuggling is a malicious technique used by hackers to hide malware payloads in an encoded script in a specially crafted HTML attachment or web page. The malicious script decodes and deploys the payload on the targeted device when the victim opens/clicks the HTML attachment/link. The HTML smuggling technique leverages legitimate HTML5 and JavaScript features to hide malicious payloads and evade security detections. The HTML smuggling method is highly evasive. It could bypass standard perimeter security controls like web proxies and email gateways, which only check for suspicious attachments like EXE, DLL, ZIP, RAR, DOCX or PDF | ⭐ `154` | `Python` |
| [0NullBit0/NullTrace-Injector](https://github.com/0NullBit0/NullTrace-Injector) | Inject shared libraries into processes on Android (real/emulator device supported) | ⭐ `118` | `C++` |
| [ghostpepper108/Evasion](https://github.com/ghostpepper108/Evasion) | Sin descripción | ⭐ `106` | `C++` |
| [Helixo32/SimpleEDR](https://github.com/Helixo32/SimpleEDR) | Simple EDR that injects a DLL into a process to place a hook on specific Windows API | ⭐ `99` | `Nim` |
| [afwu/GoBypass](https://github.com/afwu/GoBypass) | GolangÕàìµØÇþöƒµêÉÕÀÑÕàÀ | ⭐ `86` | `N/A` |
| [awaitlol/Undetected-DLL-Injection-Method](https://github.com/awaitlol/Undetected-DLL-Injection-Method) | Undetected DLL Injection Method | ⭐ `34` | `C++` |
| [D3Ext/Nimbus](https://github.com/D3Ext/Nimbus) | Shellcode loader with evasion capabilities written in Nim | ⭐ `16` | `Nim` |
| [nobodyatall648/UAC_Bypass](https://github.com/nobodyatall648/UAC_Bypass) | Bypass Windows UAC Technique | ⭐ `9` | `PowerShell` |

---

## 🇨🇳 MÓDULO 03: ECOSISTEMA OFENSIVO CHINO & AUTOMATIZACIÓN
> Escáneres masivos de intranet en Go/Rust, herramientas de penetración rápida y PoCs automatizadas.

| Repositorio | Descripción | Stars | Lenguaje |
| :--- | :--- | :---: | :---: |
| [shadow1ng/fscan](https://github.com/shadow1ng/fscan) | õ©Çµ¼¥Õåàþ¢æþ╗╝ÕÉêµë½µÅÅÕÀÑÕàÀ´╝îµû╣õ¥┐õ©ÇÚö«Þç¬Õè¿ÕîûÒÇüÕà¿µû╣õ¢ìµ╝Åµë½µë½µÅÅÒÇé(An intranet comprehensive scanning tool, enabling one-click automated, all-round vulnerability scanning) | ⭐ `14600` | `Go` |
| [moonD4rk/HackBrowserData](https://github.com/moonD4rk/HackBrowserData) | Extract and decrypt browser data, supporting multiple data types, runnable on various operating systems (macOS, Windows, Linux). | ⭐ `14563` | `Go` |
| [shmilylty/OneForAll](https://github.com/shmilylty/OneForAll) | OneForAllµÿ»õ©Çµ¼¥ÕèƒÞâ¢Õ╝║ÕñºþÜäÕ¡ÉÕƒƒµöÂÚøåÕÀÑÕàÀ | ⭐ `10097` | `Python` |
| [yaklang/yakit](https://github.com/yaklang/yakit) | Cyber Security ALL-IN-ONE Platform | ⭐ `7776` | `TypeScript` |
| [k8gege/Ladon](https://github.com/k8gege/Ladon) | LadonÕñºÕ×ïÕåàþ¢æµ©ùÚÇÅµë½µÅÅÕÖ¿´╝îPowerShellÒÇüCobalt StrikeµÅÆõ╗ÂÒÇüÕåàÕ¡ÿÕèáÞ¢¢ÒÇüµùáµûçõ╗Âµë½µÅÅÒÇéÕÉ½þ½»ÕÅúµë½µÅÅÒÇüµ£ìÕèíÞ»åÕê½ÒÇüþ¢æþ╗£ÞÁäõ║ºµÄóµÁïÒÇüÕ»åþáüÕ«íÞ«íÒÇüÚ½ÿÕì▒µ╝Åµ┤×µúÇµÁïÒÇüµ╝Åµ┤×Õê®þö¿ÒÇüÕ»åþáüÞ»╗ÕÅûõ╗ÑÕÅèõ©ÇÚö«GetShell´╝îµö»µîüµë╣ÚçÅAµ«Á/Bµ«Á/Cµ«Áõ╗ÑÕÅèÞÀ¿þ¢æµ«Áµë½µÅÅ´╝îµö»µîüURLÒÇüõ©╗µ£║ÒÇüÕƒƒÕÉìÕêùÞí¿µë½µÅÅþ¡ëÒÇéþ¢æþ╗£ÞÁäõ║ºµÄóµÁï32þºìÕìÅÞ««(ICMP\NBT\DNS\MAC\SMB\WMI\SSH\HTTP\HTTPS\Exchange\mssql\FTP\RDP)µêûµû╣µ│òÕ┐½ÚÇƒÞÄÀÕÅûþø«µáçþ¢æþ╗£Õ¡ÿµ┤╗õ©╗µ£║IPÒÇüÞ«íþ«ùµ£║ÕÉìÒÇüÕÀÑõ¢£þ╗äÒÇüÕà▒õ║½ÞÁäµ║ÉÒÇüþ¢æÕìíÕ£░ÕØÇÒÇüµôìõ¢£þ│╗þ╗ƒþëêµ£¼ÒÇüþ¢æþ½ÖÒÇüÕ¡ÉÕƒƒÕÉìÒÇüõ©¡Úù┤õ╗ÂÒÇüÕ╝Çµö¥µ£ìÕèíÒÇüÞÀ»þö▒ÕÖ¿ÒÇüõ║ñµìóµ£║ÒÇüµò░µì«Õ║ôÒÇüµëôÕì░µ£║þ¡ë´╝îÕñºÚçÅÚ½ÿÕì▒µ╝Åµ┤×µúÇµÁïµ¿íÕØùMS17010ÒÇüZimbraÒÇüExchange | ⭐ `5330` | `C#` |
| [zan8in/afrog](https://github.com/zan8in/afrog) | A Security Tool for Bug Bounty, Pentest and Red Teaming. | ⭐ `4427` | `HTML` |
| [knownsec/shellcodeloader](https://github.com/knownsec/shellcodeloader) | shellcodeloader | ⭐ `1746` | `C++` |
| [chaitin/rad](https://github.com/chaitin/rad) | Sin descripción | ⭐ `1518` | `N/A` |
| [rootclay/WMIHACKER](https://github.com/rootclay/WMIHACKER) | A Bypass Anti-virus Software Lateral Movement Command Execution Tool | ⭐ `1463` | `VBScript` |
| [TideSec/GoBypassAV](https://github.com/TideSec/GoBypassAV) | µò┤þÉåõ║åÕƒ║õ║ÄGoþÜä16þºìAPIÕàìµØÇµÁïÞ»òÒÇü8þºìÕèáÕ»åµÁïÞ»òÒÇüÕÅìµ▓ÖþøÆµÁïÞ»òÒÇüþ╝ûÞ»æµÀÀµÀåÒÇüÕèáÕú│ÒÇüÞÁäµ║Éõ┐«µö╣þ¡ëÕàìµØÇµèÇµ£»´╝îÕ╣ÂµÉ£Úøåµ▒çµÇ╗õ║åõ©Çõ║øÞÁäµûÖÕÆîÕÀÑÕàÀÒÇé | ⭐ `1183` | `Go` |
| [safe6Sec/GolangBypassAV](https://github.com/safe6Sec/GolangBypassAV) | þáöþ®ÂÕê®þö¿golangÕÉäþºìÕº┐Õè┐bypassAV | ⭐ `814` | `Go` |

---

## 🏛️ MÓDULO 04: ACTIVE DIRECTORY, LATERAL MOVEMENT & PIVOTING
> Tácticas de identidad empresarial, Kerberos, dumping de credenciales, proxying y túneles.

| Repositorio | Descripción | Stars | Lenguaje |
| :--- | :--- | :---: | :---: |
| [gentilkiwi/mimikatz](https://github.com/gentilkiwi/mimikatz) | A little tool to play with Windows security | ⭐ `21878` | `C` |
| [fortra/impacket](https://github.com/fortra/impacket) | Impacket is a collection of Python classes for working with network protocols. | ⭐ `16135` | `Python` |
| [byt3bl33d3r/CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec) | A swiss army knife for pentesting networks | ⭐ `9163` | `Python` |
| [SpiderLabs/Responder](https://github.com/SpiderLabs/Responder) | Responder is a LLMNR, NBT-NS and MDNS poisoner, with built-in HTTP/SMB/MSSQL/FTP/LDAP rogue authentication server supporting NTLMv1/NTLMv2/LMv2, Extended Security NTLMSSP and Basic HTTP authentication. | ⭐ `4890` | `Python` |
| [SpecterOps/BloodHound](https://github.com/SpecterOps/BloodHound) | Six Degrees of Domain Admin | ⭐ `3447` | `Go` |
| [davidprowe/BadBlood](https://github.com/davidprowe/BadBlood) | BadBlood by @davidprowe, Secframe.com, fills a Microsoft Active Directory Domain with a structure and thousands of objects. The output of the tool is a domain similar to a domain in the real world.  After BadBlood is ran on a domain, security analysts and engineers can practice using tools to gain an understanding and prescribe to securing Active Directory. Each time this tool runs, it produces different results.  The domain, users, groups, computers and permissions are different. Every. Single. Time. | ⭐ `2270` | `PowerShell` |
| [antonioCoco/RunasCs](https://github.com/antonioCoco/RunasCs) | RunasCs - Csharp and open version of windows builtin runas.exe | ⭐ `1438` | `C#` |
| [GhostPack/SafetyKatz](https://github.com/GhostPack/SafetyKatz) | SafetyKatz is a combination of slightly modified version of @gentilkiwi's Mimikatz project and @subtee's .NET PE Loader | ⭐ `1333` | `C#` |
| [stanislav-web/OpenDoor](https://github.com/stanislav-web/OpenDoor) | OWASP Web Recon & Directory Discovery Platform | ⭐ `1008` | `Python` |
| [CiscoCXSecurity/creddump7](https://github.com/CiscoCXSecurity/creddump7) | Sin descripción | ⭐ `412` | `Python` |
| [C-Sto/gosecretsdump](https://github.com/C-Sto/gosecretsdump) | Dump ntds.dit really fast | ⭐ `407` | `Go` |
| [n00py/LAPSDumper](https://github.com/n00py/LAPSDumper) | Dumping LAPS from Python | ⭐ `289` | `Python` |
| [rvrsh3ll/Rubeus-Rundll32](https://github.com/rvrsh3ll/Rubeus-Rundll32) | Run Rubeus via Rundll32 | ⭐ `214` | `C#` |

---

## 🛰️ MÓDULO 05: RECONOCIMIENTO MASIVO, OSINT & BUG BOUNTY
> Mapeo de superficie de ataque externa, subdominios, fuzzing, scrapers y motores de plantillas.

| Repositorio | Descripción | Stars | Lenguaje |
| :--- | :--- | :---: | :---: |
| [sherlock-project/sherlock](https://github.com/sherlock-project/sherlock) | Hunt down social media accounts by username across social networks | ⭐ `93019` | `Python` |
| [qeeqbox/social-analyzer](https://github.com/qeeqbox/social-analyzer) | API, CLI, and Web App for analyzing and finding a person's profile in 1000 social media \ websites | ⭐ `24141` | `JavaScript` |
| [ffuf/ffuf](https://github.com/ffuf/ffuf) | Fast web fuzzer written in Go | ⭐ `16777` | `Go` |
| [s0md3v/Photon](https://github.com/s0md3v/Photon) | Incredibly fast crawler designed for OSINT. | ⭐ `13246` | `Python` |
| [projectdiscovery/httpx](https://github.com/projectdiscovery/httpx) | httpx is a fast and multi-purpose HTTP toolkit that allows running multiple probes using the retryablehttp library. | ⭐ `10436` | `Go` |
| [antoniaci/blackbird](https://github.com/antoniaci/blackbird) | An OSINT tool to search for accounts by username and email in social networks. | ⭐ `8738` | `Python` |
| [TheKingOfDuck/fuzzDicts](https://github.com/TheKingOfDuck/fuzzDicts) | You Know, For WEB Fuzzing ! | ⭐ `8449` | `Python` |
| [xmendez/wfuzz](https://github.com/xmendez/wfuzz) | Web application fuzzer | ⭐ `6587` | `Python` |
| [alpkeskin/mosint](https://github.com/alpkeskin/mosint) | An automated e-mail OSINT tool | ⭐ `6041` | `Go` |
| [EdOverflow/can-i-take-over-xyz](https://github.com/EdOverflow/can-i-take-over-xyz) | "Can I take over XYZ?" ÔÇö a list of services and how to claim (sub)domains with dangling DNS records. | ⭐ `5819` | `Python` |
| [hakluke/hakrawler](https://github.com/hakluke/hakrawler) | Simple, fast web crawler designed for easy, quick discovery of endpoints and assets within a web application | ⭐ `5138` | `Go` |
| [lc/gau](https://github.com/lc/gau) | Fetch known URLs from AlienVault's Open Threat Exchange, the Wayback Machine, and Common Crawl. | ⭐ `5106` | `Go` |
| [tomnomnom/waybackurls](https://github.com/tomnomnom/waybackurls) | Fetch all the URLs that the Wayback Machine knows about for a domain | ⭐ `4563` | `Go` |
| [opsdisk/pagodo](https://github.com/opsdisk/pagodo) | pagodo (Passive Google Dork) - Automate Google Hacking Database scraping and searching | ⭐ `3401` | `Python` |
| [dwisiswant0/awesome-oneliner-bugbounty](https://github.com/dwisiswant0/awesome-oneliner-bugbounty) | A collection of awesome one-liner scripts especially for bug bounty tips. | ⭐ `3195` | `N/A` |
| [devanshbatham/ParamSpider](https://github.com/devanshbatham/ParamSpider) | Mining URLs from dark corners of Web Archives for bug hunting/fuzzing/further probing | ⭐ `3182` | `Python` |
| [cipher387/Dorks-collections-list](https://github.com/cipher387/Dorks-collections-list) | List of Github repositories and articles with list of dorks for different search engines | ⭐ `2755` | `N/A` |
| [cipher387/API-s-for-OSINT](https://github.com/cipher387/API-s-for-OSINT) | List of API's for gathering information about phone numbers, addresses, domains etc | ⭐ `2559` | `N/A` |
| [kpcyrd/sn0int](https://github.com/kpcyrd/sn0int) | Semi-automatic OSINT framework and package manager | ⭐ `2548` | `Rust` |
| [The-Osint-Toolbox/Telegram-OSINT](https://github.com/The-Osint-Toolbox/Telegram-OSINT) | In-depth repository of Telegram OSINT resources covering, tools, techniques & tradecraft. | ⭐ `2024` | `N/A` |
| [n0a/telegram-get-remote-ip](https://github.com/n0a/telegram-get-remote-ip) | Get IP address on other side audio call in Telegram. | ⭐ `1857` | `Python` |
| [s0md3v/uro](https://github.com/s0md3v/uro) | declutters url lists for crawling/pentesting | ⭐ `1594` | `Python` |
| [forkgram/TelegramAndroid](https://github.com/forkgram/TelegramAndroid) | Fork client of Telegram app for Android. | ⭐ `1529` | `Java` |
| [superhedgy/AttackSurfaceMapper](https://github.com/superhedgy/AttackSurfaceMapper) | AttackSurfaceMapper is a tool that aims to automate the reconnaissance process. | ⭐ `1413` | `Python` |
| [Proviesec/google-dorks](https://github.com/Proviesec/google-dorks) | Useful Google Dorks for WebSecurity and Bug Bounty | ⭐ `1383` | `N/A` |
| [lc/subjs](https://github.com/lc/subjs) | Fetches javascript file from a list of URLS or subdomains. | ⭐ `864` | `Go` |
| [ArsenalRecon/Arsenal-Image-Mounter](https://github.com/ArsenalRecon/Arsenal-Image-Mounter) | Arsenal Image Mounter mounts the contents of disk images as complete disks in Microsoft Windows. | ⭐ `804` | `C#` |
| [Alb-310/Geogramint](https://github.com/Alb-310/Geogramint) | An OSINT Geolocalization tool for Telegram that find nearby users and groups ­ƒôí­ƒîì­ƒöì | ⭐ `732` | `Python` |
| [momenbasel/keyFinder](https://github.com/momenbasel/keyFinder) | Passive API key and secret discovery browser extension for Chrome and Firefox. 80+ detection patterns, zero config. | ⭐ `719` | `JavaScript` |
| [forkgram/tdesktop](https://github.com/forkgram/tdesktop) | Fork of Telegram Desktop messaging app. | ⭐ `655` | `C++` |
| [ayadim/Nuclei-bug-hunter](https://github.com/ayadim/Nuclei-bug-hunter) | i will upload more templates here to share with  the comunity. | ⭐ `572` | `N/A` |
| [XDeadHackerX/NetSoc_OSINT](https://github.com/XDeadHackerX/NetSoc_OSINT) | Tool focused on extracting information from an account in different Social Networks / Herramienta enfocada a extraer informaci├│n de una cuenta en diversas Redes Sociales, SIN usar nuestra Cuenta, NI API y SIN L├¡mite. [NO ME HAGO RESPONSABLE DEL MAL USO DE ESTA HERRAMIENTA] | ⭐ `518` | `Shell` |
| [KissPeter/APIFuzzer](https://github.com/KissPeter/APIFuzzer) | Fuzz test your application using your OpenAPI or Swagger API definition without coding | ⭐ `467` | `Python` |
| [r3curs1v3-pr0xy/sub404](https://github.com/r3curs1v3-pr0xy/sub404) | A python tool to check subdomain takeover vulnerability | ⭐ `354` | `Python` |
| [0xKayala/NucleiScanner](https://github.com/0xKayala/NucleiScanner) | NucleiScanner is a Powerful Automation tool for detecting Unknown Vulnerabilities in the Web Applications | ⭐ `347` | `Shell` |
| [JettChenT/scan-for-webcams](https://github.com/JettChenT/scan-for-webcams) | scan for webcams on the internet | ⭐ `274` | `Python` |
| [pielco11/telescan](https://github.com/pielco11/telescan) | Sin descripción | ⭐ `248` | `Python` |
| [ba0f3/telebot.nim](https://github.com/ba0f3/telebot.nim) | Async Telegram Bot API Client implement in @Nim-Lang | ⭐ `191` | `Nim` |
| [CScorza/SOCMIntelligence](https://github.com/CScorza/SOCMIntelligence) | Identificazione profili, relazioni, organizzazioni e tracciare reti | ⭐ `116` | `N/A` |
| [password123456/cve-collector](https://github.com/password123456/cve-collector) | Simple Latest CVE Collector Written in Python | ⭐ `60` | `Python` |
| [D3Ext/go-recon](https://github.com/D3Ext/go-recon) | External recon toolkit | ⭐ `58` | `Go` |
| [yss14/TelegramGameBotHacks](https://github.com/yss14/TelegramGameBotHacks) | A hack to register your desired score on the telegram lumberjack game. | ⭐ `44` | `JavaScript` |
| [ShadowVMX/Web-Scanner](https://github.com/ShadowVMX/Web-Scanner) | Escaner WEB que tiene como objetivo sacar toda la informaci├│n posible como IP, CMS, Usuarios, posibles correos, rendimiento de la URL, Puertos Abiertos, Subdirectorios ... Etc. | ⭐ `30` | `Shell` |
| [the5orcerer/Oh-Shit](https://github.com/the5orcerer/Oh-Shit) | Bunch of free OSINT tools which one are available on the internet. | ⭐ `24` | `N/A` |
| [gilangkurniiawant/GameeHack](https://github.com/gilangkurniiawant/GameeHack) | This will hack your score on Gamee Telegram bot | ⭐ `2` | `JavaScript` |
| [rggassner/telecrawler](https://github.com/rggassner/telecrawler) | A random telegram crawler that is able to save groups messages, files and images, and users related to groups. Sqlite is used for storage. This little project can be used to gather OSINT information. | ⭐ `1` | `Python` |
| [G0uth4m/Web-Spider](https://github.com/G0uth4m/Web-Spider) | A simple web spider built using python3 to get a sitemap of the whole website. | ⭐ `1` | `Python` |

---

## ⚙️ MÓDULO 06: DEVSECOPS, SAST/DAST & SEGURIDAD EN CÓDIGO
> Auditoría de código, escaneo de secretos, seguridad en APIs, GraphQL y pipelines CI/CD.

| Repositorio | Descripción | Stars | Lenguaje |
| :--- | :--- | :---: | :---: |
| [gitleaks/gitleaks](https://github.com/gitleaks/gitleaks) | Find secrets with Gitleaks ­ƒöæ | ⭐ `29554` | `Go` |
| [shieldfy/API-Security-Checklist](https://github.com/shieldfy/API-Security-Checklist) | Checklist of the most important security countermeasures when designing, testing, and releasing your API | ⭐ `23330` | `N/A` |
| [MobSF/Mobile-Security-Framework-MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) | Mobile Security Framework (MobSF) is an automated, all-in-one mobile application (Android/iOS/Windows) pen-testing, malware analysis and security assessment framework capable of performing static and dynamic analysis. | ⭐ `21852` | `JavaScript` |
| [bee-san/RustScan](https://github.com/bee-san/RustScan) | ­ƒñû The Modern Port Scanner ­ƒñû | ⭐ `20474` | `Rust` |
| [semgrep/semgrep](https://github.com/semgrep/semgrep) | Lightweight static analysis for many languages. Find bug variants with patterns that look like source code. | ⭐ `16792` | `C` |
| [telekom-security/tpotce](https://github.com/telekom-security/tpotce) | ­ƒì» T-Pot - The All In One Multi Honeypot Platform ­ƒÉØ | ⭐ `9544` | `Shell` |
| [exiftool/exiftool](https://github.com/exiftool/exiftool) | ExifTool meta information reader/writer | ⭐ `5105` | `Perl` |
| [google/grr](https://github.com/google/grr) | GRR Rapid Response: remote live forensics for incident response | ⭐ `5088` | `Python` |
| [khchen/winim](https://github.com/khchen/winim) | Windows API, COM, and CLR Module for Nim | ⭐ `514` | `Nim` |
| [EllyMandliel/WebDumper](https://github.com/EllyMandliel/WebDumper) | A tool for scraping, dumping and unpacking (webpacked) javascript source files. | ⭐ `158` | `TypeScript` |
| [amirinsight/py-bingx](https://github.com/amirinsight/py-bingx) | A Python package to easily use BingX Perpetual Swap API. Can be used to automate trading on BingX. | ⭐ `23` | `Python` |
| [FaztWeb/node-webscraping-proxy](https://github.com/FaztWeb/node-webscraping-proxy) | Sin descripción | ⭐ `8` | `JavaScript` |
| [gquagliano/api-ferozo](https://github.com/gquagliano/api-ferozo) | Interfaz PHP con el panel de control de hosting Ferozo. | ⭐ `2` | `PHP` |

---

## 🐬 MÓDULO 07: HARDWARE HACKING, RF & FLIPPER ZERO
> Firmwares modificados, Evil Portals, BadUSB, radiofrecuencia e interfaces físicas.

| Repositorio | Descripción | Stars | Lenguaje |
| :--- | :--- | :---: | :---: |
| [DarkFlippers/unleashed-firmware](https://github.com/DarkFlippers/unleashed-firmware) | Flipper Zero Unleashed Firmware | ⭐ `22394` | `C` |
| [flipperdevices/flipperzero-firmware](https://github.com/flipperdevices/flipperzero-firmware) | Flipper Zero firmware source code | ⭐ `16652` | `C` |
| [Flipper-XFW/Xtreme-Firmware](https://github.com/Flipper-XFW/Xtreme-Firmware) | The Dom amongst the Flipper Zero Firmware. Give your Flipper the power and freedom it is really craving. Let it show you its true form. Dont delay, switch to the one and only true Master today! | ⭐ `9900` | `C` |
| [RogueMaster/flipperzero-firmware-wPlugins](https://github.com/RogueMaster/flipperzero-firmware-wPlugins) | RogueMaster Flipper Zero Firmware | ⭐ `6373` | `C` |
| [derv82/wifite](https://github.com/derv82/wifite) | Sin descripción | ⭐ `3657` | `Python` |
| [D3Ext/WEF](https://github.com/D3Ext/WEF) | Wi-Fi Exploitation Framework | ⭐ `3222` | `Shell` |
| [bigbrodude6119/flipper-zero-evil-portal](https://github.com/bigbrodude6119/flipper-zero-evil-portal) | Evil portal app for the flipper zero + WiFi dev board | ⭐ `2362` | `HTML` |
| [flipperdevices/qFlipper](https://github.com/flipperdevices/qFlipper) | qFlipper ÔÇö desktop application for updating Flipper Zero firmware via PC | ⭐ `1657` | `C++` |
| [RocketGod-git/Flipper_Zero](https://github.com/RocketGod-git/Flipper_Zero) | My SD Drive for Flipper Zero | ⭐ `1594` | `PowerShell` |
| [flipperdevices/flipperzero-3d-models](https://github.com/flipperdevices/flipperzero-3d-models) | Flipper Zero 3D models | ⭐ `656` | `N/A` |
| [mame82/duckencoder.py](https://github.com/mame82/duckencoder.py) | Python port of infamous duckencoder for RubberDucky | ⭐ `151` | `Python` |
| [C0n4r7157/git-github.com-ClaraCrazy-Flipper-Xtreme](https://github.com/C0n4r7157/git-github.com-ClaraCrazy-Flipper-Xtreme) | Flipper zero | ⭐ `28` | `N/A` |
| [dherl0623/wifi-deauth](https://github.com/dherl0623/wifi-deauth) | Automated wifi deauthenticator of clients using MDK3. | ⭐ `5` | `Shell` |

---

## 📜 MÓDULO 08: EXPLOITS CVE, CHEATSHEETS & CERTIFICACIONES
> Vulnerabilidades conocidas (CVE), repositorios de trucos para OSCP/CRTO y guías operativas.

| Repositorio | Descripción | Stars | Lenguaje |
| :--- | :--- | :---: | :---: |
| [trekhleb/learn-python](https://github.com/trekhleb/learn-python) | ­ƒôÜ Playground and cheatsheet for learning Python. Collection of Python scripts that are split by topics and contain code examples with explanations. | ⭐ `18324` | `Python` |
| [berstend/puppeteer-extra](https://github.com/berstend/puppeteer-extra) | ­ƒÆ»  Teach puppeteer new tricks through plugins. | ⭐ `7404` | `JavaScript` |
| [epsylon/xsser](https://github.com/epsylon/xsser) | Cross Site "Scripter" (aka XSSer) is an automatic -framework- to detect, exploit and report XSS vulnerabilities in web-based applications. | ⭐ `1466` | `Python` |
| [klezVirus/CVE-2021-40444](https://github.com/klezVirus/CVE-2021-40444) | CVE-2021-40444 - Fully Weaponized Microsoft Office Word RCE Exploit | ⭐ `834` | `HTML` |
| [0xb0bb/pwndra](https://github.com/0xb0bb/pwndra) | A collection of pwn/CTF related utilities for Ghidra | ⭐ `708` | `Python` |
| [ieshreya/obsidian-cheat-sheet](https://github.com/ieshreya/obsidian-cheat-sheet) | all the basic cheatsheets you need to get started to make notes in obsidian. | ⭐ `666` | `N/A` |
| [EntySec/CamOver](https://github.com/EntySec/CamOver) | CamOver is a camera exploitation tool that allows to disclosure network camera admin password. | ⭐ `601` | `Python` |
| [caster0x00/Intercept](https://github.com/caster0x00/Intercept) | MITM Field Manual | ⭐ `389` | `N/A` |
| [Twigonometry/OSCP-Notes-Template](https://github.com/Twigonometry/OSCP-Notes-Template) | A template Obsidian Vault for storing your OSCP revision notes | ⭐ `309` | `N/A` |
| [bcdannyboy/CVE-2023-44487](https://github.com/bcdannyboy/CVE-2023-44487) | Basic vulnerability scanning to see if web servers may be vulnerable to CVE-2023-44487 | ⭐ `247` | `Python` |
| [ayoubfaouzi/windows-exploitation](https://github.com/ayoubfaouzi/windows-exploitation) | My notes while studying Windows exploitation | ⭐ `194` | `C++` |
| [Cuerz/CVE-2021-36260](https://github.com/Cuerz/CVE-2021-36260) | µÁÀÕ║ÀÕ¿üÞºåRCEµ╝Åµ┤× µë╣ÚçÅµúÇµÁïÕÆîÕê®þö¿ÕÀÑÕàÀ | ⭐ `170` | `Python` |
| [pimps/CVE-2018-7600](https://github.com/pimps/CVE-2018-7600) | Exploit for Drupal 7 <= 7.57 CVE-2018-7600 | ⭐ `140` | `Python` |
| [tandasat/CVE-2023-36427](https://github.com/tandasat/CVE-2023-36427) | Report and exploit of CVE-2023-36427 | ⭐ `89` | `C++` |
| [ContandoBits/CRTO-Cheatsheet-Mindmap](https://github.com/ContandoBits/CRTO-Cheatsheet-Mindmap) | A cheatsheet and mindmap for CRTO certification | ⭐ `16` | `N/A` |
| [G0uth4m/XSSploit](https://github.com/G0uth4m/XSSploit) | A python3 tool for testing XSS vulnerabilities and finding appropriate exploit | ⭐ `4` | `Python` |
| [JuanPMC/MassExploiting](https://github.com/JuanPMC/MassExploiting) | Usando el obvserver pattern para explotar en masa | ⭐ `3` | `Python` |

---

## 🔬 MÓDULO 09: ANÁLISIS FORENSE (DFIR) & REVERSE ENGINEERING
> Análisis de memoria, desensamblado, extracción de artefactos y peritaje.

| Repositorio | Descripción | Stars | Lenguaje |
| :--- | :--- | :---: | :---: |
| [NationalSecurityAgency/ghidra](https://github.com/NationalSecurityAgency/ghidra) | Ghidra is a software reverse engineering (SRE) framework | ⭐ `79918` | `Java` |
| [ufrisk/MemProcFS](https://github.com/ufrisk/MemProcFS) | MemProcFS | ⭐ `4357` | `C` |
| [ElevenPaths/FOCA](https://github.com/ElevenPaths/FOCA) | Tool to find metadata and hidden information in the documents. | ⭐ `3645` | `C#` |
| [pentestmonkey/php-reverse-shell](https://github.com/pentestmonkey/php-reverse-shell) | Sin descripción | ⭐ `2881` | `PHP` |
| [jtsylve/LiME](https://github.com/jtsylve/LiME) | LiME (formerly DMD) is a Loadable Kernel Module (LKM), which allows the acquisition of volatile memory from Linux and Linux-based devices, such as those powered by Android. The tool supports acquiring memory either to the file system of the device or over the network. LiME is unique in that it is the first tool that allows full memory captures from Android devices. It also minimizes its interaction between user and kernel space processes during acquisition, which allows it to produce memory captures that are more forensically sound than those of other tools designed for Linux memory acquisition. | ⭐ `2040` | `C` |
| [den4uk/andriller](https://github.com/den4uk/andriller) | ­ƒô▒ Andriller - is software utility with a collection of forensic tools for smartphones. It performs read-only, forensically sound, non-destructive acquisition from Android devices. | ⭐ `1613` | `Python` |
| [mozilla/mig](https://github.com/mozilla/mig) | Distributed & real time digital forensics at the speed of the cloud | ⭐ `1203` | `Go` |
| [denandz/KeeFarce](https://github.com/denandz/KeeFarce) | Extracts passwords from a KeePass 2.x database, directly from memory. | ⭐ `1028` | `C++` |
| [vitaly-kamluk/bitscout](https://github.com/vitaly-kamluk/bitscout) | Remote forensics meta tool | ⭐ `482` | `Shell` |
| [kevthehermit/VolUtility](https://github.com/kevthehermit/VolUtility) | Web App for Volatility framework | ⭐ `388` | `Python` |
| [BusKill/buskill-app](https://github.com/BusKill/buskill-app) | BusKill's main CLI/GUI app for arming/disarming/configuring the BusKill laptop kill cord | ⭐ `326` | `Python` |
| [arxsys/dff](https://github.com/arxsys/dff) | DFF (Digital Forensics Framework) is a Forensics Framework coming with command line and graphical interfaces. DFF can be used to investigate hard drives and volatile memory and create reports about user and system activities. | ⭐ `318` | `Python` |
| [ReversecLabs/Ninjasploit](https://github.com/ReversecLabs/Ninjasploit) | A meterpreter extension for applying hooks to avoid windows defender memory scans | ⭐ `251` | `C` |
| [coinbase/dexter](https://github.com/coinbase/dexter) | Forensics acquisition framework designed to be extensible and secure | ⭐ `127` | `Go` |

---

## 📦 MÓDULO 10: UTILIDADES Y HERRAMIENTAS DIVERSAS
> Scripts auxiliares, bots, extensiones y utilidades de automatización general.

| Repositorio | Descripción | Stars | Lenguaje |
| :--- | :--- | :---: | :---: |
| [ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp) | LLM inference in C/C++ | ⭐ `129855` | `C++` |
| [deepseek-ai/DeepSeek-V3](https://github.com/deepseek-ai/DeepSeek-V3) | Sin descripción | ⭐ `104505` | `Python` |
| [abi/screenshot-to-code](https://github.com/abi/screenshot-to-code) | Drop in a screenshot and convert it to clean code (HTML/Tailwind/React/Vue) | ⭐ `79846` | `Python` |
| [Z4nzu/hackingtool](https://github.com/Z4nzu/hackingtool) | ALL IN ONE Hacking Tool For Hackers | ⭐ `79841` | `Python` |
| [ryanoasis/nerd-fonts](https://github.com/ryanoasis/nerd-fonts) | Iconic font aggregator, collection, & patcher. 3,600+ icons, 50+ patched fonts: Hack, Source Code Pro, more. Glyph collections: Font Awesome, Material Design Icons, Octicons, & more | ⭐ `64758` | `CSS` |
| [dylanaraps/pure-bash-bible](https://github.com/dylanaraps/pure-bash-bible) | ­ƒôû A collection of pure bash alternatives to external processes. | ⭐ `41715` | `Shell` |
| [gchq/CyberChef](https://github.com/gchq/CyberChef) | The Cyber Swiss Army Knife - a web app for encryption, encoding, compression and data analysis | ⭐ `35987` | `JavaScript` |
| [flameshot-org/flameshot](https://github.com/flameshot-org/flameshot) | Powerful yet simple to use screenshot software :desktop_computer: :camera_flash: | ⭐ `31013` | `C++` |
| [iperov/DeepFaceLab](https://github.com/iperov/DeepFaceLab) | DeepFaceLab is the leading software for creating deepfakes. | ⭐ `19281` | `Python` |
| [vxunderground/MalwareSourceCode](https://github.com/vxunderground/MalwareSourceCode) | Collection of malware source code for a variety of platforms in an array of different programming languages. | ⭐ `18756` | `Assembly` |
| [trustedsec/social-engineer-toolkit](https://github.com/trustedsec/social-engineer-toolkit) | The Social-Engineer Toolkit (SET) repository from TrustedSec - All new versions of SET will be deployed here. | ⭐ `15343` | `Python` |
| [gophish/gophish](https://github.com/gophish/gophish) | Open-Source Phishing Toolkit | ⭐ `14271` | `Go` |
| [redcanaryco/atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | Small and highly portable detection tests based on MITRE's ATT&CK. | ⭐ `12597` | `C` |
| [secdev/scapy](https://github.com/secdev/scapy) | Scapy: the Python-based interactive packet manipulation program & library. | ⭐ `12573` | `Python` |
| [0xk1h0/ChatGPT_DAN](https://github.com/0xk1h0/ChatGPT_DAN) | ChatGPT DAN, Jailbreaks prompt | ⭐ `12514` | `N/A` |
| [infosecn1nja/Red-Teaming-Toolkit](https://github.com/infosecn1nja/Red-Teaming-Toolkit) | This repository contains cutting-edge open-source security tools (OST) for a red teamer and threat hunter. | ⭐ `10746` | `N/A` |
| [jgamblin/Mirai-Source-Code](https://github.com/jgamblin/Mirai-Source-Code) | Leaked Mirai Source Code for Research/IoC Development Purposes | ⭐ `9513` | `C` |
| [LOLBAS-Project/LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | Living Off The Land Binaries And Scripts - (LOLBins and LOLScripts) | ⭐ `8842` | `XSLT` |
| [bee-san/pyWhat](https://github.com/bee-san/pyWhat) | ­ƒÉ©   Identify anything. pyWhat easily lets you identify emails, IP addresses, and more. Feed it a .pcap file or some text and it'll tell you what it is! ­ƒºÖÔÇìÔÖÇ´©Å | ⭐ `7321` | `Python` |
| [apache/caldera](https://github.com/apache/caldera) | Automated Adversary Emulation Platform | ⭐ `7298` | `Python` |
| [ritwickdey/vscode-live-server](https://github.com/ritwickdey/vscode-live-server) | Launch a development local Server with live reload feature for static & dynamic pages. | ⭐ `6871` | `TypeScript` |
| [FluxionNetwork/fluxion](https://github.com/FluxionNetwork/fluxion) | Fluxion is a remake of linset by vk496 with enhanced functionality. | ⭐ `5957` | `HTML` |
| [BurntSushi/toml](https://github.com/BurntSushi/toml) | TOML parser for Golang with reflection. | ⭐ `5013` | `Go` |
| [x64dbg/ScyllaHide](https://github.com/x64dbg/ScyllaHide) | Advanced usermode anti-anti-debugger. Forked from https://bitbucket.org/NtQuery/scyllahide | ⭐ `4313` | `C++` |
| [201853910/VMwareWorkstation](https://github.com/201853910/VMwareWorkstation) | µëïÕè¿õ©èõ╝áÕ«ÿþ¢æþÜäVMwareWorkstationÕ«ëÞúàÕîà | ⭐ `4299` | `N/A` |
| [protocolbuffers/protobuf-go](https://github.com/protocolbuffers/protobuf-go) | Go support for Google's protocol buffers | ⭐ `3357` | `Go` |
| [ignis-sec/Pwdb-Public](https://github.com/ignis-sec/Pwdb-Public) | A collection of all the data i could extract from 1 billion leaked credentials from internet. | ⭐ `3303` | `N/A` |
| [mkaring/ConfuserEx](https://github.com/mkaring/ConfuserEx) | An open-source, free protector for .NET applications | ⭐ `2902` | `C#` |
| [everdox/InfinityHook](https://github.com/everdox/InfinityHook) | Hook system calls, context switches, page faults and more. | ⭐ `2682` | `C++` |
| [ohmplatform/FreedomGPT](https://github.com/ohmplatform/FreedomGPT) | This codebase is for a React and Electron-based app that executes the FreedomGPT LLM locally (offline and private) on Mac and Windows using a chat-based interface | ⭐ `2674` | `TypeScript` |
| [arthaud/git-dumper](https://github.com/arthaud/git-dumper) | A tool to dump a git repository from a website | ⭐ `2671` | `Python` |
| [kismetwireless/kismet](https://github.com/kismetwireless/kismet) | Github mirror of official Kismet repository | ⭐ `2229` | `C++` |
| [thinkst/canarytokens](https://github.com/thinkst/canarytokens) | Canarytokens helps track activity and actions on your network | ⭐ `2169` | `Python` |
| [tomnomnom/gf](https://github.com/tomnomnom/gf) | A wrapper around grep, to help you grep for things | ⭐ `2138` | `Go` |
| [defparam/smuggler](https://github.com/defparam/smuggler) | Smuggler - An HTTP Request Smuggling / Desync testing tool written in Python 3 | ⭐ `2110` | `Python` |
| [w2016561536/android_virtual_cam](https://github.com/w2016561536/android_virtual_cam) | xposedÕ«ëÕìôÞÖÜµïƒµæäÕâÅÕñ┤ android virtual camera on xposed hook | ⭐ `2065` | `Java` |
| [fin3ss3g0d/evilgophish](https://github.com/fin3ss3g0d/evilgophish) | evilginx3 + gophish | ⭐ `2029` | `Go` |
| [CCob/SweetPotato](https://github.com/CCob/SweetPotato) | Local Service to SYSTEM privilege escalation from Windows 7 to Windows 10 / Server 2019 | ⭐ `1845` | `C#` |
| [hlldz/Phant0m](https://github.com/hlldz/Phant0m) | Windows Event Log Killer | ⭐ `1808` | `C` |
| [MScholtes/PS2EXE](https://github.com/MScholtes/PS2EXE) | Module to compile powershell scripts to executables | ⭐ `1786` | `PowerShell` |
| [r3motecontrol/Ghostpack-CompiledBinaries](https://github.com/r3motecontrol/Ghostpack-CompiledBinaries) | Compiled Binaries for Ghostpack | ⭐ `1761` | `N/A` |
| [Mr-Un1k0d3r/SCShell](https://github.com/Mr-Un1k0d3r/SCShell) | Fileless lateral movement tool that relies on ChangeServiceConfigA to run command | ⭐ `1667` | `C` |
| [hatRiot/zarp](https://github.com/hatRiot/zarp) | Network Attack Tool | ⭐ `1507` | `Python` |
| [elastic/protections-artifacts](https://github.com/elastic/protections-artifacts) | Elastic Security detection content for Endpoint | ⭐ `1495` | `YARA` |
| [1ndianl33t/Gf-Patterns](https://github.com/1ndianl33t/Gf-Patterns) | GF Paterns For (ssrf,RCE,Lfi,sqli,ssti,idor,url redirection,debug_logic, interesting Subs) parameters grep | ⭐ `1457` | `N/A` |
| [simsong/bulk_extractor](https://github.com/simsong/bulk_extractor) | This is the development tree. Production downloads are at: | ⭐ `1427` | `C++` |
| [Octoberfest7/TeamsPhisher](https://github.com/Octoberfest7/TeamsPhisher) | Send phishing messages and attachments to Microsoft Teams users | ⭐ `1125` | `Python` |
| [0xbadjuju/Tokenvator](https://github.com/0xbadjuju/Tokenvator) | A tool to elevate privilege with Windows Tokens | ⭐ `1065` | `C#` |
| [vulmon/Vulmap](https://github.com/vulmon/Vulmap) | Vulmap Online Local Vulnerability Scanners Project | ⭐ `977` | `Python` |
| [RamblingCookieMonster/PowerShell](https://github.com/RamblingCookieMonster/PowerShell) | Various PowerShell functions and scripts | ⭐ `973` | `PowerShell` |
| [Mr-Un1k0d3r/RedTeamPowershellScripts](https://github.com/Mr-Un1k0d3r/RedTeamPowershellScripts) | Various PowerShell scripts that may be useful during red team exercise | ⭐ `967` | `PowerShell` |
| [Las-Fuerzas-Del-Cielo/Sistema-Anti-Fraude-Electoral](https://github.com/Las-Fuerzas-Del-Cielo/Sistema-Anti-Fraude-Electoral) | Sistema Open Source para Identificar potenciales fraudes electorales, minimizar su ocurrencia e impacto. | ⭐ `963` | `PHP` |
| [tomnomnom/qsreplace](https://github.com/tomnomnom/qsreplace) | Accept URLs on stdin, replace all query string values with a user-supplied value | ⭐ `887` | `Go` |
| [BishopFox/h2csmuggler](https://github.com/BishopFox/h2csmuggler) | HTTP Request Smuggling over HTTP/2 Cleartext (h2c) | ⭐ `819` | `Python` |
| [praetorian-inc/PortBender](https://github.com/praetorian-inc/PortBender) | TCP Port Redirection Utility | ⭐ `787` | `C` |
| [lclevy/firepwd](https://github.com/lclevy/firepwd) | firepwd.py, an open source tool to decrypt Mozilla protected passwords | ⭐ `767` | `Python` |
| [tastypepperoni/PPLBlade](https://github.com/tastypepperoni/PPLBlade) | Protected Process Dumper Tool | ⭐ `602` | `Go` |
| [IntelligenceX/SDK](https://github.com/IntelligenceX/SDK) | Public SDK for Intelligence X | ⭐ `554` | `Python` |
| [WKL-Sec/Malleable-CS-Profiles](https://github.com/WKL-Sec/Malleable-CS-Profiles) | A list of python tools to help create an OPSEC-safe Cobalt Strike profile. | ⭐ `544` | `C++` |
| [C-Sto/BananaPhone](https://github.com/C-Sto/BananaPhone) | It's a go variant of Hells gate! (directly calling windows kernel functions, but from Go!) | ⭐ `532` | `Go` |
| [Enelg52/OffensiveGo](https://github.com/Enelg52/OffensiveGo) | Golang weaponization for red teamers. | ⭐ `527` | `Go` |
| [thefLink/RecycledGate](https://github.com/thefLink/RecycledGate) | Hellsgate + Halosgate/Tartarosgate. Ensures that all systemcalls go through ntdll.dll | ⭐ `518` | `C` |
| [CanIPhish/Phishious](https://github.com/CanIPhish/Phishious) | An open-source Secure Email Gateway (SEG) evaluation toolkit designed for red-teamers. | ⭐ `515` | `C#` |
| [JoelGMSec/LeakSearch](https://github.com/JoelGMSec/LeakSearch) | Search & Parse Password Leaks | ⭐ `447` | `Python` |
| [conjure-up/conjure-up](https://github.com/conjure-up/conjure-up) | Deploying complex solutions, magically. | ⭐ `447` | `Python` |
| [eddiechu/File-Smuggling](https://github.com/eddiechu/File-Smuggling) | HTML smuggling is not an evil, it can be useful | ⭐ `391` | `HTML` |
| [MatthewClarkMay/geoip-attack-map](https://github.com/MatthewClarkMay/geoip-attack-map) | Cyber security geoip attack map that follows syslog and parses IPs/port numbers to visualize attackers in real time. | ⭐ `368` | `Python` |
| [S3cur3Th1sSh1t/Invoke-SharpLoader](https://github.com/S3cur3Th1sSh1t/Invoke-SharpLoader) | Sin descripción | ⭐ `360` | `PowerShell` |
| [cobbr/SharpGen](https://github.com/cobbr/SharpGen) | SharpGen is a .NET Core console application that utilizes the Rosyln C# compiler to quickly cross-compile .NET Framework console applications or libraries. | ⭐ `301` | `C#` |
| [bp0lr/gauplus](https://github.com/bp0lr/gauplus) | Sin descripción | ⭐ `298` | `Go` |
| [Quillhash/DeFi-Attack-Vectors](https://github.com/Quillhash/DeFi-Attack-Vectors) | This Repository contains list of Common DeFi threat and Attack Vectors. If you find any attack vectors missing, you can create a pull request and be a contributor of the project. | ⭐ `229` | `N/A` |
| [ropnop/go-clr](https://github.com/ropnop/go-clr) | A PoC package for hosting the CLR and executing .NET from Go | ⭐ `226` | `Go` |
| [orkido/LViewLoL](https://github.com/orkido/LViewLoL) | League of Legends Python based scripting platform. | ⭐ `224` | `C++` |
| [ralphte/build_a_phish](https://github.com/ralphte/build_a_phish) | Ansible playbook to deploy a phishing engagement in the cloud. | ⭐ `221` | `Jinja` |
| [EntySec/Shreder](https://github.com/EntySec/Shreder) | Shreder is a powerful multi-threaded SSH protocol password brute-force tool. | ⭐ `218` | `Python` |
| [C-Sto/goWMIExec](https://github.com/C-Sto/goWMIExec) | Really stupid re-implementation of invoke-wmiexec | ⭐ `215` | `Go` |
| [bluesentinelsec/OffensiveGoLang](https://github.com/bluesentinelsec/OffensiveGoLang) | A collection of Offensive Go packages. | ⭐ `214` | `Go` |
| [puzzlepeaches/sneaky_gophish](https://github.com/puzzlepeaches/sneaky_gophish) | Hiding GoPhish from the boys in blue | ⭐ `208` | `Go` |
| [rischanlab/bruteforce_py](https://github.com/rischanlab/bruteforce_py) | all bruteforces with python, ssh bf, wordpress bf, cpanel bf, mysql bf, etc | ⭐ `202` | `Python` |
| [smaranchand/bucky](https://github.com/smaranchand/bucky) | Bucky (An automatic S3 bucket discovery tool) | ⭐ `197` | `PHP` |
| [daffainfo/Oneliner-Bugbounty](https://github.com/daffainfo/Oneliner-Bugbounty) | A collection  oneliner scripts for bug bounty | ⭐ `185` | `N/A` |
| [idiotc4t/Reflective-HackBrowserData](https://github.com/idiotc4t/Reflective-HackBrowserData) | HackBrowserDataþÜäÕÅìÕ░äµ¿íÕØù | ⭐ `179` | `Go` |
| [TheGetch/Burp-Suite-Pro-Scan-Profiles](https://github.com/TheGetch/Burp-Suite-Pro-Scan-Profiles) | Custom scan profiles for use with Burp Suite Pro | ⭐ `154` | `N/A` |
| [lesnuages/go-execute-assembly](https://github.com/lesnuages/go-execute-assembly) | Allow a Go process to dynamically load .NET assemblies | ⭐ `148` | `Go` |
| [mttaggart/blue-jupyter](https://github.com/mttaggart/blue-jupyter) | Jupyter Notebooks for the Blue Team | ⭐ `146` | `Jupyter Notebook` |
| [nymtech/CensorshipMeasurements](https://github.com/nymtech/CensorshipMeasurements) | Censorship tests for the Nym network | ⭐ `143` | `Go` |
| [Peco602/findwall](https://github.com/Peco602/findwall) | Check if your provider is blocking you! | ⭐ `103` | `Python` |
| [OscarDogar/Platzi-Download](https://github.com/OscarDogar/Platzi-Download) | Permite descargar videos de platzi muchos m├ís r├ípido. Permite descargar tanto los videos, las lecturas, los subt├¡tulos (si est├ín disponibles) y los recursos de cada una de las clases. | ⭐ `100` | `Python` |
| [S3cur3Th1sSh1t/Sharp-HackBrowserData](https://github.com/S3cur3Th1sSh1t/Sharp-HackBrowserData) | C# binary with embeded golang hack-browser-data | ⭐ `100` | `C#` |
| [enigma0x3/MessageBox](https://github.com/enigma0x3/MessageBox) | PoC dlls for Task Scheduler COM Hijacking | ⭐ `95` | `C++` |
| [kulaginds/rdp-html5](https://github.com/kulaginds/rdp-html5) | RDP web client with Golang backend for proxy connection to Windows machine | ⭐ `94` | `Go` |
| [shlima/fortune](https://github.com/shlima/fortune) | Ôÿá´©Å bitcoin rich address miner, steal bitcoins by checking private keys for balance (bundled dataset) | ⭐ `88` | `Go` |
| [ncorbuk/Google-Chrome-Browser-Database-Hack](https://github.com/ncorbuk/Google-Chrome-Browser-Database-Hack) | Google Chrome Database Cracking Hacking - Get username & passwords | ⭐ `81` | `Python` |
| [p0dalirius/LFIDump](https://github.com/p0dalirius/LFIDump) | A simple python script to dump remote files through a local file read or local file inclusion web vulnerability. | ⭐ `79` | `Python` |
| [Mario-Hero/toolUnRar](https://github.com/Mario-Hero/toolUnRar) | þö¿Pythonµë╣ÚçÅÞºúÕÄïÕ©ªÕ»åþáüþÜäÕÄïþ╝®Õîà A Python script for batch extraction with passwords | ⭐ `75` | `Python` |
| [HalilDeniz/CryptoChat](https://github.com/HalilDeniz/CryptoChat) | CryptChat: Beyond Secure Messaging ­ƒøí´©Å | ⭐ `73` | `Python` |
| [magichk/magicleaks](https://github.com/magichk/magicleaks) | Magicleaks it's a python script that checks if an email or a list of email accounts was compromised | ⭐ `73` | `Python` |
| [nytr0gen/deduplicate](https://github.com/nytr0gen/deduplicate) | Remove duplicate urls from input | ⭐ `58` | `Go` |
| [qi4L/Phant0m-go](https://github.com/qi4L/Phant0m-go) | kill windows log | ⭐ `42` | `Go` |
| [D3Ext/malware-practices](https://github.com/D3Ext/malware-practices) | Repo for malware development practices I post on my blog | ⭐ `36` | `Go` |
| [maesoser/sshscan](https://github.com/maesoser/sshscan) | Multithreaded ssh scan tool for networks | ⭐ `20` | `C` |
| [Mario-Hero/Tarot-Card](https://github.com/Mario-Hero/Tarot-Card) | Õíöþ¢ùþëîÕìáÕì£PythonÞäÜµ£¼ÒÇéTarot-Card Python script. | ⭐ `19` | `Python` |
| [bfrasure/opensea_mint_and_list_automation](https://github.com/bfrasure/opensea_mint_and_list_automation) | Batch Mint and List NFTs on Opensea. This script uses selenium python to automate a chrome driver, letting you batch upload and list however many pictures or files as you want. | ⭐ `19` | `N/A` |
| [Amansinghtech/BadBot](https://github.com/Amansinghtech/BadBot) | Sin descripción | ⭐ `10` | `Python` |
| [thesubtlety/offsec-golang-utilities](https://github.com/thesubtlety/offsec-golang-utilities) | Sin descripción | ⭐ `9` | `Go` |
| [CodeWithJoe2020/Mempool](https://github.com/CodeWithJoe2020/Mempool) | Query the mempoool with nodeJS and ethersJs | ⭐ `9` | `JavaScript` |
| [cluster311/obras-sociales-argentinas](https://github.com/cluster311/obras-sociales-argentinas) | Lista de las obras sociales argentinas | ⭐ `9` | `Python` |
| [FaztWeb/cryptomus-nodejs](https://github.com/FaztWeb/cryptomus-nodejs) | Sin descripción | ⭐ `8` | `JavaScript` |
| [FaztWeb/react-webcam-tutorial](https://github.com/FaztWeb/react-webcam-tutorial) | React Webcam Tutorial | ⭐ `7` | `TypeScript` |
| [fbsobreira/tron-python-automate-send](https://github.com/fbsobreira/tron-python-automate-send) | Python tool automate send TRX from dividend accounts to main wallet | ⭐ `7` | `N/A` |
| [KevinDeep/IPEXTREME](https://github.com/KevinDeep/IPEXTREME) | IP locator! it also allows you to check if the IP address is suspicious! | ⭐ `7` | `Python` |
| [p-qq/Password-Grabber](https://github.com/p-qq/Password-Grabber) | just a password stealer in go this is all for educational purposes | ⭐ `6` | `Go` |
| [MRMYSTERY003/dont-run-this](https://github.com/MRMYSTERY003/dont-run-this) | just dont download and run this file | ⭐ `5` | `Python` |
| [Busirus/PyQt5-EmailSpoofing-Tool](https://github.com/Busirus/PyQt5-EmailSpoofing-Tool) | "Email Spoofing App is a tool for sending emails with a spoofed sender address and name. Features include HTML templates, attachments. For educational purposes only. | ⭐ `4` | `Python` |
| [Dkavalanche/decoder](https://github.com/Dkavalanche/decoder) | Another Grandoreiro malware decoder but in assembler | ⭐ `4` | `Assembly` |
| [tcpcon/Chrome-v80-Dump](https://github.com/tcpcon/Chrome-v80-Dump) | Go code to dump chromium browsers. | ⭐ `4` | `Go` |
| [Hl4p3x/Anti-DDOS](https://github.com/Hl4p3x/Anti-DDOS) | ­ƒöÆ Anti DDOS - Bash Script Project ­ƒöÆ | ⭐ `4` | `N/A` |
| [galviy/rdp-stealer](https://github.com/galviy/rdp-stealer) | simple rdp stealer written on node js (undetectable program) | ⭐ `3` | `JavaScript` |
| [balerdis/valida-renaper](https://github.com/balerdis/valida-renaper) | Sin descripción | ⭐ `1` | `PHP` |

---

