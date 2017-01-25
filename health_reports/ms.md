# `ms.` TLD Health Check Results

Final scan status: **error** 

Original RIPE scan results URL: http://dnscheck.ripe.net/?time=1485320565&id=15766667&view=basic&test=standard

## Delegation Scan

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

## Nameserver Scan

### `a.ms.dyntld.net`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `b.ms.dyntld.net`

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 2001:500:96:0:0:0:0:23 (3.2.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.6.9.0.0.0.0.5.0.1.0.0.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `mnidns1.mninet.ms`

**Errors**:

* Name server mnidns1.mninet.ms (199.7.90.2) does not answer queries over UDP. The name server failed to answer queries sent over UDP.  This is probably due to the name server not correctly set up or due to misconfigured filtering in a firewall.
* Name server mnidns1.mninet.ms (199.7.90.2) does not answer queries over TCP. The name server failed to answer queries sent over TCP.  This is probably due to the name server not correctly set up or due to misconfgured filtering in a firewall. It is a rather common misconception that DNS does not need TCP unless they provide zone transfers - perhaps the name server administrator is not aware that TCP usually is a requirement.

**Warnings**:

* Could not find reverse address for 199.7.90.2 (2.90.7.199.in-addr.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ms-ns.anycast.pch.net`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `phloem.uoregon.edu`

**Errors**:

* DNS SERVFAIL when querying 128.223.32.35 for SOA
* DNS SERVFAIL when querying 128.223.32.35 for SOA
* DNS SERVFAIL when querying 128.223.32.35 for SOA
* Name server phloem.uoregon.edu (128.223.32.35) not authoritative for ms.. The name server does not answer authoritatively to queries for the tested domain.  This is probably due to misconfiguration where the name server is not set up to serve the tested domain.
* DNS SERVFAIL when querying 2001:468:d01:20:0:0:80df:2023 for SOA
* DNS SERVFAIL when querying 2001:468:d01:20:0:0:80df:2023 for SOA
* DNS SERVFAIL when querying 2001:468:d01:20:0:0:80df:2023 for SOA
* Name server phloem.uoregon.edu (2001:468:d01:20:0:0:80df:2023) not authoritative for ms.. The name server does not answer authoritatively to queries for the tested domain.  This is probably due to misconfiguration where the name server is not set up to serve the tested domain.

**Warnings**:

* Nameserver at 128.223.32.35 is not authoritative over UDP.
* Nameserver at 2001:468:d01:20:0:0:80df:2023 is not authoritative over UDP.

**Notices**:

* No answer received from 128.223.32.35 when querying for ms./SOA/IN.
* No answer received from 2001:468:d01:20:0:0:80df:2023 when querying for ms./SOA/IN.

**Statuses**:

No statuses to display.

## Consistency Scan

**Errors**:

* DNS SERVFAIL when querying 2001:468:d01:20:0:0:80df:2023 for SOA
* DNS SERVFAIL when querying 128.223.32.35 for SOA

**Warnings**:

* The listed nameservers for ms. does not all report the same set of nameservers.

**Notices**:

* No answer received from 128.223.32.35 when querying for ms./IN/NS.
* No answer received from 2001:468:d01:20:0:0:80df:2023 when querying for ms./IN/NS.

**Statuses**:

No statuses to display.

## Soa Scan

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 199.7.90.2 (2.90.7.199.in-addr.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

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
* No answer received from 128.223.32.35 when querying for ms./IN/DNSKEY.
* No answer received from 2001:468:d01:20:0:0:80df:2023 when querying for ms./IN/DNSKEY.

**Statuses**:

No statuses to display.


---
