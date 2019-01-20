# The RPKI and Route Origin Validation: Advances in Deployment and Measurement

As one of the most critical Internet infrastructure subsystems deployed on the
Internet, BGP inter-domain routing is of utmost importance to modern online
communications.  Consequently the security, stability, and trustworthiness of
this system has been under near constant evaluation, attracting a wide range of
research attention.  Ensuring distributed routing information is both authentic
and correct, a series of specifications in the IETF Secure Inter-Domain Routing
working group arose to enable authentication of BGP routing information.  The
Resource Public Key Infrastructure (RPKI) is a system that enables route origin
validation (ROV) and AS path validation (also known as BGPsec) .  Deployment of
RPKI systems has begun.  Meanwhile some networks are beginning to sign routes
and perform ROV in production networks.  Researchers are actively conducting
experiments that both measure and encourage deployment of these secure routing
extensions.  The following are a short list of scholarly papers that could form
the basis of a written critique and presentation (WCP) on RPKI and ROV to
satisfy UIC Computer Science PhD degree requirements.


## Primary Comparative Sources:

* Gilad, Y, Cohen A, Herzberg A, Schapira M, Shulman H.  [Are We There Yet? On RPKI's Deployment and Security](https://www.ndss-symposium.org/wp-content/uploads/sites/25/2017/09/ndss2017_06A-3_Gilad_paper.pdf).  Network and Distributed Security Symposium ( NDSS) 2017.

* Reuter A, Bush R, Cunha I, Katz-Bassett E, Schmidt T, Wählisch M.  [Towards a Rigorous Methodology for Measuring Adoption of RPKI Route Validation and Filtering](https://dl.acm.org/citation.cfm?id=3211856).  ACM SIGCOMM Computer Communication Review 48, no. 1, pp. 19-27, 2018.

* Hlavacek T, Herzberg A, Shulman H, Waidner M.  [Practical Experience: Methodologies for Measuring Route Origin Validation](https://ieeexplore.ieee.org/abstract/document/8416522).  48th Annual IEEE/IFIP International Conference on Dependable Systems and Networks (DSN) 2018.


## Secondary Sources:

* Lychev R, Goldberg S, Schapira M.  [BGP Security in Partial Deployment: Is the Juice Worth the Squeeze?](https://dl.acm.org/citation.cfm?id=2486010).  ACM SIGCOMM 2013.

* Heilman E, Cooper D, Reyzin L, Goldberg S.  [From the Consent of the Routed: Improving the Transparency of the RPKI](https://dl.acm.org/citation.cfm?id=2626293).  ACM SIGCOMM 2014.

* Iamartino D, Pelsser C, Bush R.  [Measuring Bgp Route Origin Registration and Validation](https://link.springer.com/chapter/10.1007/978-3-319-15509-8_3). Passive and Active Network Measurement (PAM) 2015.

* Cohen A, Gilad Y, Herzberg A, Schapira M.  [One Hop for RPKI, One Giant Leap for BGP Security](https://dl.acm.org/citation.cfm?id=2834078). 14th ACM Workshop on Hot Topics in Networks (HOTNETS) 2015.

* Cohen A, Gilad Y, Herzberg A, Schapira M.  [Jumpstarting BGP Security with Path-End Validation](https://dl.acm.org/citation.cfm?id=2934883). ACM SIGCOMM 2016.

* Yoo C, Wishnick D.  [Lowering Legal Barriers to RPKI Adoption](https://papers.ssrn.com/sol3/Papers.cfm?abstract_id=3308619).  U of Penn Law School, Public Law Research Paper 19-02 (2018).

* Gilad Y, Hlavacek T, Herzberg A, Schapira M, Shulman H.  [Perfect is the Enemy of Good: Setting Realistic Goals for BGP Security](www.cs.huji.ac.il/~schapiram/DISCO__HotNets.pdf).  17th ACM Workshop on Hot Topics in Networks (HOTNETS) 2018.


## Normative Sources:

* Lepinski M, Kent S.  [An Infrastructure to Support Secure Internet Routing](https://tools.ietf.org/html/rfc6480).  IETF RFC 6480, Feburary 2012.

* Huston G, Loomans R, Michaelson G.  [A Profile for Resource Certificate Repository Structure](https://tools.ietf.org/html/rfc6481).  IETF RFC 6481, February 2012.

* Lepinski M, Kent S, Kong D.  [A Profile for Route Origin Authorizations (ROAs)](https://tools.ietf.org/html/rfc6482).  IETF RFC 6482, February 2012.

* Huston G, Michaelson G.  [Validation of Route Origination Using the Resource Certificate Public Key Infrastructure (PKI) and Route Origin Authorizations (ROAs)](https://tools.ietf.org/html/rfc6483).  IETF RFC 6483, February 2012.

* Bush R.  [Origin Validation Operation Based on the Resource Public Key Infrastructure (RPKI)](https://tools.ietf.org/html/rfc7115).  IETF RFC 7115 / IETF BCP 185, January 2014.

* Kent S, Chi A.  [Threat Model for BGP Path Security](https://tools.ietf.org/html/rfc7132).  IETF RFC 7132, February 2014.

* Lepinski M, Sriram K.  [BGPsec Protocol Specification](https://tools.ietf.org/html/rfc8205).  IETF RFC 8205, September 2017.

* Bush R.  [BGPsec Operational Considerations](https://tools.ietf.org/html/rfc8207).  IETF RFC 8207 / IETF BCP 211, September 2017.

* Bush R, Austein R.  [The Resource Public Key Infrastructure (RPKI) to Route Protocol, Version 1](https://tools.ietf.org/html/rfc8210).  IETF RFC 8210, September 2017.


## Informative Sources:

* Butler K, Farley T, McDaniel P, Rexford J.  [A Survey of BGP Security Issues and Solutions](https://cise.ufl.edu/~butler/pubs/bgpsurvey.pdf).  Proceedings of the IEEE, Vol. 98, No. 1, January 2010.

* Huston G, Rossi M.  [Securing BGP - A Literature Survey](http://www.potaroo.net/papers/ieee/bgp_survey_2010.pdf).  IEEE Communications Surveys and Tutorials, 2010.

* Huston G, Bush R.  [Securing BGP with BGPsec](http://wattle.apnic.net/papers/isoc/2011-07/bgpsec.pdf).  The Internet Protocol Journal, Vol. 14, No. 2, June 2011.

* Reuter A.  [Measuring the Adoption of RPKI Route Origin Validation: Update](https://ripe76.ripe.net/archives/video/32/).  Lightning talk, RIPE 76, May 2018.

* [Route Security](https://pc.nanog.org/static/published/meetings/NANOG74/1760/20181003_Tzvetanov_Security_Track_Bgp_v1.pdf).  NANOG 74: Security Track, October, 2018.

* Huston, G.  [NANOG 74: Securing the routing system](https://blog.apnic.net/2018/10/19/nanog-74-securing-the-routing-system/).  APNIC blog, October 19, 2018.
