# `cm.` TLD Health Check Results

Final scan status: **error** 

Original RIPE scan results URL: http://dnscheck.ripe.net/?time=1485323900&id=15767334&view=basic&test=standard

## Delegation Scan

**Errors**:

* Superfluous name server listed at parent: sanaga.camnet.cm A name server listed at the parent, but not at the child, was found. This is most likely an administrative error. You should update the parent to match the name servers at the child as soon as possible.
* Inconsistent glue for name server lom.camnet.cm. The address of a name server differed between the child and the parent.  This is a configuration error and should be corrected as soon as possible.

**Warnings**:

* The smallest referral packet we could build for cm. was 515 bytes, which requires EDNS0 and will not work with old resolvers.

**Notices**:

* Additional name server listed at child: benoue.camnet.cm A name server listed at the child, but not at the parent, was found. This is most likely a configuration error, but there are sometimes reasons for setting up a zone this way.
* Additional name server listed at child: mbam.camnet.cm A name server listed at the child, but not at the parent, was found. This is most likely a configuration error, but there are sometimes reasons for setting up a zone this way.
* Additional name server listed at child: ns1.nic.cm A name server listed at the child, but not at the parent, was found. This is most likely a configuration error, but there are sometimes reasons for setting up a zone this way.
* Additional name server listed at child: ns2.nic.cm A name server listed at the child, but not at the parent, was found. This is most likely a configuration error, but there are sometimes reasons for setting up a zone this way.
* Additional name server listed at child: phloem.uoregon.edu A name server listed at the child, but not at the parent, was found. This is most likely a configuration error, but there are sometimes reasons for setting up a zone this way.

**Statuses**:

No statuses to display.

## Nameserver Scan

### `auth02.ns.uu.net`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `benoue.camnet.cm`

**Errors**:

* Name server benoue.camnet.cm (195.24.208.2) does not answer queries over UDP. The name server failed to answer queries sent over UDP.  This is probably due to the name server not correctly set up or due to misconfigured filtering in a firewall.
* Name server benoue.camnet.cm (195.24.208.2) does not answer queries over TCP. The name server failed to answer queries sent over TCP.  This is probably due to the name server not correctly set up or due to misconfgured filtering in a firewall. It is a rather common misconception that DNS does not need TCP unless they provide zone transfers - perhaps the name server administrator is not aware that TCP usually is a requirement.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `cm.cctld.authdns.ripe.net`

**Errors**:

* Name server cm.cctld.authdns.ripe.net (193.0.9.68) not authoritative for cm.. The name server does not answer authoritatively to queries for the tested domain.  This is probably due to misconfiguration where the name server is not set up to serve the tested domain.
* Name server cm.cctld.authdns.ripe.net (2001:67c:e0:0:0:0:0:68) not authoritative for cm.. The name server does not answer authoritatively to queries for the tested domain.  This is probably due to misconfiguration where the name server is not set up to serve the tested domain.

**Warnings**:

* Nameserver at 193.0.9.68 is not authoritative over UDP.
* Nameserver at 2001:67c:e0:0:0:0:0:68 is not authoritative over UDP.

**Notices**:

* No answer received from 193.0.9.68 when querying for cm./IN/SOA.
* No answer received from 193.0.9.68 when querying for cm./IN/SOA.
* No answer received from 193.0.9.68 when querying for cm./SOA/IN.
* No answer received from 193.0.9.68 when querying for cm./IN/SOA.
* No answer received from 2001:67c:e0:0:0:0:0:68 when querying for cm./IN/SOA.
* No answer received from 2001:67c:e0:0:0:0:0:68 when querying for cm./IN/SOA.
* No answer received from 2001:67c:e0:0:0:0:0:68 when querying for cm./SOA/IN.
* No answer received from 2001:67c:e0:0:0:0:0:68 when querying for cm./IN/SOA.

**Statuses**:

No statuses to display.

### `kim.camnet.cm`

**Errors**:

* Name server kim.camnet.cm (195.24.192.35) does not answer queries over TCP. The name server failed to answer queries sent over TCP.  This is probably due to the name server not correctly set up or due to misconfgured filtering in a firewall. It is a rather common misconception that DNS does not need TCP unless they provide zone transfers - perhaps the name server administrator is not aware that TCP usually is a requirement.

**Warnings**:

No warnings to display.

**Notices**:

* DNS lookup error (connection failed).
* DNS lookup error (connection failed).

**Statuses**:

No statuses to display.

### `lom.camnet.cm`

**Errors**:

* Name server lom.camnet.cm (195.24.192.34) does not answer queries over TCP. The name server failed to answer queries sent over TCP.  This is probably due to the name server not correctly set up or due to misconfgured filtering in a firewall. It is a rather common misconception that DNS does not need TCP unless they provide zone transfers - perhaps the name server administrator is not aware that TCP usually is a requirement.

**Warnings**:

No warnings to display.

**Notices**:

* DNS lookup error (connection failed).
* DNS lookup error (connection failed).

**Statuses**:

No statuses to display.

### `mbam.camnet.cm`

**Errors**:

* Name server mbam.camnet.cm (195.24.192.33) does not answer queries over TCP. The name server failed to answer queries sent over TCP.  This is probably due to the name server not correctly set up or due to misconfgured filtering in a firewall. It is a rather common misconception that DNS does not need TCP unless they provide zone transfers - perhaps the name server administrator is not aware that TCP usually is a requirement.

