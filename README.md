WAScan - Web Application Scanner

WAScan ((W)eb (A)pplication (Scan)ner) is a Open Source web application security scanner. It is designed to find various vulnerabilities using "black-box" method, 
that means it won't study the source code of web applications but will work like a fuzzer, scanning the pages of the deployed web application, 
extracting links and forms and attacking the scripts, sending payloads and looking for error messages,..etc. 
WAScan is built on python2.7 and can run on any platform which has a Python environment.

Features

    Fingerprint
        Detect Server
        Detect Web Frameworks (22)
        Check Cookie Security
        Check Headers Security
        Detect Language (9)
        Detect Operating System (OS - 8)
        Detect Content Management System (CMS - 6)
        Detect Web Application Firewall (WAF - 54)

    Attacks
        Bash Command Injection (ShellShock)
        Blind SQL Injection
        SQL Injection via Cookie,Referer and User-Agent Header Value
        Cross-Site Scripting (XSS) via Cookie,Referer and User-Agent Header Value
        Buffer Overflow
        HTML Code Injection
        PHP Code Injection
        LDAP Injection
        Local File Inclusion (lfi)
        OS Commanding
        SQL Injection
        XPath Injection
        Cross Site Scripting (XSS)

    Audit
        Apache Status
        WebDav
        PHPInfo
        Robots Paths
        Cross-Site Tracing (XST)

    Bruteforce
        Admin Panel
        Backdoor (shell)
        Backup Dirs
        Backup Files
        Common Dirs
        Common Files

    Disclosure
        Credit Cards
        Emails
        Private IP
        SSN
        Detect Warnings,Fatal Error,...

Installation

$ git clone https://github.com/HackingTeamOficial/wascan 
$ cd wascan 
$ pip install -r requirements.txt
$ python wascan.py


