# `gw.` TLD Health Check Results

Final scan status: **error** 

Original RIPE scan results URL: http://dnscheck.ripe.net/?time=1485322123&id=15766991&view=basic&test=standard

## Delegation Scan

**Errors**:

* Superfluous name server listed at parent: ns4.dns.pt A name server listed at the parent, but not at the child, was found. This is most likely an administrative error. You should update the parent to match the name servers at the child as soon as possible.

**Warnings**:

No warnings to display.

**Notices**:

* Additional name server listed at child: gw01.dns.pt A name server listed at the child, but not at the parent, was found. This is most likely a configuration error, but there are sometimes reasons for setting up a zone this way.
* Additional name server listed at child: gw03.dns.pt A name server listed at the child, but not at the parent, was found. This is most likely a configuration error, but there are sometimes reasons for setting up a zone this way.

**Statuses**:

No statuses to display.

## Nameserver Scan

### `gw01.dns.pt`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `gw03.dns.pt`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `phobos.fccn.pt`

**Errors**:

No errors to display.

**Warnings**:

* Reverse for 193.136.7.17 points to an unknown host name (phobos.rccn.net). The PTR record for the address points to an unknown host name.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `sns-pb.isc.org`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns4.dns.pt`

**Errors**:

* No address found for ns4.dns.pt. No IPv4 or IPv6 address was found for the host name.
* Host name or address error for ns4.dns.pt. The specified host name is not a valid host name or the host name points to an invalid IP address, e.g. a private or reserved IP address.

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

* The listed nameservers for gw. all report the same set of nameservers.

**Statuses**:

No statuses to display.

## Soa Scan

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

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

* Broken chain of trust for gw. - DNSKEY found at child, but no DS was found at parent. The child seems to use DNSSEC, but the parent has no secure delegation.  The chain of trust between the parent and the child is broken and validating resolvers will not be able to validate answers from the child.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.


---
