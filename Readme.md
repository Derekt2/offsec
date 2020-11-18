# Discovery
Place ip ranges in newline delimited ip_ranges, then:
```
nmap -p- -sC --min-rate=10000 -iL ip_ranges > nmap_scan_full.txt
```

consider masscan as well:
```
masscan -iL ips-online.txt --rate 10000 -p1-65535 --only-open -oL masscan.out

```

Find subdomains using bfac, subbrute, and gobuster and spyse and theharvester, and google dorks

Try subdomain takeover using HostileSubBruteforcer

Find emails using theharvester and google dorking

Run Vuln Scan


# webapp recon
Check sites using wappanlyzer, research underlying techniques and pocs or exploits

launch nikto scan against all sites

In Burp manipulate X-Forwarded header looking for admin sessions from 127.0.0.1

Run zap scan of all websites, export report after

# Access

Search credential leaks for harvested emails/passwords and try variations

Use macro documents in phishes, email and chats

Use Arduino badusb


Resources:
```
https://github.com/swisskyrepo/PayloadsAllTheThings 
https://github.com/blackc03r/OSCP-Cheatsheets/tree/master/offensive-security
https://github.com/blackc03r/OSCP-Cheatsheets/blob/master/offensive-security/initial-access/phishing-with-ms-office/t1137-office-vba-macros.md
https://guide.offsecnewbie.com/network-pen
```