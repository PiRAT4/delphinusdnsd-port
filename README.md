# Delphinus DNS
Delphinus DNS is a non-caching, non-recursing DNS server that serves
authoritative answers for A, AAAA, CNAME, DNSKEY, DS, MX, NAPTR, NS,
NSEC3, NSEC3PARAM, PTR, RRSIG, SOA, SRV, SSHFP, TLSA, and TXT resource
records.

For more information please visit Delphinus DNS's [homepage](https://delphinusdns.org).

## Installation

```shell
$ doas pkg_add delphinusdnsd
```

## Thanks

* [Peter J. Philipp](http://delphinusdns.org/credits.html) for developing the software in the first place and for his patience answering all my questions
* [Brian Callahan](https://briancallahan.net) for sharing this awesome [guide](https://www.youtube.com/watch?v=z_TnemhzbXQ) on how to port software for OpenBSD
* gonzalo for helping with post-install instructions
