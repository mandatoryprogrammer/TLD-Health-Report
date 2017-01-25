# `cw.` TLD Health Check Results

Final scan status: **error** 

Original RIPE scan results URL: http://dnscheck.ripe.net/?time=1485323428&id=15767281&view=basic&test=standard

## Delegation Scan

**Errors**:

* Inconsistent glue for name server engine2.una.cw. The address of a name server differed between the child and the parent.  This is a configuration error and should be corrected as soon as possible.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

## Nameserver Scan

### `cw.cctld.authdns.ripe.net`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `engine0.una.cw`

**Errors**:

No errors to display.

**Warnings**:

* Reverse for 200.26.199.99 points to an unknown host name (engine0.una.an). The PTR record for the address points to an unknown host name.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `engine2.una.cw`

**Errors**:

* Name server engine2.una.cw (190.112.254.246) does not answer queries over UDP. The name server failed to answer queries sent over UDP.  This is probably due to the name server not correctly set up or due to misconfigured filtering in a firewall.
* Name server engine2.una.cw (190.112.254.246) does not answer queries over TCP. The name server failed to answer queries sent over TCP.  This is probably due to the name server not correctly set up or due to misconfgured filtering in a firewall. It is a rather common misconception that DNS does not need TCP unless they provide zone transfers - perhaps the name server administrator is not aware that TCP usually is a requirement.

**Warnings**:

* Could not find reverse address for 190.112.254.246 (246.254.112.190.in-addr.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `kadushi.curinfo.cw`

**Errors**:

No errors to display.

**Warnings**:

* Reverse for 65.208.122.63 points to an unknown host name (kadushi.curinfo.an). The PTR record for the address points to an unknown host name.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns0.ja.net`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns01-server.curinfo.cw`

**Errors**:

No errors to display.

**Warnings**:

* Reverse for 65.208.122.36 points to an unknown host name (ns01-server.curinfo.an). The PTR record for the address points to an unknown host name.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns1.uoc.cw`

**Errors**:

* Name server ns1.uoc.cw (198.93.177.21) does not answer queries over UDP. The name server failed to answer queries sent over UDP.  This is probably due to the name server not correctly set up or due to misconfigured filtering in a firewall.
* Name server ns1.uoc.cw (198.93.177.21) does not answer queries over TCP. The name server failed to answer queries sent over TCP.  This is probably due to the name server not correctly set up or due to misconfgured filtering in a firewall. It is a rather common misconception that DNS does not need TCP unless they provide zone transfers - perhaps the name server administrator is not aware that TCP usually is a requirement.

**Warnings**:

* Reverse for 198.93.177.21 points to an unknown host name (engine1.una.net). The PTR record for the address points to an unknown host name.

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

* The listed nameservers for cw. all report the same set of nameservers.

**Statuses**:

No statuses to display.

## Soa Scan

**Errors**:

No errors to display.

**Warnings**:

* Reverse for 65.208.122.36 points to an unknown host name (ns01-server.curinfo.an). The PTR record for the address points to an unknown host name.

**Notices**:

* SOA refresh for cw. too small (10800) - recommended >= 14400. SOA refresh decides how often a secondary name server should check the primary name server for zone updates.

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
* DNS lookup error (connection failed).

**Statuses**:

No statuses to display.


---
