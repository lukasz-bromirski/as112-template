# AS 112 config templates

Łukasz Bromirski

Based on [as112.net](https://as112.net/), [RFC 6305](https://www.rfc-editor.org/rfc/rfc6305), [RFC 7534](https://www.rfc-editor.org/rfc/rfc7534), [RFC 7535](https://www.rfc-editor.org/rfc/rfc7535) and [draft-ietf-dnssd-srp-25](https://datatracker.ietf.org/doc/html/draft-ietf-dnssd-srp-25).

* [named](named/) - for [BIND](https://www.isc.org/bind/) 9.x
* [bird](bird/) - for [BIRD](https://bird.network.cz/) 2.x
* [nsd](nsd/) - for [NSD](https://www.nlnetlabs.nl/projects/nsd/about/) 4.x
* [FreeBSD](FreeBSD/) - for [FreeBSD](https://www.freebsd.org/) 12.x-14.x (only cloned interface, and assumes you'd enable forwarding for IPv4 and IPv6 to get traffic across)
