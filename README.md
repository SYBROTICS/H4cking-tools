# H4cking-tools
# SubDominate

**SubDominate** is an advanced Bash script for subdomain enumeration using both passive and active techniques.

## ✨ Features

- Passive enumeration using public APIs
- Active bruteforce using wordlists
- DNS resolution and wildcard filtering
- Custom resolvers support
- Result logging with timestamps

## 🔧 Requirements

- `curl`
- `jq`
- `dig`
- `dnsx` (optional)
- `shuffledns` (optional)
- `parallel`

## 🚀 Usage

```bash
chmod +x subdominate.sh
./subdominate.sh example.com
