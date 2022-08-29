<div align=center>

# Kagebuyo DDoS
 Layer 7 DDoS with Multiple Bypass<br/>
 Don't attack any websites you don't own it<br/>
 This was created for educational purposes<br/>
 All responsibilities and disadvantages of using this program is for the user.<br/>

# Menu
![image](https://user-images.githubusercontent.com/109874531/187014527-6807820e-c551-452b-b7a6-adf9d5f1e657.png)
</div>

## Methods

```sh
  [Layer 7]
 - cfb     | Bypass CF attack
 - pxcfb   | Bypass CF attack with proxy
 - cfreq   | Bypass CF UAM, CAPTCHA, BFM, etc,, with request
 - cfsoc   | Bypass CF UAM, CAPTCHA, BFM, etc,, with socket
 - pxsky   | Bypass Google Project Shield, Vshield, DDoS Guard Free, CF NoSec With Proxy
 - sky     | Sky method without proxy
 - http2   | HTTP 2.0 Request Attack 
 = pxhttp2 | HTTP 2.0 Request Attack With Proxy
 - spoof   | Spoof Attasck
 - pxspoof | Spoof Attack with Proxy
 - get     | Get  Request Attack
 - post    | Post Request Attack
 - head    | Head Request Attack
 - soc     | Socket Attack
 - pxraw   | Proxy Request Attack
 - pxsoc   | Proxy Socket Attack
 
  [Layer 4]
  -udp     | UDP Attack
  -tcp     | TCP Attack
  
  [Tools]
 - Dns     | Classic DNS Lookup
 - Geoip   | Geo IP Address Lookup
 - Subnet  | Subnet IP Address Lookup
```

## Usage on Linux
```sh
You must use Python 3.9 or higher

git clone https://github.com/404Kator1/Kagebuyo-DDoS

Install Python3 modules
 - pip3 install -r requirements.txt  or  pip install -r requirements.txt
Install Chrome (or update it lastest version)
 - wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
 - apt-get install ./google-chrome-stable_current_amd64.deb

OR
 - python3 ksetup.py

```

## Example
```sh
Use DDoS Panel   : python3 kagebuyo.py
Use command line : python3 kagebuyo.py <method> <target> <thread> <time>
      └──────────> python3 kagebuyo.py cfb https://example.com 100 30
```
