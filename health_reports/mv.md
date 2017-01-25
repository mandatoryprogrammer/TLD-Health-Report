# `mv.` TLD Health Check Results

Final scan status: **ok** 

Original RIPE scan results URL: http://dnscheck.ripe.net/?time=1485320507&id=15766658&view=basic&test=standard

## Delegation Scan

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

* Additional name server listed at child: ns.mv A name server listed at the child, but not at the parent, was found. This is most likely a configuration error, but there are sometimes reasons for setting up a zone this way.
* Too few IPv6 name servers (1). Only one IPv6 name server was found for the zone. You should always have at least two IPv6 name servers for a zone to be able to handle transient connectivity problems.

**Statuses**:

No statuses to display.

## Nameserver Scan

### `mv-ns.anycast.pch.net`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns.dhivehinet.net.mv`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns.mv`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns2.dhivehinet.net.mv`

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

* The listed nameservers for mv. all report the same set of nameservers.

**Statuses**:

No statuses to display.

## Soa Scan

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

* SOA refresh for mv. too small (1800) - recommended >= 14400. SOA refresh decides how often a secondary name server should check the primary name server for zone updates.
* SOA refresh for mv. lower than retry (1800 vs 1800). The retry value is the amount of time secondary name servers will wait before contacting the primary name server again if the last attempt failed.  If the refresh value is lower than the retry value, it's useless.
* SOA retry for mv. too small (1800) - recommended >= 3600. The retry value is the amount of time secondary name servers will wait before contacting the primary name server again if the last attempt failed. If the retry value is too small, secondary name servers will retry too frequently.
* SOA expire for mv. too small (3600) - recommended >= 604800. The SOA expire value defines how long a secondary name server will wait before considering DNS data for a zone to be too old to serve in case it fails to reach the primary name server.
* SOA expire for mv. lower than refresh. The SOA expire value should be at least 7 times the SOA refresh value, to give secondary name servers a fair chance of refreshing their copy of the zone before the data is considered too old to serve.

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

No notices to display.

**Statuses**:

No statuses to display.


---
