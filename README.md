# Mask_URL

A simple bash script to generate phishing-style masked URLs with optional URL shortening and custom social engineering words.  
This tool is useful for **ethical hacking** and **cybersecurity research**, particularly for demonstrating how URL masking works in social engineering attacks.


## Features
- Automatically validates and fixes URLs with missing `http` or `https`.
- Optional URL shortening via [is.gd](https://is.gd/).
- Supports multiple popular domains for masking (Facebook, YouTube, Instagram, Twitter, etc.).
- Allows adding custom **social engineering keywords** (e.g., `free-gift`, `update-now`).
- Generates final masked phishing-style URL.

---

## Installation
```bash
git clone https://github.com/Andro-Spy/Mask_URL.git
cd Mask_URL
chmod +x url
sudo mv url /usr/bin
cd ..
rm -rf Mask_URL
```
## ▶️ Run
Now run this Command.
```
url
```
Use `sudo rm /usr/bin/url` For remove.

## Example Workflow
```
==== Custom Mask URL Generator ====
Enter the target URL: example.com
⚠️ URL doesn't contain http/https.
Do you want to add it?
1) http
2) https
Choose: 2
[+] Updated URL: https://example.com
Do you want to shorten the URL? (y/n): y
[*] Shortening URL using is.gd...
[+] Shortened URL: https://is.gd/abcd

Choose mask domain:
1) facebook.com
2) youtube.com
3) instagram.com
4) twitter.com
5) custom domain
Enter choice [1-5]: 1
Enter social engineering words (e.g., free-gift): video
```
✅ Final Masked URL:
`https://facebook.com-video@is.gd/abcd`



> ⚠️ **Disclaimer:**  
> This tool is for educational purposes only.  
> The author is **not responsible** for any misuse or illegal activities.

---
