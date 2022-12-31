## Information Gathering
OK nmap                      https://nmap.org/
OK parsero                   https://github.com/behindthefirewalls/Parsero
OK whatweb                   https://github.com/urbanadventurer/WhatWeb
- dmitry                     https://github.com/jaygreig86/dmitry
- maltego
- recon-ng
- sparta
- ike-scan                   https://github.com/royhills/ike-scan
- ikecrack                   https://ikecrack.sourceforge.net/
- httpx
- nuclei
- subfinder
- urlcrazy                   https://github.com/urbanadventurer/urlcrazy
- aircrack-ng                https://github.com/aircrack-ng/aircrack-ng
- squid3                     https://github.com/CIRDLES/Squid
- dnstracer                  https://github.com/Orc/dnstracer
- httrack                    https://github.com/xroche/httrack
- sxlzptprjkt-admin-finder   https://github.com/sxlmnwb/sxlzptprjkt-admin-finder
- okadminfinder3             https://github.com/mIcHyAmRaNe/okadminfinder3
- hexinject                  https://hexinject.sourceforge.net/
- cdpsnarf                   https://github.com/Zapotek/cdpsnarf
- svmap                      https://github.com/EnableSecurity/sipvicious
- sctpscan                   https://github.com/philpraxis/sctpscan
- multimac                   https://multimac.sourceforge.net/
- intrace                    https://github.com/robertswiecki/intrace
- sslscan                    https://github.com/rbsec/sslscan
- stunnel                    https://github.com/mtrojnar/stunnel
- enum4linux                 https://labs.portcullis.co.uk/tools/enum4linux