**Warnings**:

No warnings to display.

**Notices**:

* DNS lookup error (connection failed).
* DNS lookup error (connection failed).

**Statuses**:

No statuses to display.

### `ns.itu.ch`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns1.nic.cm`

**Errors**:

* Name server ns1.nic.cm (195.24.205.60) does not answer queries over UDP. The name server failed to answer queries sent over UDP.  This is probably due to the name server not correctly set up or due to misconfigured filtering in a firewall.
* Name server ns1.nic.cm (195.24.205.60) does not answer queries over TCP. The name server failed to answer queries sent over TCP.  This is probably due to the name server not correctly set up or due to misconfgured filtering in a firewall. It is a rather common misconception that DNS does not need TCP unless they provide zone transfers - perhaps the name server administrator is not aware that TCP usually is a requirement.

**Warnings**:

* Could not find reverse address for 195.24.205.60 (60.205.24.195.in-addr.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns2.nic.cm`

**Errors**:

* Name server ns2.nic.cm (195.24.205.61) does not answer queries over UDP. The name server failed to answer queries sent over UDP.  This is probably due to the name server not correctly set up or due to misconfigured filtering in a firewall.
* Name server ns2.nic.cm (195.24.205.61) does not answer queries over TCP. The name server failed to answer queries sent over TCP.  This is probably due to the name server not correctly set up or due to misconfgured filtering in a firewall. It is a rather common misconception that DNS does not need TCP unless they provide zone transfers - perhaps the name server administrator is not aware that TCP usually is a requirement.

**Warnings**:

* Could not find reverse address for 195.24.205.61 (61.205.24.195.in-addr.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `phloem.uoregon.edu`

**Errors**:

* DNS SERVFAIL when querying 128.223.32.35 for SOA
* DNS SERVFAIL when querying 128.223.32.35 for SOA
* DNS SERVFAIL when querying 128.223.32.35 for SOA
* Name server phloem.uoregon.edu (128.223.32.35) not authoritative for cm.. The name server does not answer authoritatively to queries for the tested domain.  This is probably due to misconfiguration where the name server is not set up to serve the tested domain.
* DNS SERVFAIL when querying 2001:468:d01:20:0:0:80df:2023 for SOA
* DNS SERVFAIL when querying 2001:468:d01:20:0:0:80df:2023 for SOA
* DNS SERVFAIL when querying 2001:468:d01:20:0:0:80df:2023 for SOA
* Name server phloem.uoregon.edu (2001:468:d01:20:0:0:80df:2023) not authoritative for cm.. The name server does not answer authoritatively to queries for the tested domain.  This is probably due to misconfiguration where the name server is not set up to serve the tested domain.

**Warnings**:

* Nameserver at 128.223.32.35 is not authoritative over UDP.
* Nameserver at 2001:468:d01:20:0:0:80df:2023 is not authoritative over UDP.

**Notices**:

* No answer received from 128.223.32.35 when querying for cm./SOA/IN.
* No answer received from 2001:468:d01:20:0:0:80df:2023 when querying for cm./SOA/IN.

**Statuses**:

No statuses to display.

### `sanaga.camnet.cm`

**Errors**:

* Name server sanaga.camnet.cm (195.24.192.17) does not answer queries over TCP. The name server failed to answer queries sent over TCP.  This is probably due to the name server not correctly set up or due to misconfgured filtering in a firewall. It is a rather common misconception that DNS does not need TCP unless they provide zone transfers - perhaps the name server administrator is not aware that TCP usually is a requirement.

**Warnings**:

No warnings to display.

**Notices**:

* DNS lookup error (connection failed).
* DNS lookup error (connection failed).

**Statuses**:

No statuses to display.

## Consistency Scan

**Errors**:

* DNS SERVFAIL when querying 2001:468:d01:20:0:0:80df:2023 for SOA
* DNS SERVFAIL when querying 128.223.32.35 for SOA

**Warnings**:

* 3 different serials found. The SOA serial is not the same on all name servers. This is usually due to misconfiguration, but can sometimes be the result of slow zone propagation to secondary name servers.
* The listed nameservers for cm. does not all report the same set of nameservers.

**Notices**:

* No answer received from 193.0.9.68 when querying for cm./IN/SOA.
* No answer received from 2001:67c:e0:0:0:0:0:68 when querying for cm./IN/SOA.
* No answer received from 193.0.9.68 when querying for cm./IN/NS.
* No answer received from 2001:67c:e0:0:0:0:0:68 when querying for cm./IN/NS.

**Statuses**:

No statuses to display.

## Soa Scan

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 195.24.205.60 (60.205.24.195.in-addr.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

## Connectivity Scan

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

## Dnssec Scan

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

* DNS lookup error (connection failed).
* No answer received from 193.0.9.68 when querying for cm./IN/DNSKEY.
* DNS lookup error (connection failed).
* No answer received from 128.223.32.35 when querying for cm./IN/DNSKEY.
* DNS lookup error (connection failed).
* DNS lookup error (connection failed).
* DNS lookup error (connection failed).
* DNS lookup error (connection failed).
* No answer received from 2001:468:d01:20:0:0:80df:2023 when querying for cm./IN/DNSKEY.
* No answer received from 2001:67c:e0:0:0:0:0:68 when querying for cm./IN/DNSKEY.

**Statuses**:

No statuses to display.


---
