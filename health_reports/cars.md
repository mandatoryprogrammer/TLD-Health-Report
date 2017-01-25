# `cars.` TLD Health Check Results

Final scan status: **error** 

Original RIPE scan results URL: http://dnscheck.ripe.net/?time=1485324387&id=15767403&view=basic&test=standard

## Delegation Scan

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

* Additional name server listed at child: ns2.uniregistry.info A name server listed at the child, but not at the parent, was found. This is most likely a configuration error, but there are sometimes reasons for setting up a zone this way.

**Statuses**:

No statuses to display.

## Nameserver Scan

### `a.cars.dyntld.net`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `b.cars.dyntld.net`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `c.cars.dyntld.net`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns1.uniregistry.net`

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 2620:57:4000:1:0:0:0:1 (1.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.1.0.0.0.0.0.0.4.7.5.0.0.0.2.6.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns2.uniregistry.info`

**Errors**:

* Name server ns2.uniregistry.info (64.96.245.53) does not answer queries over UDP. The name server failed to answer queries sent over UDP.  This is probably due to the name server not correctly set up or due to misconfigured filtering in a firewall.
* Name server ns2.uniregistry.info (64.96.245.53) does not answer queries over TCP. The name server failed to answer queries sent over TCP.  This is probably due to the name server not correctly set up or due to misconfgured filtering in a firewall. It is a rather common misconception that DNS does not need TCP unless they provide zone transfers - perhaps the name server administrator is not aware that TCP usually is a requirement.

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

* The listed nameservers for cars. all report the same set of nameservers.

**Statuses**:

No statuses to display.

## Soa Scan

**Errors**:

* No address found for ns.uniregistry.net. No IPv4 or IPv6 address was found for the host name.

**Warnings**:

* Error while checking SOA MNAME for cars. (ns.uniregistry.net). The SOA MNAME is not a valid host name.

**Notices**:

* SOA MNAME for cars. (ns.uniregistry.net) not listed as NS. The name server listed as the SOA MNAME is not listed as a name server.
* SOA TTL for cars. too small (900) - recommended >= 3600. The smaller the SOA TTL value, the more often resolvers need to requery for SOA record.
* SOA refresh for cars. too small (1800) - recommended >= 14400. SOA refresh decides how often a secondary name server should check the primary name server for zone updates.
* SOA retry for cars. too small (900) - recommended >= 3600. The retry value is the amount of time secondary name servers will wait before contacting the primary name server again if the last attempt failed. If the retry value is too small, secondary name servers will retry too frequently.

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

**Statuses**:

No statuses to display.


---
