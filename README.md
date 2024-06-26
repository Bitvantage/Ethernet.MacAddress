# Bitvantage.Ethernet.MacAddress
Parse, decode, and format MAC addresses in various formats

A [MAC address](https://en.wikipedia.org/wiki/MAC_address) is a globally unique identifier assigned to Ethernet devices that consists of a bit to indicate if it is locally administrated, a bit to indicate if it is a multicast address, a manufacture identifier, and an extension identifier or serial number.


## Installing via NuGet Package Manager
```
PM> NuGet\Install-Package Bitvantage.Ethernet.MacAddress
```

## Quick Start
```csharp
var macAddress1 = MacAddress.Parse("dead:beef:abcd");
var macAddress2 = MacAddress.Parse("dead.beef.abcd");
var macAddress3 = MacAddress.Parse("de.ad.be.ef.ab.cd");
var macAddress4 = MacAddress.Parse("de:ad:be:ef:ab:cd");
var macAddress5 = MacAddress.Parse("deadbeefabcd");
```