### Github RegEx Search for Hunting (Cheatsheet)
- Want to find internal emails?
`/[a-zA-Z0-9\.\-_]*@tesla.com/`
- Need some environment variables?
`/\=.*\.amazon\.com\// "DB_HOST"`
- URL extraction?
`/https?:\/\/[^\/\s]+\.grab\.com\/[^?\s]*/`
- Find exposed tokens?
**For example (AWS Key):**
`/\b(A3T[A-Z0-9]|AKIA|AGPA|AROA|AIPA|ANPA|ANVA|ASIA)[A-Z0-9]{16}\b/`
