# notes
everything i learnt till now all my hands on experience
for private ip - ipconfig 
for public ip curl ifconfig.me
for ip in linux ifconfig "or" ip a
nmap - sn ip for port scanning
nmap -sS ip syn scan
nmap -sA ip ack scan
nmap -sX ip xmas scan sends flags
nmap -sN ip null scan "or" fping -a -g ip/subnet
nmap -sN ip/24 for discovering live hosts "or" fping -a -g ip/subnet
sudo arp -scan ip/24 arp scan found mac address from ip address
sudo netdiscover -r ip/24

