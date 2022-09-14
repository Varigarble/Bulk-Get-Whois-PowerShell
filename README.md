### Bulk domain name whois lookups with PowerShell

This is a small script that reads a list of domain names in "payload.csv" and saves DNS and Whois results with lookup date to individual text files for each domain name, if such file doesn't already exist.

Note that [whois64.exe from Microsoft SysInternals](https://docs.microsoft.com/en-us/sysinternals/downloads/whois) doesn't handle all TLDs.