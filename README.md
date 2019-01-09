# DDos-script
DDos 

If you use this script give me credits !! Nerds!!

It is very easy to use. This is layer 7 and layer 4 attacks. Just be careful when your using on anyone.  

# Usage
usage: ddos.py [-h] [-g G] [-p P] [-d D] [-ah AH] [-t T]

Example: python ddos.py -t 999 -g 'https://targeted-website.com 
          python ddos.py -t 999 -p 'https://targeted-website.com' -ah 'Content-Type: application/json' -d '{"json": "payload"}

optional arguments:

  -h, --help  show this help message and exit
  
  -g        Specify GET request. Usage: -g '< url >'
  
  -p        Specify POST request. Usage: -p '< url >'
  
  -d        Specify data payload for POST request
  
  -ah      Specify addtional header
  
  -t        Specify number of threads to be used 

# MacFlood: 

Edit the mac address you want to flood in the python script. 

## Requirements
* scapy -- `pip install scapy`

## Usage
./macflood.py
