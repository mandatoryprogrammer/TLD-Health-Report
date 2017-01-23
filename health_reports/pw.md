# `pw.` TLD Health Check Results

Final scan status: **error** 

Original RIPE scan results URL: http://dnscheck.ripe.net/?time=1485155084&id=15758276&view=basic&test=standard

## Delegation Scan

**Errors**:

* Inconsistent glue for name server ns3.nic.pw. The address of a name server differed between the child and the parent.  This is a configuration error and should be corrected as soon as possible.
* Inconsistent glue for name server ns3.nic.pw. The address of a name server differed between the child and the parent.  This is a configuration error and should be corrected as soon as possible.
* Inconsistent glue for name server ns4.nic.pw. The address of a name server differed between the child and the parent.  This is a configuration error and should be corrected as soon as possible.
* Inconsistent glue for name server ns4.nic.pw. The address of a name server differed between the child and the parent.  This is a configuration error and should be corrected as soon as possible.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

## Nameserver Scan

### `ns1.nic.pw`

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 194.169.218.12 (12.218.169.194.in-addr.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).
* Could not find reverse address for 2001:67c:13cc:0:0:0:1:12 (2.1.0.0.1.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.c.c.3.1.c.7.6.0.1.0.0.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns2.nic.pw`

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 185.24.64.12 (12.64.24.185.in-addr.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).
* Could not find reverse address for 2a04:2b00:13cc:0:0:0:1:12 (2.1.0.0.1.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.c.c.3.1.0.0.b.2.4.0.a.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns3.nic.pw`

**Errors**:

No errors to display.

**Warnings**:

* Reverse for 185.38.99.11 points to an unknown host name (c.nic.pw). The PTR record for the address points to an unknown host name.
* Could not find reverse address for 2a02:e180:3:0:0:0:0:11 (1.1.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.3.0.0.0.0.8.1.e.2.0.a.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns4.nic.pw`

**Errors**:

No errors to display.

**Warnings**:

* Reverse for 108.59.161.11 points to an unknown host name (d.nic.pw). The PTR record for the address points to an unknown host name.
* Could not find reverse address for 2a02:e180:4:0:0:0:0:11 (1.1.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.4.0.0.0.0.8.1.e.2.0.a.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

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

* The listed nameservers for pw. all report the same set of nameservers.

**Statuses**:

No statuses to display.

## Soa Scan

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 193.105.170.150 (150.170.105.193.in-addr.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).
* Could not find reverse address for 2001:67c:2630:0:0:0:1701:150 (0.5.1.0.1.0.7.1.0.0.0.0.0.0.0.0.0.0.0.0.0.3.6.2.c.7.6.0.1.0.0.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

* SOA MNAME for pw. (ns0.centralnic.net) not listed as NS. The name server listed as the SOA MNAME is not listed as a name server.
* SOA refresh for pw. too small (900) - recommended >= 14400. SOA refresh decides how often a secondary name server should check the primary name server for zone updates.
* SOA refresh for pw. lower than retry (900 vs 1800). The retry value is the amount of time secondary name servers will wait before contacting the primary name server again if the last attempt failed.  If the refresh value is lower than the retry value, it's useless.
* SOA retry for pw. too small (1800) - recommended >= 3600. The retry value is the amount of time secondary name servers will wait before contacting the primary name server again if the last attempt failed. If the retry value is too small, secondary name servers will retry too frequently.

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
