# `mh.` TLD Health Check Results

Final scan status: **error** 

Original RIPE scan results URL: http://dnscheck.ripe.net/?time=1485320728&id=15766706&view=basic&test=standard

## Delegation Scan

**Errors**:

* Superfluous name server listed at parent: ns.ntamar.net A name server listed at the parent, but not at the child, was found. This is most likely an administrative error. You should update the parent to match the name servers at the child as soon as possible.
* Too few name servers (1). Only one name server was found for the zone. You should always have at least two name servers for a zone to be able to handle transient connectivity problems.

**Warnings**:

No warnings to display.

**Notices**:

* Additional name server listed at child: ns.minta.mh A name server listed at the child, but not at the parent, was found. This is most likely a configuration error, but there are sometimes reasons for setting up a zone this way.
* Too few IPv6 name servers (1). Only one IPv6 name server was found for the zone. You should always have at least two IPv6 name servers for a zone to be able to handle transient connectivity problems.

**Statuses**:

No statuses to display.

## Nameserver Scan

### `ns.amarshallinc.com`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns.minta.mh`

**Errors**:

* Name server ns.minta.mh (2405:400:0:2:0:0:0:33) does not answer queries over UDP. The name server failed to answer queries sent over UDP.  This is probably due to the name server not correctly set up or due to misconfigured filtering in a firewall.
* Name server ns.minta.mh (2405:400:0:2:0:0:0:33) does not answer queries over TCP. The name server failed to answer queries sent over TCP.  This is probably due to the name server not correctly set up or due to misconfgured filtering in a firewall. It is a rather common misconception that DNS does not need TCP unless they provide zone transfers - perhaps the name server administrator is not aware that TCP usually is a requirement.

**Warnings**:

* Could not find reverse address for 2405:400:0:2:0:0:0:33 (3.3.0.0.0.0.0.0.0.0.0.0.0.0.0.0.2.0.0.0.0.0.0.0.0.0.4.0.5.0.4.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns.ntamar.net`

**Errors**:

* Name server ns.ntamar.net (2405:400:0:2:0:0:0:33) does not answer queries over UDP. The name server failed to answer queries sent over UDP.  This is probably due to the name server not correctly set up or due to misconfigured filtering in a firewall.
* Name server ns.ntamar.net (2405:400:0:2:0:0:0:33) does not answer queries over TCP. The name server failed to answer queries sent over TCP.  This is probably due to the name server not correctly set up or due to misconfgured filtering in a firewall. It is a rather common misconception that DNS does not need TCP unless they provide zone transfers - perhaps the name server administrator is not aware that TCP usually is a requirement.

**Warnings**:

* Could not find reverse address for 2405:400:0:2:0:0:0:33 (3.3.0.0.0.0.0.0.0.0.0.0.0.0.0.0.2.0.0.0.0.0.0.0.0.0.4.0.5.0.4.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

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

* The listed nameservers for mh. all report the same set of nameservers.

**Statuses**:

No statuses to display.

## Soa Scan

**Errors**:

No errors to display.

**Warnings**:

* Could not find reverse address for 2405:400:0:2:0:0:0:33 (3.3.0.0.0.0.0.0.0.0.0.0.0.0.0.0.2.0.0.0.0.0.0.0.0.0.4.0.5.0.4.2.ip6.arpa.). PTR record(s) for the address could not be found in the .arpa-zone. (ip6.arpa. for IPv6 addresses and in-addr.arpa. for IPv4).

**Notices**:

* SOA minimum for mh. too large (345600) - recommended <= 86400. The SOA minimum is used to tell caching resolvers how long they may cache negative answers. If the value is too large, negative caching will be to aggressive.

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
