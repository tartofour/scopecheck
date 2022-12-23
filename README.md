# scopecheck

- [ ] Add help menu

## Description
Take a list of FQDNs from stdin. The script resolves each FQDN and check if resolved IP addresses are present in the SCOPE_FILE. In-scope FQDNs are sent to stdout.

## Usage

```bash
▶ cat subdomains.txt | scopecheck <SCOPE_FILE>

www.example.com
xxx.example.com
yyy.example.com
```

## File format
The SCOPE_FILE must contain one IP address per line.
