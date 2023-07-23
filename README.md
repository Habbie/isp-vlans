# VLAN numbers used by access ISPs

This table attempts to collect VLAN numbers used by various access ISPs around the world.
My initial purpose for this was so that I can avoid using those numbers in my home network.

Based on community contributions, the table now also lists a few non-ISP VLAN numbers that have specific semantics.

You can contribute to this list [via GitHub](https://github.com/Habbie/isp-vlans).

If you are looking for more information on configuring your own equipment with an ISP, [AVM keeps a nice list of links](https://nl.avm.de/service/vrije-modemkeuze/).

| VLAN number | ISPs                                                                                                                                                                  | Access type |
|------------:|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
|           4 | [KPN TV](https://www.kpn.com/service/eigen-apparatuur.htm) ¹⁾                                                                                                         | DHCP        |
|           4 | [tweak.nl TV](https://www.tweak.nl/support/apparatuur-configureren.html)                                                                                              | DHCP        |
|           6 | [KPN Internet](https://www.kpn.com/service/eigen-apparatuur.htm) ¹⁾                                                                                                   | PPPoE       |
|           7 | [KPN Voice](https://www.kpn.com/service/eigen-apparatuur.htm) (on older router models)                                                                                | PPPoE       |
|          34 | [tweak.nl Internet en Bellen](https://www.tweak.nl/support/apparatuur-configureren.html)                                                                              | DHCP        |
|         100 | [Delta Fiber Internet](https://www.delta.nl/klantenservice/vrije-modemkeuze/), [Caiway Fiber](https://www.caiway.nl/klantenservice/vrije-modemkeuze)                  | DHCP        |
|         101 | [Delta Fiber TV](https://www.delta.nl/klantenservice/vrije-modemkeuze/), [Caiway Fiber](https://www.caiway.nl/klantenservice/vrije-modemkeuze)                        | DHCP        |
|         102 | [Delta Fiber Voice](https://www.delta.nl/klantenservice/vrije-modemkeuze/), , [Caiway Fiber](https://www.caiway.nl/klantenservice/vrije-modemkeuze)                   | DHCP        |
|         188 | [Solcon Fiber TV via CAIW-EAS (Delta Fiber Netwerk)](https://www.solcon.nl/particulier/internet/eigen-modem-instellen-en-gebruiken/netwerk-specificatie-caiw-eas/)    | DHCP        |
|         248 | [Online.nl fiber via DFN](https://www.online.nl/klantenservice/internet-en-wifi/eigen-apparatuur/)                                                                    | DHCP        |
|         300 | [T-Mobile.nl VDSL, Fiber Internet](https://www.t-mobile.nl/klantenservice/thuis/internet-wifi/installeren/eigen-modem)                                                | DHCP        |
|         424 | [Freedom.nl TV via Glasvezel Helmond](https://helpdesk.freedom.nl/category-detail/algemene-instellingen-eigen-modem#instellingen-voor-de-glasvezelverbindingen)       | DHCP        |
|         426 | [Freedom.nl Internet via Glasvezel Helmond](https://helpdesk.freedom.nl/category-detail/algemene-instellingen-eigen-modem#instellingen-voor-de-glasvezelverbindingen) | DHCP        |
|         640 | [T-Mobile.nl TV, depending on product](https://www.t-mobile.nl/klantenservice/thuis/internet-wifi/installeren/eigen-modem)                                            | DHCP        |
|   1002-1005 | [Cisco reserved VLANS](https://showipprotocols.blogspot.com/2014/04/default-reserved-vlan-cisco-ios-nx-os.html)                                                       |             |
|        2005 | [Kabel Noord Voice](https://www.kabelnoord.nl/service-en-contact/veelgestelde-vragen/internet/welke-gegevens-heb-ik-nodig-als-ik-mijn-eigen-modem-wil-gebruiken)      | DHCP        |
|        2009 | [Kabel Noord Internet](https://www.kabelnoord.nl/service-en-contact/veelgestelde-vragen/internet/welke-gegevens-heb-ik-nodig-als-ik-mijn-eigen-modem-wil-gebruiken)   | DHCP        |
|        3000 | [SVK Internet](https://www.skv.nl/vrije-modem-keuze/)                                                                                                                 | DHCP        |

¹⁾ these VLAN numbers, especially number 4, are also used by various providers that offer their services over the KPN network or other networks
