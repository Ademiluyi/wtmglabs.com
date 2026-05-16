# wtmglabs.com

Landing page for WTMG Labs. Static HTML hosted on GitHub Pages at https://wtmglabs.com.

## Deploy

1. Push to `main`.
2. Repo Settings → Pages → Source: `main` / root.
3. Custom domain: `wtmglabs.com` (CNAME file is already in the repo).
4. GoDaddy DNS — A records to GitHub Pages IPs:
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
   CNAME: `www` → `<username>.github.io`
5. Enable "Enforce HTTPS" once the cert provisions.
