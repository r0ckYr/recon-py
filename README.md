# recon-py
A simple python script for gathering subdomains for a domain

**Sources:**

1. alienvault
2. hackertarget
3. crt.sh
4. virustotal
5. bufferoverrun
6. threatcorwd
7. securitytrails
8. certspotter

# Install
```
git clone https://github.com/r0ckYr/recon-py.git
cd recon-py
```

# Usage
```
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
