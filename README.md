# Admin Brute

admin-brute is a focused wordlist repository containing common admin panel paths
used during reconnaissance and authorization testing.

It helps security testers quickly identify exposed administrative interfaces.

## About

This repository provides a curated list of frequently used admin, administrator,
and backend login directories found across web applications and CMS platforms.

The list is optimized for:
- Directory brute forcing
- Admin panel discovery
- Initial attack surface mapping

## Included Paths

The wordlist includes common admin locations such as:

admin/  
administrator/  
admin5/  
usuarios/  
usuario/  
moderator/  
webadmin/  
adminarea/  
bb-admin/  
adminLogin/
memberadmin/
administratorlogin/
adm/

## Usage

This wordlist can be used with tools such as:

- dirsearch
- gobuster
- ffuf
- wfuzz

Example:

ffuf -u https://target.com/FUZZ -w admin-brute.txt

## Intended Audience

- Bug bounty hunters
- Penetration testers
- Security researchers
- Red teamers

## Legal Disclaimer

Use this repository **only** on systems you own or have explicit permission to test.
Unauthorized access attempts are illegal.

## Author

Muhammad Sudais Usmani  
GitHub: https://github.com/Dit-Developers  
LinkedIn: https://www.linkedin.com/in/muhammad-sudais-usmani-950889311/  
Portfolio: https://msu-portfolio.vercel.app/
