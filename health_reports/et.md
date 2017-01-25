# `et.` TLD Health Check Results

Final scan status: **error** 

Original RIPE scan results URL: http://dnscheck.ripe.net/?time=1485323011&id=15767171&view=basic&test=standard

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

### `et.cctld.authdns.ripe.net`

**Errors**:

* Name server et.cctld.authdns.ripe.net (193.0.9.73) not authoritative for et.. The name server does not answer authoritatively to queries for the tested domain.  This is probably due to misconfiguration where the name server is not set up to serve the tested domain.
* Name server et.cctld.authdns.ripe.net (2001:67c:e0:0:0:0:0:73) not authoritative for et.. The name server does not answer authoritatively to queries for the tested domain.  This is probably due to misconfiguration where the name server is not set up to serve the tested domain.

**Warnings**:

* Nameserver at 193.0.9.73 is not authoritative over UDP.
* Nameserver at 2001:67c:e0:0:0:0:0:73 is not authoritative over UDP.

**Notices**:

* No answer received from 193.0.9.73 when querying for et./IN/SOA.
* No answer received from 193.0.9.73 when querying for et./IN/SOA.
* No answer received from 193.0.9.73 when querying for et./SOA/IN.
* No answer received from 193.0.9.73 when querying for et./IN/SOA.
* No answer received from 2001:67c:e0:0:0:0:0:73 when querying for et./IN/SOA.
* No answer received from 2001:67c:e0:0:0:0:0:73 when querying for et./IN/SOA.
* No answer received from 2001:67c:e0:0:0:0:0:73 when querying for et./SOA/IN.
* No answer received from 2001:67c:e0:0:0:0:0:73 when querying for et./IN/SOA.

**Statuses**:

No statuses to display.

### `ns1.telecom.net.et`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `ns2.telecom.net.et`

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

No notices to display.

**Statuses**:

No statuses to display.

### `phloem.uoregon.edu`

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

* The listed nameservers for et. does not all report the same set of nameservers.

**Notices**:

* No answer received from 2001:67c:e0:0:0:0:0:73 when querying for et./IN/SOA.
* No answer received from 193.0.9.73 when querying for et./IN/SOA.
* No answer received from 193.0.9.73 when querying for et./IN/NS.
* No answer received from 2001:67c:e0:0:0:0:0:73 when querying for et./IN/NS.

**Statuses**:

No statuses to display.

## Soa Scan

**Errors**:

No errors to display.

**Warnings**:

No warnings to display.

**Notices**:

* SOA refresh for et. too small (600) - recommended >= 14400. SOA refresh decides how often a secondary name server should check the primary name server for zone updates.
* SOA refresh for et. lower than retry (600 vs 1800). The retry value is the amount of time secondary name servers will wait before contacting the primary name server again if the last attempt failed.  If the refresh value is lower than the retry value, it's useless.
* SOA retry for et. too small (1800) - recommended >= 3600. The retry value is the amount of time secondary name servers will wait before contacting the primary name server again if the last attempt failed. If the retry value is too small, secondary name servers will retry too frequently.

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

* No answer received from 193.0.9.73 when querying for et./IN/DNSKEY.
* No answer received from 2001:67c:e0:0:0:0:0:73 when querying for et./IN/DNSKEY.

**Statuses**:

No statuses to display.


---
