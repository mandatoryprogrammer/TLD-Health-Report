# `ye.` TLD Health Check Results

Final scan status: **error** 

Original RIPE scan results URL: http://dnscheck.ripe.net/?time=1485317604&id=15765994&view=basic&test=standard

## Delegation Scan

**Errors**:

* Superfluous name server listed at parent: sah1.ye A name server listed at the parent, but not at the child, was found. This is most likely an administrative error. You should update the parent to match the name servers at the child as soon as possible.
* Superfluous name server listed at parent: sah2.ye A name server listed at the parent, but not at the child, was found. This is most likely an administrative error. You should update the parent to match the name servers at the child as soon as possible.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

## Nameserver Scan

### `ns1.yemen.net.ye`

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 2a02:2718:4:0:0:0:0:33 (3.3.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.4.0.0.0.8.1.7.2.2.0.a.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns2.yemen.net.ye`

**Errors**:

* Name server ns2.yemen.net.ye (2a02:2718:4:0:0:0:0:34) does not answer queries over UDP. The name server failed to answer queries sent over UDP.  This is probably due to the name server not correctly set up or due to misconfigured filtering in a firewall.
* Name server ns2.yemen.net.ye (2a02:2718:4:0:0:0:0:34) does not answer queries over TCP. The name server failed to answer queries sent over TCP.  This is probably due to the name server not correctly set up or due to misconfgured filtering in a firewall. It is a rather common misconception that DNS does not need TCP unless they provide zone transfers - perhaps the name server administrator is not aware that TCP usually is a requirement.

**Warnings**:

* Could not find reverse address for 2a02:2718:4:0:0:0:0:34 (4.3.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.4.0.0.0.8.1.7.2.2.0.a.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `sah1.ye`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `sah2.ye`

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

* 2 different SOA records found. The other fields in the SOA record are not the same among all name servers. This is usually due to misconfiguration.

**Warnings**:

* 2 different serials found. The SOA serial is not the same on all name servers. This is usually due to misconfiguration, but can sometimes be the result of slow zone propagation to secondary name servers.
* The listed nameservers for ye. does not all report the same set of nameservers.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

## Soa Scan

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 2a02:2718:4:0:0:0:0:33 (3.3.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.4.0.0.0.8.1.7.2.2.0.a.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

* SOA refresh for ye. too small (10800) - recommended >= 14400. SOA refresh decides how often a secondary name server should check the primary name server for zone updates.
* SOA minimum for ye. too small (0) - recommended >= 300. The SOA minimum is used to tell caching resolvers how long they may cache negative answers. If the value is too small, negative caching will not work and resolvers will re-query frequently.

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

* DNS lookup error (connection failed(IPv6 socket failure)).

**Statuses**:

No statuses to display.


---
