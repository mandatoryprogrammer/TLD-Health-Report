# `in.` TLD Health Check Results

Final scan status: **warning** 

Original RIPE scan results URL: http://dnscheck.ripe.net/?time=1485321773&id=15766910&view=basic&test=standard

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

### `a0.in.afilias-nst.info`

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 2001:500:29:0:0:0:0:1 (1.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.9.2.0.0.0.0.5.0.1.0.0.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `a1.in.afilias-nst.in`

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 115.249.164.142 (142.164.249.115.in-addr.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).
* Could not find reverse address for 2001:4528:fff:13:0:0:0:142 (2.4.1.0.0.0.0.0.0.0.0.0.0.0.0.0.3.1.0.0.f.f.f.0.8.2.5.4.1.0.0.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `a2.in.afilias-nst.info`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `b0.in.afilias-nst.org`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `b1.in.afilias-nst.in`

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 180.179.215.70 (70.215.179.180.in-addr.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).
* Could not find reverse address for 2401:8800:411:8:0:0:0:70 (0.7.0.0.0.0.0.0.0.0.0.0.0.0.0.0.8.0.0.0.1.1.4.0.0.0.8.8.1.0.4.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `b2.in.afilias-nst.org`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `c0.in.afilias-nst.info`

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

* The listed nameservers for in. all report the same set of nameservers.

**Statuses**:

No statuses to display.

## Soa Scan

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

* SOA MNAME for in. (a0.cctld.afilias-nst.info) not listed as NS. The name server listed as the SOA MNAME is not listed as a name server.
* SOA TTL for in. too small (900) - recommended >= 3600. The smaller the SOA TTL value, the more often resolvers need to requery for SOA record.
* SOA refresh for in. too small (600) - recommended >= 14400. SOA refresh decides how often a secondary name server should check the primary name server for zone updates.
* SOA refresh for in. lower than retry (600 vs 900). The retry value is the amount of time secondary name servers will wait before contacting the primary name server again if the last attempt failed.  If the refresh value is lower than the retry value, it's useless.
* SOA retry for in. too small (900) - recommended >= 3600. The retry value is the amount of time secondary name servers will wait before contacting the primary name server again if the last attempt failed. If the retry value is too small, secondary name servers will retry too frequently.

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

No notices to display.

**Statuses**:

No statuses to display.


---
