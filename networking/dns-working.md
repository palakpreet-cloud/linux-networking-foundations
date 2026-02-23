# How DNS Works

DNS (Domain Name System) translates domain names into IP addresses.

Example:
google.com → 142.250.x.x

---

## DNS Resolution Process

1. User enters domain name in browser.
2. Request goes to local DNS resolver.
3. Resolver checks cache.
4. If not found, it queries:
   - Root server
   - TLD server (.com, .org)
   - Authoritative server
5. IP address is returned.
6. Browser connects to server using that IP.

---

## Why DNS is Important

- Makes internet user-friendly
- Enables website access
- Critical for cloud services
