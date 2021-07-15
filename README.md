# recon-py
A simple python script for gathering subdomains for a domain

**Sources:**
    
alienvault

hackertarget

crt.sh

virustotal

bufferoverrun

threatcorwd

securitytrails

certspotter

# Install
```
git clone https://github.com/r0ckYr/recon-py.git
cd recon-py
python3 recon.py example.com
```

# TODO
**1. Data sources to add**
```
    passivetotal
    binaryedge
    recon.dev
    urlscan.io
    whoisxmlapi.com
    riddler
    webarchive
    threatminer
    threatbook
    rapiddns
    sublister
    zoomeye
    sonarsearch
    anubis
    facebook
    twitter
    https://ui.ctsearch.entrust.com/ui/ctsearchui --> like crt.sh
```
**2. Add user options**
```
-t      threads (default 7), number of data sources to fetch from concurrently
-i      specify input file for root domains`

read data from stdout
```
