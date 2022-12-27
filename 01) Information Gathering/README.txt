## Information Gathering
OK nmap               https://nmap.org/
OK parsero            https://github.com/behindthefirewalls/Parsero
OK whatweb            https://github.com/urbanadventurer/WhatWeb
- dmitry              https://github.com/jaygreig86/dmitry
- maltego
- recon-ng
- sparta
- ike-scan            https://github.com/royhills/ike-scan
- httpx
- nuclei
- subfinder
- urlcrazy            https://github.com/urbanadventurer/urlcrazy
- aircrack-ng         https://github.com/aircrack-ng/aircrack-ng
- squid3              https://github.com/CIRDLES/Squid
- dnstracer           https://github.com/Orc/dnstracer
- httrack             https://github.com/xroche/httrack
- sxlzptprjkt-admin-finder   https://github.com/sxlmnwb/sxlzptprjkt-admin-finder
- okadminfinder3             https://github.com/mIcHyAmRaNe/okadminfinder3

01) Information Gathering
    = • CMS Identification
        = whatweb                         [DEB-DEBIAN] apt install whatweb
    = • DNS Analysis
        = dmitry                          [DEB-DEBIAN] apt install dmitry
	    = dnmap
        = dnsdict6                        [DEB-DEBIAN] apt install thc-ipv6
        = dnsenum                         [DEB-DEBIAN] apt install dnsenum
        = dnsmap                          [DEB-DEBIAN] apt install dnsmap
        = dnsrecon                        [DEB-DEBIAN] apt install dnsrecon
        = dnsrevenum6                     [DEB-DEBIAN] apt install dnsrevenum6
        = dnssecwalk                      [DEB-DEBIAN] apt install thc-ipv6 
        = dnstracer                       [DEB-DEBIAN] apt install dnstracer
        = lbd 
        = Nmap                            [DEB-DEBIAN] sudo apt install nmap
        = urlcrazy                        [SOURCE-NATIVE] cd /pentest/01/urlcrazy && ruby urlcrazy
    = • DNS Evolution
        = dnsdict6                        [DEB-DEBIAN] apt install thc-ipv6
        = dnsenum                         [DEB-DEBIAN] apt install dnsenum
        = dnsmap                          [DEB-DEBIAN] apt install dnsmap
        = dnsrecon                        [DEB-DEBIAN] apt install dnsrecon
        = dnsrevenum6                     [DEB-DEBIAN] apt install dnsrevenum6
        = dnstracer                       [DEB-DEBIAN] sudo apt install dnstracer         
        = Nmap                            [DEB-DEBIAN] sudo apt install nmap
        = urlcrazy                        [SOURCE-NATIVE] cd /pentest/01/urlcrazy && ruby urlcrazy    
    = • Firewall Analysis 
        = denial6                         [DEB-DEBIAN] apt install thc-ipv6
        = dump_router6                    [DEB-DEBIAN] apt install thc-ipv6 
        = firewall6                       [DEB-DEBIAN] apt install thc-ipv6
        = fragmentation6                  [DEB-DEBIAN] apt install thc-ipv6
	= fragrouter6
        = implementation6                 [DEB-DEBIAN] apt install thc-ipv6
        = implementation6d                [DEB-DEBIAN] apt install thc-ipv6
    = • HTTrack
        = httrack                         [DEB-DEBIAN] apt install httrack
    = • IDS/IPS Identification
        = ftest
	    = ftestd
	    = ftester
	    = hexinject
	    = lbd
	    = wafw00f
    = • Live Host Identification
        = alive6                          [DEB-DEBIAN] apt install thc-ipv6
	    = arping
	    = cdpsnarf
        = detect-new-ip6                  [DEB-DEBIAN] apt install thc-ipv6
	    = detect_sniffer6                 [DEB-DEBIAN] apt install thc-ipv6
	    = dmitry                          [DEB-DEBIAN] apt install dmitry
	    = dnmap-client
	    = dnamp-server
        = four2six 
        = inverse_lookup6                 [DEB-DEBIAN] apt install thc-ipv6
	    = miranda
	    = nmap                            [DEB-DEBIAN] sudo apt install nmap
	    = passive_discovery6              [DEB-DEBIAN] apt install thc-ipv6
        = randicmp6                       [DEB-DEBIAN] apt install thc-ipv6
        = sctpscan
	    = svwar
        = thcping6                        [DEB-DEBIAN] apt install thc-ipv6
	    = trace6                          [DEB-DEBIAN] apt install thc-ipv6
    = • Network & Port Scanners
        = dmitry                          [DEB-DEBIAN] apt install dmitry
	    = implementation6                 [DEB-DEBIAN] apt install thc-ipv6
	    = implementation6d                [DEB-DEBIAN] apt install thc-ipv6
	    = knockpy
	    = multimac
	    = nmap                            [DEB-DEBIAN] sudo apt install nmap
	    = scapy
    = • OS Fingerprint
        = dnmap-client
	    = dnmap-server
	    = miranda
	    = nmap                             [DEB-DEBIAN] sudo apt install nmap
	    = p0f
	    = sctpscan
    = • Open Source Intelligence
        = dmitry                           [DEB-DEBIAN] sudo apt install dmitry
	    = revhosts
	    = urlcrazy                         [SOURCE-NATIVE] cd /pentest/01/urlcrazy && ruby urlcrazy
    = • Port Analysis 
        = sslsplit  
    = • Proxy
        = squid3                           
    = • Route Analysis
        = dnmap-client
	    = dnmap-server
	    = intrace
	    = scapy
	    = trace6
    = • SMB Analysis
        = smbclient
    = • SMTP Analysis
        = nmap                             [DEB-DEBIAN] sudo apt install nmap
	    = swaks
    = • SNMP Analysis
        = onesixtyone
	    = snmpcheck
    = • SSL Analysis
        = sslh
	    = sslstrip
	    = testssl.sh
    = • SSL Breakdown
        = sslh
	    = sslscan
	    = sslstrip
	    = stunnel
	    = tlssled
    = • Service Analysis 
        = miranda 
    = • Service Fingerprinting
        = dnmap-client
	    = dnmap-server
	    = implementation6                  [DEB-DEBIAN] apt install thc-ipv6
	    = implementation6d                 [DEB-DEBIAN] apt install thc-ipv6
	    = miranda
	    = nmap                             [DEB-DEBIAN] sudo apt install nmap
	    = sslscan
	    = tlssled
    = • SMB Evolution
        = nmap                             [DEB-DEBIAN] sudo apt install nmap
    = • SNMP Evolution
        = nmap                             [DEB-DEBIAN] sudo apt install nmap
    = • Telphony Aalysis
        = svmap
    = • Traffic Monitor
        = cdpsnarf
	    = ftest
	    = intrace
	    = p0f
	    = scapy
	    = wireshark                        [DEB-DEBIAN] apt install wireshark
    = • VPN Analysis
        = fiked
	    = ike-scan                         [DEB-DEBIAN] apt install ike-scan
	    = ikecrack
    = • Web IPS IDS Analysis
        = waffit
    = • Web Inventory
        = enum4linux
	    = firewalk
	    = iwebaudit
	    = nmap-scrape
	    = parsero                          [SOURCE-NATIVE] cd /pentest/03/parsero && python3 parsero.py                    
	    = pyfoca
	    = rid_enum
    = • Web Snanner
        = dirb                             [DEB-DEBIAN] apt install dirb
    = • Wireless Analysis
        = airodump-ng                      [DEB-DEBIAN] apt install aircrack-ng
	    = giskismet 
	    = kismet                           [DEB-DEBIAN] apt install kismet
	= nmap                                 [DEB-DEBIAN] apt install nmap
	= maltego
	= recon-ng
	= sparta
	= ike-scan                             [DEB-DEBIAN] apt install ike-scan
	= httpx
	= nuclei
	= subfinder
