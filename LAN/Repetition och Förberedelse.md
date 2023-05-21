---
tags: Repetition
---

Ge ett exempel på en LAN-teknik som använder ring-topologi;;token ring, fddi
Ge ett exempel på en LAN-teknik som använder buss-topologi;;ehternet
<!--SR:!2023-05-22,1,224-->
Vad är den stora fördelen med att bygga nät i mesh-topologi?;;vi har en fysisk redundans
Vad heter accessmetoden i Ethernet?;;CSMA CD eller IEEE 802.3
<!--SR:!2023-05-22,1,224-->
Vad är en switch primära arbetsuppgift, i förhållande till t.ex. en hub?;;separerar kollisionsdomänen
Vad har IP för huvudsakliga arbetsuppgifter?;;adressera och fragmentera
<!--SR:!2023-05-24,3,264-->
Är UDP förbindelselöst eller förbindelseorienterat?;;förbindelselöst
<!--SR:!2023-05-25,4,270-->
Är TCP förbindelselöst eller förbindelseorienterat?;;förbindelseorienterat

Rita TCP ”Three way handshake”, ta med de fält i TCP-huvudet som är viktigast (flaggor och räknare).  
?
![[pULVa8U6xwmr-gACZk8O3BK8slB4PBZm2-jooSz9P_wrbjSFUx_5iHgNJ3KBuLEMqdh-LSUMsI_wiLxJc1w5_WAWwhg-TKlDURlOL3OGi7OwfOX3YTUL6lw9xxDzlZzP.png]]
<!--SR:!2023-05-22,1,230-->

Vilka portnummer brukar räknas som ”well known ports” (Serverportar?) i TCP/UDP?;; 0-1024
<!--SR:!2023-05-22,1,230-->
Nämn 2 routingprotokoll i TCP/IP-stacken.;;RIP, OSPF
<!--SR:!2023-05-22,1,224-->
Är RIP ett Distans Vektor-protokoll eller ett Link State-protokoll?;;Distans
<!--SR:!2023-05-23,2,244-->
Vad används för ”Metric” i RIP?;;Hops/Steps
Vad används för ”Metric” i OSPF?;;Cost på länken
<!--SR:!2023-05-22,1,224-->
Vad betyder E i EIGRP och vad betyder det i praktiken?;;Den klarar variabla
<!--SR:!2023-05-22,1,230-->
Vad innebär VLSM?;;du kan göra subnät av subnät. Ju högre du kommer upp i näten, desto mindre blir de
Hur många bitar har använts i subnetmasken 255.255.255.252 och hur många adresserbara noder kan vi adressera i ett sådant nät?;;30 bitar, 64 och 2 adresserbara
<!--SR:!2023-05-22,1,224-->
Vad heter SAParna som gränsar mellan lager 2 och 3 respektive 3 och 4?;;(SAP är överlämningspunkten) mellan 2o3=Type 3o4=Protocol
<!--SR:!2023-05-23,2,244-->
Vad hanteras av protokollet ARP/R;; Det hanterar översättningen av IP-adresser till MAC-adresser i ett nätverk
<!--SR:!2023-05-22,1,224-->

Vad gör STP?;;förhindrar logiska loopar i nätet. Annars tror alla portar att de äger alla MAC adresserna 
<!--SR:!2023-05-22,1,224-->
Vad gör FHRP?;;First Hop Routing Protocol 
<!--SR:!2023-05-22,1,230-->
Vad betyder HSRP?;;Hot Stand-by Routing Protocol - Du har en virtuell IP adress och en standby router
Vad gör LACP?;;Link Aggregation Control Protocol Slår ihop flera fysiska länkar till en logisk. Kan också användas för att stacka VLAN på varandra
<!--SR:!2023-05-22,1,224-->
Vad betyder NAT?;;Network Adress Translation
<!--SR:!2023-05-22,1,230-->

I RFC 1918 nämns ”Private Address Space” – nämn 3 sådana adressrymder, med korrekt (default) subnet mask
?
![[0PHJNWBk3M2OIDB-zSp42_OTBvPlvu1bsNNJ_OU6uinMrpV7ni5SGCRR4tZluS7d9_cHbYFrBxxpZBAHd6HPLr4s9O4LiUR6tuyn5xEL-xTeTSBuTYIy-516FFERA2A6.png]]
<!--SR:!2023-05-22,1,224-->

