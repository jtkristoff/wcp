# DNS Hijacking Threats and Countermeasures

The domain name system (DNS) starts most forms of communications on the
Internet.  Whether browsing the web, sending email, or when clicking on
a recently installed game application, a DNS query and response pair
help the user to locate and make use of almost all Internet services.
The DNS specifications, compared to many other standards, are loosely
defined and have lacked any serious, widely deployed, built-in security
mechanisms such as data encryption or authentication.  DNSSEC, a set of
security extensions to the DNS, has been under development and
deployment for years to add data authentication, but deployment is still
relatively sparse.  Yet, DNS still largely works as expected most of the
time, even though its weaknesses are not only well known, but
occasionally taken advantage of.  The following is a sample of scholarly
papers that could form the basis of a written critique and presentation
(WCP) in the field of DNS hijacking to satisfy UIC Computer Science PhD
degree requirements.

* Steve Bellovin: [Using the Domain Name System for System Break-ins](https://www.usenix.org/legacy/publications/library/proceedings/security95/full_papers/bellovin.pdf).  Proceedings of the Fifth USENIX UNIX Security Symposium 1995.

* Haixin Duan, Nicholas Weaver, Zongxu Zhao, Meng Hu, Jinjin Liang, Kang Li, Vern Paxson: [Hold-On: Protecting Against On-Path DNS Poisoning](http://www.icsi.berkeley.edu/pubs/networking/dnspoisoning12.pdf).  Workshop on Securing and Trusting Internet Names, SATIN 2012.

* Kyle Schomp, Tom Callahan, Michael Rabinovich, Mark Allman: [Assessing DNS Vulnerability to Record Injection](https://link.springer.com/chapter/10.1007/978-3-319-04918-2_21).  Passive and Active Measurement Conference, March 2014.

* Markus Brandt, Tianxiang Dai, Amit Klein, Haya Shulman, Michael Waidner: [Domain Validation++ For MitM-Resilient PKI](https://dl.acm.org/citation.cfm?id=3243790).  Proceedings of the 2018 ACM SIGSAC Conference on Computer and Communications Security.