01) Information Gathering
    = • Admin Login Page Finder 
        = okadminfinder3                  [SOURCE-NATIVE] cd /pentest/01/okadminfinder3 && python3 okadminfinder3.py 
    = • CMS Identification
        = whatweb                         [DEB-DEBIAN] apt install whatweb
    = • DNS Analysis
        = dmitry                          [DEB-DEBIAN] apt install dmitry
        = dnsdict6                        [DEB-DEBIAN] apt install thc-ipv6
        = dnsenum                         [DEB-DEBIAN] apt install dnsenum
        = dnsmap                          [DEB-DEBIAN] apt install dnsmap
        = dnsrecon                        [DEB-DEBIAN] apt install dnsrecon
        = dnsrevenum6                     [DEB-DEBIAN] apt install dnsrevenum6
        = dnssecwalk                      [DEB-DEBIAN] apt install thc-ipv6 
        = dnstracer                       [DEB-DEBIAN] apt install dnstracer
        = lbd                             [SOURCE-NATIVE] cd /pentest/01/lbd && bash lbd
        = nmap                            [DEB-DEBIAN] apt install nmap
        = urlcrazy                        [SOURCE-NATIVE] cd /pentest/01/urlcrazy && ruby urlcrazy
    = • DNS Evolution
        = dnsdict6                        [DEB-DEBIAN] apt install thc-ipv6
        = dnsenum                         [DEB-DEBIAN] apt install dnsenum
        = dnsmap                          [DEB-DEBIAN] apt install dnsmap
        = dnsrecon                        [DEB-DEBIAN] apt install dnsrecon
        = dnsrevenum6                     [DEB-DEBIAN] apt install dnsrevenum6
        = dnstracer                       [DEB-DEBIAN] apt install dnstracer         
        = nmap                            [DEB-DEBIAN] apt install nmap
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
	    = hexinject                       [BIN-NATIVE] cd /pentest/01/hexinject && ./hexinject
	    = lbd                             [SOURCE-NATIVE] cd /pentest/01/lbd && bash lbd
	    = wafw00f                         [DEB-DEBIAN] apt install wafw00f
    = • Live Host Identification
        = alive6                          [DEB-DEBIAN] apt install thc-ipv6
	    = arping                          [DEB-DEBIAN] apt install arping
	    = cdpsnarf                        [SOURCE-NATIVE] cd /pentest/01/cdpsnarf && ./cdpsnarf             
        = detect-new-ip6                  [DEB-DEBIAN] apt install thc-ipv6
	    = detect_sniffer6                 [DEB-DEBIAN] apt install thc-ipv6
	    = dmitry                          [DEB-DEBIAN] apt install dmitry
        = dnmap-client                    [SOURCE-NATIVE] cd /pentest/01/dnmap && python3 dnmapc.py   
	    = dnmap-server                    [SOURCE-NATIVE] cd /pentest/01/dnmap && python3 dnmaps.py  
        = four2six                        [DEB-DEBIAN] apt install thc-ipv6
        = inverse_lookup6                 [DEB-DEBIAN] apt install thc-ipv6
	    = miranda                         [SOURCE-NATIVE] cd /pentest/01/miranda && ./miranda
	    = nmap                            [DEB-DEBIAN] apt install nmap
	    = passive_discovery6              [DEB-DEBIAN] apt install thc-ipv6
        = randicmp6                       [DEB-DEBIAN] apt install thc-ipv6
        = sctpscan                        [SOURCE-NATIVE] cd /pentest/01/sctpscan && ./sctpscan
	    = svwar                           [DEB-DEBIAN] apt install sipvicious
        = thcping6                        [DEB-DEBIAN] apt install thc-ipv6
	    = trace6                          [DEB-DEBIAN] apt install thc-ipv6
    = • Network & Port Scanners
        = dmitry                          [DEB-DEBIAN] apt install dmitry
	    = implementation6                 [DEB-DEBIAN] apt install thc-ipv6
	    = implementation6d                [DEB-DEBIAN] apt install thc-ipv6
	    = knockpy                         [DEB-DEBIAN] apt install knockpy
	    = multimac                        [SOURCE-NATIVE] cd /pentest/01/multimac && ./multimac
	    = nmap                            [DEB-DEBIAN] apt install nmap
	    = scapy                           [DEB-DEBIAN] apt install scapy
    = • OS Fingerprint
        = dnmap-client                    [SOURCE-NATIVE] cd /pentest/01/dnmap && python3 dnmapc.py   
	    = dnmap-server                    [SOURCE-NATIVE] cd /pentest/01/dnmap && python3 dnmaps.py  
	    = miranda                         [SOURCE-NATIVE] cd /pentest/01/miranda && ./miranda
	    = nmap                            [DEB-DEBIAN] apt install nmap
	    = p0f                             [DEB-DEBIAN] apt install p0f
	    = sctpscan                        [SOURCE-NATIVE] cd /pentest/01/sctpscan && ./sctpscan
    = • Open Source Intelligence
        = dmitry                          [DEB-DEBIAN] apt install dmitry
	    = urlcrazy                        [SOURCE-NATIVE] cd /pentest/01/urlcrazy && ruby urlcrazy
    = • Port Analysis 
        = sslsplit                        [DEB-DEBIAN] apt install sslsplit
    = • Proxy
        = squid                           [DEB-DEBIAN] apt install squid && squid -h
        = tor                             [DEB-DEBIAN] apt install tor && man tor
    = • Route Analysis
        = dnmap-client                    [SOURCE-NATIVE] cd /pentest/01/dnmap && python3 dnmapc.py   
	    = dnmap-server                    [SOURCE-NATIVE] cd /pentest/01/dnmap && python3 dnmaps.py  
	    = intrace                         [SOURCE-NATIVE] cd /pentest/01/intrace && ./intrace -h 
	    = scapy                           [DEB-DEBIAN] apt install scapy
	    = trace6                          [DEB-DEBIAN] apt install thc-ipv6
    = • SMB Analysis
        = smbclient                       [DEB-DEBIAN] apt install smbclient
    = • SMTP Analysis
        = nmap                            [DEB-DEBIAN] apt install nmap
	    = swaks                           [DEB-DEBIAN] apt install swaks
    = • SNMP Analysis
        = onesixtyone                     [DEB-DEBIAN] apt install onesixtyone
	    = snmpcheck                       [SOURCE-NATIVE] cd /pentest/01/snmpcheck && ruby snmpcheck.rb  
    = • SSL Analysis
        = sslh                            [DEB-DEBIAN] apt install sslh
	    = sslstrip                        [SOURCE-NATIVE] cd /pentest/01/sslstrip && python3 sslstrip.py  
	    = testssl.sh                      [SOURCE-NATIVE] cd /pentest/01/testssl-sh && bash testssl.sh  
    = • SSL Breakdown
        = sslh                            [DEB-DEBIAN] apt install sslh
	    = sslstrip                        [SOURCE-NATIVE] cd /pentest/01/sslstrip && python3 sslstrip.py  
	    = stunnel                         [SOURCE-NATIVE] cd /pentest/01/stunnel ./configure make make install
    = • Service Analysis 
        = miranda                         [SOURCE-NATIVE] cd /pentest/01/miranda && ./miranda
    = • Service Fingerprinting
        = dnmap-client                    [SOURCE-NATIVE] cd /pentest/01/dnmap && python3 dnmapc.py   
	    = dnmap-server                    [SOURCE-NATIVE] cd /pentest/01/dnmap && python3 dnmaps.py   
	    = implementation6                 [DEB-DEBIAN] apt install thc-ipv6
	    = implementation6d                [DEB-DEBIAN] apt install thc-ipv6
	    = miranda                         [SOURCE-NATIVE] cd /pentest/01/miranda && ./miranda
	    = nmap                            [DEB-DEBIAN] apt install nmap
    = • SMB Evolution
        = nmap                            [DEB-DEBIAN] apt install nmap
    = • SNMP Evolution
        = nmap                            [DEB-DEBIAN] apt install nmap
    = • Telphony Aalysis
        = svmap                           [DEB-DEBIAN] apt install sipvicious
    = • Traffic Monitor
        = cdpsnarf                        [SOURCE-NATIVE] cd /pentest/01/cdpsnarf && ./cdpsnarf
	    = intrace                         [SOURCE-NATIVE] cd /pentest/01/intrace && ./intrace -h 
	    = p0f                             [DEB-DEBIAN] apt install p0f
	    = scapy                           [DEB-DEBIAN] apt install scapy
	    = wireshark                       [DEB-DEBIAN] apt install wireshark
    = • VPN Analysis
        = fiked                           [SOURCE-NATIVE] cd /pentest/01/fiked && ./fiked
	    = ike-scan                        [DEB-DEBIAN] apt install ike-scan
	    = ikecrack                        [SOURCE-NATIVE] cd /pentest/01/ikecrack && perl ikecrack.pl
    = • Web IPS IDS Analysis
        = wafw00f                         [DEB-DEBIAN] apt install wafw00f
    = • Web Inventory
        = enum4linux                      [SOURCE-NATIVE] cd /pentest/01/enum4linux && perl enum4linux.pl
	    = firewalk
	    = iwebaudit
	    = nmap-scrape
	    = parsero                         [SOURCE-NATIVE] cd /pentest/03/parsero && python3 parsero.py                    
	    = pyfoca
	    = rid_enum
    = • Web Snanner
        = dirb                            [DEB-DEBIAN] apt install dirb
    = • Wireless Analysis
        = airodump-ng                     [DEB-DEBIAN] apt install aircrack-ng
	    = giskismet 
	    = kismet                          [DEB-DEBIAN] apt install kismet
	= nmap                                [DEB-DEBIAN] apt install nmap
	= maltego                             [DEB-DEBIAN] dpkg -i
	= recon-ng
	= sparta
	= ike-scan                            [DEB-DEBIAN] apt install ike-scan
	= httpx
	= nuclei
