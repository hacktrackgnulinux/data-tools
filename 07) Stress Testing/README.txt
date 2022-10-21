## Stress Testing

OK bed https://gitlab.com/kalilinux/packages/bed
OK doona https://github.com/wireghoul/doona
OK ohrwurm https://gitlab.com/kalilinux/packages/ohrwurm
PENDING powerfuzzer https://github.com/marcinguy/powerfuzzer
OK sfuzz https://github.com/foreni-packages/sfuzz
OK uniscan https://sourceforge.net/projects/uniscan
PENDING xsser https://github.com/epsylon/xsser

07) Stress Testing
    = • DOS
        = denial6                         [DEB-DEBIAN] apt install thc-ipv6
        = dos-new-ip6                     [DEB-DEBIAN] apt install thc-ipv6
        = flood_advertise6                [DEB-DEBIAN] apt install thc-ipv6
        = flood_dhcpc6                    [DEB-DEBIAN] apt install thc-ipv6
        = flood_mld6                      [DEB-DEBIAN] apt install thc-ipv6
        = flood_mldrouter6                [DEB-DEBIAN] apt install thc-ipv6
        = flood_redir6                    [DEB-DEBIAN] apt install thc-ipv6
        = flood_router26                  [DEB-DEBIAN] apt install thc-ipv6
        = flood_router6                   [DEB-DEBIAN] apt install thc-ipv6
        = flood_rs6                       [DEB-DEBIAN] apt install thc-ipv6
        = flood_solicitate6               [DEB-DEBIAN] apt install thc-ipv6
        = kill_router6                    [DEB-DEBIAN] apt install thc-ipv6
        = rsmurf6                         [DEB-DEBIAN] apt install thc-ipv6
        = smurf6                          [DEB-DEBIAN] apt install thc-ipv6
    = • Fuzzing Tools
        = bed                             [DEB-DEBIAN] apt install bed
        = fuzz_dhcpc6                     [DEB-DEBIAN] apt install thc-ipv6
        = fuzz_ip6                        [DEB-DEBIAN] apt install thc-ipv6 
        = ohrwurm                         [SOURCE-DEBUILD] debuild && cp -v ohrwurm /usr/bin/ 
        = sfuzz                           [HTGL-PACKAGES] htgl -i sfuzz
    = • Network Stress Testing
        = denial6                         [DEB-DEBIAN] apt install thc-ipv6
        = dos-new-ip6                     [DEB-DEBIAN] apt install thc-ipv6
        = flood_advertise6                [DEB-DEBIAN] apt install thc-ipv6
        = flood_router6                   [DEB-DEBIAN] apt install thc-ipv6
        = rsmurf6                         [DEB-DEBIAN] apt install thc-ipv6
        = sendpees6                       [DEB-DEBIAN] apt install thc-ipv6
        = smurf6                          [DEB-DEBIAN] apt install thc-ipv6
    = • VOIP Stress Testing
        = dos-new-ip6                     [DEB-DEBIAN] apt install thc-ipv6
        = flood_advertise6                [DEB-DEBIAN] apt install thc-ipv6
        = flood_dhcpc6                    [DEB-DEBIAN] apt install thc-ipv6
        = flood_mld6                      [DEB-DEBIAN] apt install thc-ipv6
        = flood_mldrouter6                [DEB-DEBIAN] apt install thc-ipv6
        = flood_redir6                    [DEB-DEBIAN] apt install thc-ipv6
        = flood_router26                  [DEB-DEBIAN] apt install thc-ipv6
        = flood_router6                   [DEB-DEBIAN] apt install thc-ipv6
        = flood_rs6                       [DEB-DEBIAN] apt install thc-ipv6
        = flood_solicitate6               [DEB-DEBIAN] apt install thc-ipv6
        = fragmentation6                  [DEB-DEBIAN] apt install thc-ipv6
        = kill_router6                    [DEB-DEBIAN] apt install thc-ipv6
        = mdk3                            [DEB-DEBIAN] apt install mdk3
        = ndpexhaust26                    [DEB-DEBIAN] apt install thc-ipv6
        = ndpexhaust6                     [DEB-DEBIAN] apt install thc-ipv6
        = smurf6                          [DEB-DEBIAN] apt install thc-ipv6
        = thcsyn6                         [DEB-DEBIAN] apt install thc-ipv6 
    = • WLAN Stress Testing
        = mdk3                            [DEB-DEBIAN] apt install mdk3
        = reaver                          [DEB-DEBIAN] apt install reaver
    = • WEB Application Fuzzer
        = websploit                       [DEB-DEBIAN] apt install websploit
    = bed                                 [DEB-DEBIAN] apt install bed
    = ohrwurm                             [SOURCE-DEBUILD] debuild && cp -v ohrwurm /usr/bin/
    = sfuzz                               [HTGL-PACKAGES] htgl -i sfuzz
    = uniscan                             [HTGL-PACKAGES] htgl -i uniscan
