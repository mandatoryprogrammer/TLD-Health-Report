# `fm.` TLD Health Check Results

Final scan status: **warning** 

Original RIPE scan results URL: http://dnscheck.ripe.net/?time=1485322524&id=15767109&view=basic&test=standard

## Delegation Scan

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

* DNS lookup error (SERVFAIL).
* DNS lookup error (SERVFAIL).
* DNS lookup error (SERVFAIL).
* DNS lookup error (SERVFAIL).
* DNS lookup error (SERVFAIL).
* DNS lookup error (SERVFAIL).
* DNS lookup error (SERVFAIL).
* DNS lookup error (SERVFAIL).
* DNS lookup error (SERVFAIL).
* DNS lookup error (SERVFAIL).
* DNS lookup error (SERVFAIL).
* DNS lookup error (SERVFAIL).

**Statuses**:

No statuses to display.

## Nameserver Scan

### `tld1.ultradns.net`

**Errors**:

No errors to display.

**Warnings**:

* Reverse for 2001:502:d399:0:0:0:0:1 points to an unknown host name (tld1ipv6.ultradns.net). The PTR record for the address points to an unknown host name.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `tld2.ultradns.net`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `tld3.ultradns.org`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `tld4.ultradns.org`

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 2001:502:100e:0:0:0:0:1 (1.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.e.0.0.1.2.0.5.0.1.0.0.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `tld5.ultradns.info`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `tld6.ultradns.co.uk`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

## Consistency Scan

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

* The listed nameservers for fm. all report the same set of nameservers.

**Statuses**:

No statuses to display.

## Soa Scan

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 193.105.170.150 (150.170.105.193.in-addr.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).
* Could not find reverse address for 2001:67c:2630:0:0:0:1701:150 (0.5.1.0.1.0.7.1.0.0.0.0.0.0.0.0.0.0.0.0.0.3.6.2.c.7.6.0.1.0.0.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

* SOA MNAME for fm. (ns0.centralnic.net) not listed as NS. The name server listed as the SOA MNAME is not listed as a name server.
* SOA refresh for fm. too small (900) - recommended >= 14400. SOA refresh decides how often a secondary name server should check the primary name server for zone updates.
* SOA retry for fm. too small (300) - recommended >= 3600. The retry value is the amount of time secondary name servers will wait before contacting the primary name server again if the last attempt failed. If the retry value is too small, secondary name servers will retry too frequently.

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

* Broken chain of trust for fm. - DNSKEY found at child, but no DS was found at parent. The child seems to use DNSSEC, but the parent has no secure delegation.  The chain of trust between the parent and the child is broken and validating resolvers will not be able to validate answers from the child.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.


---
