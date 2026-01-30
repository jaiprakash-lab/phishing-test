# Security & Responsible Use

- This repository contains an educational, static-only phishing simulation that does NOT collect or transmit credentials.
- Do NOT add server-side code that stores or forwards credentials to this public repo.
- If you need to run active simulations against people, obtain written authorization first.
- If you find sensitive information accidentally committed, contact the repository owner immediately and follow the cleanup steps below.

Cleanup steps if secrets were committed
1. Remove the secret from the latest commit and force-push (only in private repos).
2. Use `git filter-repo` or the BFG Repo-Cleaner to purge secrets from history:
   - Recommended: https://github.com/newren/git-filter-repo or https://rtyley.github.io/bfg-repo-cleaner/
3. Rotate any leaked keys or credentials immediately.

Contact the repository owner for responsible disclosure.