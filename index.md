# Cybersecurity incident prediction and discovery data

Everything about the datasets and data sources mentioned in the survey paper "Data-driven cyber security incident prediction".

_ _ _

## Table of contents


* [Research articles by areas](./paper.html)
* Dataset types
  * [Organization reports and datasets](./organization.html)
  * [Executables](executables.html)
  * [Network datasets](network.html)
  * [Synthetic datasets](synthetic.html)
  * [Webpage data](webpage.html)
  * [Social media data](social_media.html)
  
_ _ _

#### Organization reports and datasets


|Related paper         | Dataset          | Introduction |
|:-------------|:------------------|:------|
|[1][2]     | [VERIS community database](http://veriscommunity.net/index.html) | The vocabulary for event recording and incident sharing|
|[1]    | [Hackmageddon](https://www.hackmageddon.com/)      | Information security timelines and statistics  |
|[1] | [Web Hacking Incidents Database](http://projects.webappsec.org/w/page/13246995/Web-Hacking-Incident-Database)|  Recording web hacking incident |
|[3]|[VirusTotal](https://www.virustotal.com/en/faq/)| Analyzing suspicious files and URLs to detect types of malware|
|[3]|[National Software Reference Library (NSRL)](https://www.nist.gov/software-quality-group/national-software-reference-library-nsrl)| Providing a reference data set (RDS) of benign software|
|[3][10]|[Symantec’s Worldwide Intelligence Network Environment (WINE)](https://www.symantec.com/)| Security related data set, including malware, vulnerabilty exploited and so on|
|[17]|[KEIO, WIDE-08 and WIDE-09 traces](http://mawi.wide.ad.jp/mawi/)|Public traffic data repository|
|[10]|[ExploitDB](https://www.exploit-db.com/)|Offensive Security’s Exploit Database Archive|
|[10]|[Microsoft’s Exploitability Index](https://technet.microsoft.com/en-us/security/cc998259.aspx)|Recording exploitability information|



_ _ _





#### Executables


|Related paper         | Dataset          | Introduction|
|:-------------|:------------------|:------|
|[14][18]       |[VirusTotal](https://virustotal.com/)    |Providing executables samples, such as Windows 7 executable samples and Andriod apps|
|[14]        |[Softonic](https://en.softonic.com/)          |App news and reviews, best software downloads and discovery|
|[14]          |[PortableApps](https://portableapps.com/)      |Offering free, commonly used Windows applications that have been specially packaged for portability|
|[14]          |[SourceForge](https://sourceforge.net/)          |Open Source applications and software directory|
|[18]              |[Google Play](https://play.google.com/store)     |Offical app store for the Android operating system|

_ _ _


#### Network datasets


|Related paper         | Dataset          | Introduction|
|:-------------|:------------------|:------|
|[6]| [Open recursive projects](http://openresolverproject.org/)|Open Resolvers pose a significant threat to the global network infrastructure by answering recursive queries for hosts outside of its domain. They are utilized in DNS Amplification attacks and pose a similar threat as those from Smurf attacks commonly seen in the late 1990s. A list of 32 million resolvers that respond to queries in some fashion are collected in this project.|
|[6]|[Verisign. Inc](https://www.verisign.com)|Verisign, Inc. is an American company based in Reston, Virginia, United States that operates a diverse array of network infrastructure, including two of the Internet's thirteen root nameservers, the authoritative registry for the .com, .net, and .name generic top-level domains and the .cc and .tv country-code top-level domains, and the back-end systems for the .jobs, .gov, and .edu top-level domains. Verisign also offers a range of security services, including managed DNS, distributed denial-of-service (DDoS) attack mitigation and cyber-threat reporting.|
|[6]|[Alexa Web Information Service](https://docs.aws.amazon.com/AlexaWebInfoService/latest/index.html)|The Alexa Web Information Service (AWIS) offers a platform for creating innovative Web solutions and services based on Alexa's vast information about web sites, accessible with a web services API. |
|[6][14]|[University of Oregon Route Views Project](http://www.routeviews.org/routeviews/)|The University's Route Views project was originally conceived as a tool for Internet operators to obtain real-time BGP information about the global routing system from the perspectives of several different backbones and locations around the Internet.|
|[6]|[Spoofer project](https://www.caida.org/projects/spoofer/)|The team is developing and supporting open-source software tools to assess and report on the deployment of source address validation (SAV) best anti-spoofing practices|
|[6]|[Zmap](https://github.com/zmap/zmap)|Zmap is a modular, open-source network scanner specifically architected to perform Internet-wide scans and capable of surveying the entire IPv4 address space in under 45 minutes from user space on a single machine, approaching the theoretical maximum speed of gigabit Ethernet.|



- - --


#### Synthetic datasets


|Related paper         | Dataset          | Introduction|
|:-------------|:------------------|:------|
|[5]|Synthetic obfuscation C code|5 obfuscating transformations apply to each of 4608 synthetic C programs with security check. Totally, 23,040 synthetic obfuscation C programs are included in this dataset.|
|[14]|Sythetic network graph|A simple graph represented by four main node patterns: “center of a star”, “edge of a star”, “bridge nodes” (connecting stars/cliques), and “clique nodes”.|


- - -


#### Webpage data 


|Related paper         | Dataset          | Introduction|
|:-------------|:------------------|:------|
|[7]|SEO, porn and gambling webpages| Webpages marked as “evil” by [Baidu](http://www.baidu.com/)|
|[8]|Malicious and benign websites| Malicious websites are collected from [PhishTank blacklists](https://www.phishtank.com) and the “search-redirection attacks” list; benign websites are gathered from [entire.com zone file](entire.com) and validated by multiple reputation blacklists, including [PhishTank blacklists](https://www.phishtank.com), “search-redirection attacks” list, [DNS-BH](http://www.malwaredomains.com), [Google SafeBrowsing](https://code.google.com/apis/safebrowsing/), and [hpHosts blacklists](https://code.google.com/apis/safebrowsing/)|

_ _ _


#### Social media data


|Related paper         | Dataset          | Introduction|
|:-------------|:------------------|:------|
|[10][15]|Tweets crawled from [Twitter](https://twitter.com/)|Twitter is a social media platform which includes from breaking news and entertainment to sports and politics.|
|[13]|User reviews from Google Play|Each review is manually labeled as one or more security-related behaviors (spamming, financial issues, over priviledged permissions and data leakage)|
|[11]|71,000 articles from leading technical blogs| Technical blogs: (1)[Dancho Danchev](https://ddanchev.blogspot.com.au) (2)[Naked Security](https://nakedsecurity.sophos.com) (3)[The hacker news](https://thehackernews.com) (4)[Webroot](http://webroot.com) (5)[Threat Post](https://threatpost.com) (6)[TaoSecurity](https://taosecurity.blogspot.com.au) (7)[Sucuri](https://sucuri.net) (8)[PaloAlto](https://researchcenter.paloaltonetworks.com) (9)[Malwarebytes](https://researchcenter.paloaltonetworks.com) (10)[Hexacorn](http://www.hexacorn.com/blog/)|


_ _ _

