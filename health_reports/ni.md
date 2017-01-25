# `ni.` TLD Health Check Results

Final scan status: **error** 

Original RIPE scan results URL: http://dnscheck.ripe.net/?time=1485320400&id=15766625&view=basic&test=standard

## Delegation Scan

**Errors**:

* Superfluous name server listed at parent: ns.ibw.com.ni A name server listed at the parent, but not at the child, was found. This is most likely an administrative error. You should update the parent to match the name servers at the child as soon as possible.
* Superfluous name server listed at parent: ns.tmx.com.ni A name server listed at the parent, but not at the child, was found. This is most likely an administrative error. You should update the parent to match the name servers at the child as soon as possible.
* Asking for the address for ns.ibw.com.ni resulted in an error of type servfail.
* Asking for the address for ns.tmx.com.ni resulted in an error of type servfail.

**Warnings**:

No warnings to display.

**Notices**:

* Additional name server listed at child: dns.nic.cr A name server listed at the child, but not at the parent, was found. This is most likely a configuration error, but there are sometimes reasons for setting up a zone this way.
* Too few IPv6 name servers (1). Only one IPv6 name server was found for the zone. You should always have at least two IPv6 name servers for a zone to be able to handle transient connectivity problems.
* DNS lookup error (SERVFAIL).
* DNS lookup error (SERVFAIL).

**Statuses**:

No statuses to display.

## Nameserver Scan

### `dns.nic.cr`

**Errors**:

* Name server dns.nic.cr (200.107.82.100) does not answer queries over UDP. The name server failed to answer queries sent over UDP.  This is probably due to the name server not correctly set up or due to misconfigured filtering in a firewall.
* Name server dns.nic.cr (200.107.82.100) does not answer queries over TCP. The name server failed to answer queries sent over TCP.  This is probably due to the name server not correctly set up or due to misconfgured filtering in a firewall. It is a rather common misconception that DNS does not need TCP unless they provide zone transfers - perhaps the name server administrator is not aware that TCP usually is a requirement.
* DNS SERVFAIL when querying 2001:13c7:7004:1:0:0:0:d100 for SOA
* DNS SERVFAIL when querying 2001:13c7:7004:1:0:0:0:d100 for SOA
* DNS SERVFAIL when querying 2001:13c7:7004:1:0:0:0:d100 for SOA
* Name server dns.nic.cr (2001:13c7:7004:1:0:0:0:d100) not authoritative for ni.. The name server does not answer authoritatively to queries for the tested domain.  This is probably due to misconfiguration where the name server is not set up to serve the tested domain.

**Warnings**:

* Nameserver at 2001:13c7:7004:1:0:0:0:d100 is not authoritative over UDP.

**Notices**:

* No answer received from 2001:13c7:7004:1:0:0:0:d100 when querying for ni./SOA/IN.

**Statuses**:

No statuses to display.

### `ns.cr`

**Errors**:

* Name server ns.cr (163.178.8.2) does not answer queries over UDP. The name server failed to answer queries sent over UDP.  This is probably due to the name server not correctly set up or due to misconfigured filtering in a firewall.
* Name server ns.cr (163.178.8.2) does not answer queries over TCP. The name server failed to answer queries sent over TCP.  This is probably due to the name server not correctly set up or due to misconfgured filtering in a firewall. It is a rather common misconception that DNS does not need TCP unless they provide zone transfers - perhaps the name server administrator is not aware that TCP usually is a requirement.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns.ideay.net.ni`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns.ni`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns.uu.net`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns2.ni`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns.ibw.com.ni`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns.tmx.com.ni`

**Errors**:

* Name server ns.tmx.com.ni (200.62.64.1) not authoritative for ni.. The name server does not answer authoritatively to queries for the tested domain.  This is probably due to misconfiguration where the name server is not set up to serve the tested domain.

**Warnings**:

* Nameserver at 200.62.64.1 is not authoritative over UDP.

**Notices**:

* No answer received from 200.62.64.1 when querying for ni./IN/SOA.
* No answer received from 200.62.64.1 when querying for ni./IN/SOA.
* No answer received from 200.62.64.1 when querying for ni./SOA/IN.
* No answer received from 200.62.64.1 when querying for ni./IN/SOA.

**Statuses**:

No statuses to display.

## Consistency Scan

**Errors**:

* DNS SERVFAIL when querying 2001:13c7:7004:1:0:0:0:d100 for SOA

**Warnings**:

* The listed nameservers for ni. does not all report the same set of nameservers.

**Notices**:

* No answer received from 200.62.64.1 when querying for ni./IN/SOA.
* No answer received from 200.62.64.1 when querying for ni./IN/NS.

**Statuses**:

No statuses to display.

## Soa Scan

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

* SOA refresh for ni. too small (3600) - recommended >= 14400. SOA refresh decides how often a secondary name server should check the primary name server for zone updates.
* SOA retry for ni. too small (1200) - recommended >= 3600. The retry value is the amount of time secondary name servers will wait before contacting the primary name server again if the last attempt failed. If the retry value is too small, secondary name servers will retry too frequently.

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
* No answer received from 200.107.82.100 when querying for ni./IN/DNSKEY.
* No answer received from 2001:13c7:7004:1:0:0:0:d100 when querying for ni./IN/DNSKEY.

**Statuses**:

No statuses to display.


---
