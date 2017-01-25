# `la.` TLD Health Check Results

Final scan status: **error** 

Original RIPE scan results URL: http://dnscheck.ripe.net/?time=1485321070&id=15766810&view=basic&test=standard

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

### `ns1.nic.la`

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 185.24.64.15 (15.64.24.185.in-addr.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).
* Could not find reverse address for 2a04:2b00:13cc:0:0:0:1:15 (5.1.0.0.1.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.c.c.3.1.0.0.b.2.4.0.a.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns2.nic.la`

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 194.169.218.14 (14.218.169.194.in-addr.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).
* Could not find reverse address for 2001:67c:13cc:0:0:0:1:14 (4.1.0.0.1.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.c.c.3.1.c.7.6.0.1.0.0.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns3.nic.la`

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 185.24.64.14 (14.64.24.185.in-addr.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).
* Could not find reverse address for 2a04:2b00:13cc:0:0:0:1:14 (4.1.0.0.1.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.c.c.3.1.0.0.b.2.4.0.a.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns4.nic.la`

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 194.169.218.15 (15.218.169.194.in-addr.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).
* Could not find reverse address for 2001:67c:13cc:0:0:0:1:15 (5.1.0.0.1.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.c.c.3.1.c.7.6.0.1.0.0.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

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

* The listed nameservers for la. all report the same set of nameservers.

**Statuses**:

No statuses to display.

## Soa Scan

**Errors**:

* DNS SERVFAIL when querying 202.9.76.53 for SOA

**Warnings**:

* Could not find reverse address for 202.9.76.53 (53.76.9.202.in-addr.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).
* Nameserver at 202.9.76.53 is not authoritative over UDP.
* SOA MNAME for la. (ns0.nic.la) is not authoritative. The name server listed as the original or primary source of data for this zone does not answer authoriatively.  This is probably due to misconfiguration; perhaps the SOA MNAME is not set up as a name server for the zone.

**Notices**:

* SOA MNAME for la. (ns0.nic.la) not listed as NS. The name server listed as the SOA MNAME is not listed as a name server.
* SOA refresh for la. too small (900) - recommended >= 14400. SOA refresh decides how often a secondary name server should check the primary name server for zone updates.
* SOA refresh for la. lower than retry (900 vs 1800). The retry value is the amount of time secondary name servers will wait before contacting the primary name server again if the last attempt failed.  If the refresh value is lower than the retry value, it's useless.
* SOA retry for la. too small (1800) - recommended >= 3600. The retry value is the amount of time secondary name servers will wait before contacting the primary name server again if the last attempt failed. If the retry value is too small, secondary name servers will retry too frequently.

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

* NSEC3 for la. is set to use 150 iterations, which is higher than the limit of 100.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.


---
