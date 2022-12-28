## Information Gathering
OK nmap                      https://nmap.org/
OK parsero                   https://github.com/behindthefirewalls/Parsero
OK whatweb                   https://github.com/urbanadventurer/WhatWeb
- dmitry                     https://github.com/jaygreig86/dmitry
- maltego
- recon-ng
- sparta
- ike-scan                   https://github.com/royhills/ike-scan
- httpx
- nuclei
- subfinder
- urlcrazy                   https://github.com/urbanadventurer/urlcrazy
- aircrack-ng                https://github.com/aircrack-ng/aircrack-ng
- squid3                     https://github.com/CIRDLES/Squid
- dnstracer                  https://github.com/Orc/dnstracer
- httrack                           https://github.com/xroche/httrack
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
        = nmap                            [DEB-DEBIAN] apt install nmap
        = urlcrazy                        [SOURCE-NATIVE] cd /pentest/01/urlcrazy && ruby urlcrazy
    = • DNS Evolution
        = dnsdict6                        [DEB-DEBIAN] apt install thc-ipv6
        = dnsenum                         [DEB-DEBIAN] apt install dnsenum
        = dnsmap                          [DEB-DEBIAN] apt install dnsmap
        = dnsrecon                        [DEB-DEBIAN] apt install dnsrecon
        = dnsrevenum6                     [DEB-DEBIAN] apt install dnsrevenum6
        = dnstracer                       [DEB-DEBIAN] apt install dnstracer         
        = Nmap                            [DEB-DEBIAN] apt install nmap
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
	    = wafw00f                         [DEB-DEBIAN] apt install wafw00f
    = • Live Host Identification
        = alive6                          [DEB-DEBIAN] apt install thc-ipv6
	    = arping                          [DEB-DEBIAN] apt install arping
	    = cdpsnarf
        = detect-new-ip6                  [DEB-DEBIAN] apt install thc-ipv6
	    = detect_sniffer6                 [DEB-DEBIAN] apt install thc-ipv6
	    = dmitry                          [DEB-DEBIAN] apt install dmitry
	    = dnmap-client
	    = dnamp-server
        = four2six 
        = inverse_lookup6                 [DEB-DEBIAN] apt install thc-ipv6
	    = miranda
	    = nmap                            [DEB-DEBIAN] apt install nmap
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
	    = knockpy                         [DEB-DEBIAN] apt install knockpy
	    = multimac
	    = nmap                            [DEB-DEBIAN] apt install nmap
	    = scapy                           [DEB-DEBIAN] apt install scapy
    = • OS Fingerprint
        = dnmap-client
	    = dnmap-server
	    = miranda
	    = nmap                             [DEB-DEBIAN] apt install nmap
	    = p0f                              [DEB-DEBIAN] apt install p0f
	    = sctpscan
    = • Open Source Intelligence
        = dmitry                           [DEB-DEBIAN] apt install dmitry
	    = revhosts
	    = urlcrazy                         [SOURCE-NATIVE] cd /pentest/01/urlcrazy && ruby urlcrazy
    = • Port Analysis 
        = sslsplit                         [DEB-DEBIAN] apt install sslsplit
    = • Proxy
        = squid3                           
    = • Route Analysis
        = dnmap-client
	    = dnmap-server
	    = intrace
	    = scapy                           [DEB-DEBIAN] apt install scapy
	    = trace6                          [DEB-DEBIAN] apt install thc-ipv6
    = • SMB Analysis
        = smbclient                       [DEB-DEBIAN] apt install smbclient
    = • SMTP Analysis
        = nmap                            [DEB-DEBIAN] apt install nmap
	    = swaks                           [DEB-DEBIAN] apt install swaks
    = • SNMP Analysis
        = onesixtyone                     [DEB-DEBIAN] apt install onesixtyone
	    = snmpcheck
    = • SSL Analysis
        = sslh                            [DEB-DEBIAN] apt install sslh
	    = sslstrip
	    = testssl.sh
    = • SSL Breakdown
        = sslh                            [DEB-DEBIAN] apt install sslh
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
	    = nmap                             [DEB-DEBIAN] apt install nmap
	    = sslscan
	    = tlssled
    = • SMB Evolution
        = nmap                             [DEB-DEBIAN] apt install nmap
    = • SNMP Evolution
        = nmap                             [DEB-DEBIAN] apt install nmap
    = • Telphony Aalysis
        = svmap
    = • Traffic Monitor
        = cdpsnarf
	    = ftest
	    = intrace
	    = p0f                              [DEB-DEBIAN] apt install p0f
	    = scapy                            [DEB-DEBIAN] apt install scapy
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
