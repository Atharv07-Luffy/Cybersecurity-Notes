# Networking cheat sheet

## OSI model (Open Systems Interconnection)

| Layer | Name | What it does | Example |
|---|---|---|---|
| 7 | Application | | HTTP, DNS |
| 6 | Presentation | | |
| 5 | Session | | |
| 4 | Transport | | TCP, UDP |
| 3 | Network | | IP |
| 2 | Data Link | | MAC address |
| 1 | Physical | | |

## Common ports

| Port | Service | Meaning |
|---|---|---|
| 22 | SSH | Secure Shell |
| 53 | DNS | Domain Name System |
| 80 | HTTP | Hypertext Transfer Protocol |
| 443 | HTTPS | HTTP over TLS |

## Commands

| Command | What it does |
|---|---|
| `ip a` | |
| `ping -c 4 host` | |
| `nslookup host` | |
| `dig host` | |
| `traceroute host` | |
| `curl -I url` | |
| `curl -v url` | |
| `ss -tuln` | |

## HTTP status codes
- 100-199: INFO
- 200-299: SUCCESS
- 300-399: REDIRECTION
- 400-499: CLIENT ERRORS
- 500-599: SERVER ERRORS

## Things I noticed
- `http://example.com` returned 200 with no redirect to HTTPS
