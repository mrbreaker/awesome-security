# Awesome security [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A list of security tools and links that I find useful.

## Contents
- [Web applications](#web-applications)
  - [Reconnaissance](#reconnaissance)
  - [Domain discovery](#domain-discovery)
  - [Vulnerabilities](#web-application-vulnerabilities)
  - [Authentication bypass](#authentication-bypass)
- [Networks](#networks)
  - [Discovery](#network-discovery)
- [Reverse engineering](#reverse-engineering)
  - [Tools](#re-tools)
  - [Reading materials](#re-reading-materials)
  - [Cheat sheets](#re-cheat-sheets)
- [RSS feeds](#rss-feeds)
- [Thanks](#thanks)
- [License](#license)

## Web applications

### Domain discovery
- [VirusTotal](https://virustotal.com)
    + domain:target.com
- [Censys](https://censys.io)
    + 443.https.tls.certificate.parsed.extensions.subject_alt_name.dns_names:target.com
- [DNSdumpster](https://dnsdumpster.com)
- [crt.sh](https://crt.sh)
- [Netcraft searchdns](https://searchdns.netcraft.com)
- [Shodan](https://www.shodan.io)

### Web application vulnerabilities
- XSS
  - [BeEF](https://github.com/beefproject/beef)
  - [RequestBin](https://requestb.in/)
- SSRF
  - [SSRF bible](https://docs.google.com/document/d/1v1TkWZtrhzRLy0bYXBcdLUedXGb9njTNIJXa3u9akHM/edit)
  - [A new era of SSRF exploiting in trending programming languages](https://www.blackhat.com/docs/us-17/thursday/us-17-Tsai-A-New-Era-Of-SSRF-Exploiting-URL-Parser-In-Trending-Programming-Languages.pdf)
- XML
  - [XML cheatsheet](https://gist.github.com/mgeeky/4f726d3b374f0a34267d4f19c9004870)

### Authentication
- SAML
  - [Office365 bypass](http://www.economyofmechanism.com/office365-authbypass.html#office365-authbypass)
  - [Uber bypass](http://blog.mish.re/index.php/2017/09/06/uber-bug-bounty-gaining-access-to-an-internal-chat-system/)

### Fuzzers
- [Tiny URL Fuzzer](https://github.com/orangetw/Tiny-URL-Fuzzer) - A tiny and cute URL fuzzer

## Networks
### Network Discovery 
- [A Masscan Tutorial and Primer](https://danielmiessler.com/study/masscan/) - A basic masscan tutorial by Daniel Messler

## Reverse Engineering
### RE Tools
- [Compiler explorer](https://gcc.godbolt.org/)

### RE Reading materials
- [Reverse engineering for beginners](https://beginners.re/RE4B-EN.pdf)

### RE Cheat sheets 
- [Zeltser](https://zeltser.com/reverse-engineering-malicious-code-tips/)

## Malware analysis
- [Unpacking Shade](https://secrary.com/ReversingMalware/UnpackingShade/)

## RSS feeds
- Forums
  - [/r/hacking](https://www.reddit.com/r/hacking/.rss)
  - [/r/netsec](https://www.reddit.com/r/netsec/.rss)
  - [/r/HowToHack](https://www.reddit.com/r/HowToHack/.rss)
- News
  - [blackMORE Ops](https://www.blackmoreops.com/feed)
  - [CyberPunk](http://feeds.feedburner.com/n0where)
  - [fossBytes](http://feeds.feedburner.com/Fossbytes)
  - [Security Bloggers Network](http://securitybloggersnetwork.com/feed)
  - [The Register - Security](http://www.theregister.co.uk/security/headlines.atom)
  - [Security.NL](https://www.security.nl/rss/headlines.xml)
- Organisations
  - [SANS Information Security Reading Room](https://www.sans.org/reading-room/rss)
  - [The Akamai Blog](http://feeds.feedburner.com/TheAkamaiBlog)
- Tools
  - [Nmap Announce](http://seclists.org/rss/nmap-announce.rss)
  - [Wireshark](http://seclists.org/rss/wireshark.rss)
- Vulnerability feeds
  - [Bugtraq](http://seclists.org/rss/bugtraq.rss)
  - [Exploit-DB Updates](https://www.exploit-db.com/rss.xml)
  - [Full Disclosure](http://seclists.org/rss/fulldisclosure.rss)
  - [National Vulnerability Database](https://nvd.nist.gov/download/nvd-rss.xml)
  - [Open Source Security](http://seclists.org/rss/oss-sec.rss)
  - [Files ≈ Packet Storm](https://rss.packetstormsecurity.com/files)

## Thanks

These are some of the sources that I got lists from
- https://blog.bugcrowd.com/discovering-subdomains

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Rory Breuk](https://twitter.com/mr_breaker_) has waived all copyright and related or neighboring rights to this work.
