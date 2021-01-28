# Experiment
[nmap](https://phoenixnap.com/kb/nmap-command-linux-examples)

# Used Commands 
`nmap www.google.com`

`nmap 142.250.71.4 142.250.71.6`

`nmap 142.250.71.*`

`nmap 142.250.71.1-3`

`nmap 142.250.71.1-5 --exclude 142.250.71.4`

`nmap -O 142.250.71.4`

`nmap -sA 142.250.71.4`

`sudo nmap -sA 142.250.71.4`

`nmap -sV 142.250.71.4`

`nmap -sP 142.250.71.0/24`

`nmap --iflist`

`nmap -h`

`nmap -p 80 142.250.71.4`

`nmap -p 80,443 142.250.71.4`

`nmap -p 80-443 142.250.71.4`

`nmap -p T:8888 142.250.71.4`