Vad är en ACL?;;En paketfiltrering på nätverksinterfacet eller router
Vad gör protokollet DHCP?;;Delar ut temporära nätverksinställningar
<!--SR:!2023-05-23,2,244-->
Är frågan i DHCP och/eller ARP broadcast, multicast eller unicast?;;broadcast
<!--SR:!2023-05-22,1,224-->
Är svaret i DHCP och/eller ARP broadcast, multicast eller unicast?;;unicast
Hur många noder kan du adressera i ett IP-nät med subnetmask 255.255.255.252;;2
<!--SR:!2023-05-22,1,224-->
Hur ser den minsta möjliga subnetmasken ut för ett nät med 40 noder?;;255.255.255.192
<!--SR:!2023-05-22,1,224-->
Vilka två (sorts) adresser läser en switch för att bestämma om en ram ska skickas vidare?;;Mac adress och Source adress
<!--SR:!2023-05-22,1,230-->

Vilket IOS kommando används för att sätta enable lösenordet?
Router (config)#
?
Router (config)# enable secret
<!--SR:!2023-05-23,2,244-->

Vad betyder förkortningen VLSM?;;Variable Length Subnet Mask
<!--SR:!2023-05-24,3,264-->
När man använder CIDR och VLSM – varför är det bäst att adressera ändutrustning (som PC) ”nedifrån och upp” och länknät (med små adressrymder) ”uppifrån och ned”?;;Lättare för nätverket att växa, men framförallt ???
<!--SR:!2023-05-22,1,230-->
Hur ser en 28 bitar subnetmask ut?;;255.255.255.240

Vad är en ”root port” i en STP switch?
?
de som är närmast rot switch blir root port, men de som skickar meddelanden blir forwarding
![[5XQ7mGYPAbT-hVya3vGWkO_2RusiolE2iRbRTSpW1ptsUIL0EmM28mCzaVXTOHnbK1-IlhtfoDJvYWlqT4BVukiR_ImD1VHQy1eDgwY_ZUBQ2F8AGAAJxidD_uFyJLjI.png]]
röda stjärnor är root ports
<!--SR:!2023-05-22,1,230-->

Vad är IPv6's localhost adress?;; `::1` 
<!--SR:!2023-05-24,3,264-->
Vad signaleras på nivå 1 (physical)?;;ettor eller nollor/bits
Vad signaleras på nivå 2 (Data link)?;;frame/ram
Vad signaleras på nivå 3(network)?;;packets
<!--SR:!2023-05-22,1,224-->
hur lång är en MAC adress i bytes?;;6 bytes
<!--SR:!2023-05-24,3,250-->
hur många bytes är en IP adress (IPv4)?;;4 bytes
<!--SR:!2023-05-22,1,224-->
Vilken nivå jobbar switchar på i OSI modellen?;;nivå 2
<!--SR:!2023-05-24,3,264-->
Om de jobbar i VLAN?;;I Sappen "Type"
<!--SR:!2023-05-24,3,250-->
Vad är Switchars primära uppgift?;;att separera kollisionsdomäner
Vad är routers primära uppgift?;;skyfflar trafik mellan end-punkter
<!--SR:!2023-05-22,1,224-->
hur många bitar har vi använt i: 255.255.255.240?;;28
<!--SR:!2023-05-23,2,244-->
Vad för typ av maskning använder OSPF sig utav?;; inverse/reverse maskning (tex 0.0.0.3)
<!--SR:!2023-05-24,3,264-->
STP (Spanning Tree Protocol) är ett switchningsprotokoll, men hur beter sig den som?;; ett routingkontroll
I STP (Spanning Tree Protocol), använder man route eller root?;;root
<!--SR:!2023-05-25,4,270-->
Är STP (Spanning Tree Protocol) en routing teknik?;; NEJ!
Vilket portnummer använder HTTP och använder den TCP eller UDP?;; Port 80 och TCP
<!--SR:!2023-05-24,3,264-->
Vilket portnummer använder FTP och använder den TCP eller UDP?;; Port 21 och TCP
<!--SR:!2023-05-24,3,250-->
Vilket portnummer använder SMTP och använder den TCP eller UDP?;; Port 25 och TCP
Vilket portnummer använder SSH och använder den TCP eller UDP?;; Port 22 och TCP
Vilket portnummer använder DNS och använder den TCP eller UDP?;; Port 53 och UDP
<!--SR:!2023-05-22,1,224-->
Vilket portnummer använder DHCP och använder den TCP eller UDP?;; Port 67+68 och UDP

What kind of topology is this and what does it send?
![[Pasted image 20230521175026_2.png]]
?
![[Pasted image 20230521175026.png]]