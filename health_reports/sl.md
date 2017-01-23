# `sl.` TLD Health Check Results

Final scan status: **error** 

Original RIPE scan results URL: http://dnscheck.ripe.net/?time=1485155003&id=15758172&view=basic&test=standard

## Delegation Scan

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

* No IPv6 name servers found.

**Statuses**:

No statuses to display.

## Nameserver Scan

### `ns1.neoip.com`

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 62.90.247.118 (118.247.90.62.in-addr.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns2.neoip.com`

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

* The listed nameservers for sl. all report the same set of nameservers.

**Statuses**:

No statuses to display.

## Soa Scan

**Errors**:

* No address found for ns1.neoip.com.sl. No IPv4 or IPv6 address was found for the host name.

**Warnings**:

* Error while checking SOA MNAME for sl. (ns1.neoip.com.sl). The SOA MNAME is not a valid host name.

**Notices**:

* SOA MNAME for sl. (ns1.neoip.com.sl) not listed as NS. The name server listed as the SOA MNAME is not listed as a name server.
* SOA refresh for sl. too small (600) - recommended >= 14400. SOA refresh decides how often a secondary name server should check the primary name server for zone updates.
* SOA refresh for sl. lower than retry (600 vs 900). The retry value is the amount of time secondary name servers will wait before contacting the primary name server again if the last attempt failed.  If the refresh value is lower than the retry value, it's useless.
* SOA retry for sl. too small (900) - recommended >= 3600. The retry value is the amount of time secondary name servers will wait before contacting the primary name server again if the last attempt failed. If the retry value is too small, secondary name servers will retry too frequently.
* SOA expire for sl. too small (7200) - recommended >= 604800. The SOA expire value defines how long a secondary name server will wait before considering DNS data for a zone to be too old to serve in case it fails to reach the primary name server.

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

* Broken chain of trust for sl. - DNSKEY found at child, but no DS was found at parent. The child seems to use DNSSEC, but the parent has no secure delegation.  The chain of trust between the parent and the child is broken and validating resolvers will not be able to validate answers from the child.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.


---
