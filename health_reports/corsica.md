# `corsica.` TLD Health Check Results

Final scan status: **warning** 

Original RIPE scan results URL: http://dnscheck.ripe.net/?time=1485323483&id=15767303&view=basic&test=standard

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

### `d.nic.fr`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `f.ext.nic.fr`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `g.ext.nic.fr`

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

* 3 different serials found. The SOA serial is not the same on all name servers. This is usually due to misconfiguration, but can sometimes be the result of slow zone propagation to secondary name servers.

**Notices**:

* The listed nameservers for corsica. all report the same set of nameservers.

**Statuses**:

No statuses to display.

## Soa Scan

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

* SOA MNAME for corsica. (a.nic.fr) not listed as NS. The name server listed as the SOA MNAME is not listed as a name server.
* SOA refresh for corsica. too small (3600) - recommended >= 14400. SOA refresh decides how often a secondary name server should check the primary name server for zone updates.
* SOA retry for corsica. too small (1800) - recommended >= 3600. The retry value is the amount of time secondary name servers will wait before contacting the primary name server again if the last attempt failed. If the retry value is too small, secondary name servers will retry too frequently.

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

* Parent DS(corsica.) does not refer to secure entry point (SEP) at child: DS(corsica./8/2/63082) The DS RRset refers to a DNSKEY at the child, but the key is not marked as a secure entry point.

**Statuses**:

No statuses to display.


---
