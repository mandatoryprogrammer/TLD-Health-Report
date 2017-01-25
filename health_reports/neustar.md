# `neustar.` TLD Health Check Results

Final scan status: **warning** 

Original RIPE scan results URL: http://dnscheck.ripe.net/?time=1485320441&id=15766637&view=basic&test=standard

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

### `ns1.dns.nic.neustar`

**Errors**:

No errors to display.

**Warnings**:

* Reverse for 204.74.112.250 points to an unknown host name (ns1.gtld.neustar). The PTR record for the address points to an unknown host name.
* Could not find reverse address for 2001:502:d399:0:0:0:0:250 (0.5.2.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.9.9.3.d.2.0.5.0.1.0.0.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns2.dns.nic.neustar`

**Errors**:

No errors to display.

**Warnings**:

* Reverse for 204.74.113.250 points to an unknown host name (ns2.gtld.neustar). The PTR record for the address points to an unknown host name.
* Could not find reverse address for 2610:a1:1007:0:0:0:0:250 (0.5.2.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.7.0.0.1.1.a.0.0.0.1.6.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns3.dns.nic.neustar`

**Errors**:

No errors to display.

**Warnings**:

* Reverse for 199.7.66.250 points to an unknown host name (ns3.gtld.neustar). The PTR record for the address points to an unknown host name.
* Could not find reverse address for 2610:a1:1008:0:0:0:0:250 (0.5.2.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.8.0.0.1.1.a.0.0.0.1.6.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns4.dns.nic.neustar`

**Errors**:

No errors to display.

**Warnings**:

* Reverse for 199.7.67.250 points to an unknown host name (ns4.gtld.neustar). The PTR record for the address points to an unknown host name.
* Could not find reverse address for 2001:502:100e:0:0:0:0:250 (0.5.2.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.e.0.0.1.2.0.5.0.1.0.0.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns5.dns.nic.neustar`

**Errors**:

No errors to display.

**Warnings**:

* Reverse for 192.100.59.250 points to an unknown host name (ns5.gtld.neustar). The PTR record for the address points to an unknown host name.
* Could not find reverse address for 2610:a1:1013:0:0:0:0:250 (0.5.2.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.3.1.0.1.1.a.0.0.0.1.6.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns6.dns.nic.neustar`

**Errors**:

No errors to display.

**Warnings**:

* Reverse for 198.133.199.250 points to an unknown host name (ns6.gtld.neustar). The PTR record for the address points to an unknown host name.
* Could not find reverse address for 2610:a1:1021:0:0:0:0:250 (0.5.2.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.1.2.0.1.1.a.0.0.0.1.6.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

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

* The listed nameservers for neustar. all report the same set of nameservers.

**Statuses**:

No statuses to display.

## Soa Scan

**Errors**:

No errors to display.

**Warnings**:

* Reverse for 204.74.112.250 points to an unknown host name (ns1.gtld.neustar). The PTR record for the address points to an unknown host name.
* Could not find reverse address for 2001:502:d399:0:0:0:0:250 (0.5.2.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.9.9.3.d.2.0.5.0.1.0.0.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

* SOA refresh for neustar. too small (900) - recommended >= 14400. SOA refresh decides how often a secondary name server should check the primary name server for zone updates.
* SOA refresh for neustar. lower than retry (900 vs 900). The retry value is the amount of time secondary name servers will wait before contacting the primary name server again if the last attempt failed.  If the refresh value is lower than the retry value, it's useless.
* SOA retry for neustar. too small (900) - recommended >= 3600. The retry value is the amount of time secondary name servers will wait before contacting the primary name server again if the last attempt failed. If the retry value is too small, secondary name servers will retry too frequently.

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

* Parent DS(neustar.) does not refer to secure entry point (SEP) at child: DS(neustar./8/1/10205) The DS RRset refers to a DNSKEY at the child, but the key is not marked as a secure entry point.
* Parent DS(neustar.) does not refer to secure entry point (SEP) at child: DS(neustar./8/2/10205) The DS RRset refers to a DNSKEY at the child, but the key is not marked as a secure entry point.

**Statuses**:

No statuses to display.


---
