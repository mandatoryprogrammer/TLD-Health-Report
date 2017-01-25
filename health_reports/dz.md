# `dz.` TLD Health Check Results

Final scan status: **error** 

Original RIPE scan results URL: http://dnscheck.ripe.net/?time=1485323113&id=15767202&view=basic&test=standard

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

### `ns-dz.afrinic.net`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns1.nic.dz`

**Errors**:

* Name server ns1.nic.dz (2001:4340:1030:2:0:0:0:2) does not answer queries over UDP. The name server failed to answer queries sent over UDP.  This is probably due to the name server not correctly set up or due to misconfigured filtering in a firewall.
* Name server ns1.nic.dz (2001:4340:1030:2:0:0:0:2) does not answer queries over TCP. The name server failed to answer queries sent over TCP.  This is probably due to the name server not correctly set up or due to misconfgured filtering in a firewall. It is a rather common misconception that DNS does not need TCP unless they provide zone transfers - perhaps the name server administrator is not aware that TCP usually is a requirement.

**Warnings**:

* Could not find reverse address for 2001:4340:1030:2:0:0:0:2 (2.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.2.0.0.0.0.3.0.1.0.4.3.4.1.0.0.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns2.nic.dz`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns3.nic.fr`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns4.nic.dz`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns5.nic.dz`

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

* 2 different serials found. The SOA serial is not the same on all name servers. This is usually due to misconfiguration, but can sometimes be the result of slow zone propagation to secondary name servers.

**Notices**:

* The listed nameservers for dz. all report the same set of nameservers.

**Statuses**:

No statuses to display.

## Soa Scan

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 2001:4340:1030:2:0:0:0:2 (2.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.2.0.0.0.0.3.0.1.0.4.3.4.1.0.0.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

* SOA refresh for dz. too small (10800) - recommended >= 14400. SOA refresh decides how often a secondary name server should check the primary name server for zone updates.
* SOA minimum for dz. too large (432000) - recommended <= 86400. The SOA minimum is used to tell caching resolvers how long they may cache negative answers. If the value is too large, negative caching will be to aggressive.

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
