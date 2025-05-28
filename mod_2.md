Network protocols = pravidla a standardy, které určují, jak spolu komunikují zařízení v síti. 
    Určují: pořadí doručování dat
            strukturu dat
            jak začít, udržet a ukončit spojení


TCP = internetový komunikační protokol, který umožňuje dvěma zařízením navázat spojení a přenášet data

ARP (adress resolution protocol) = siťový protokol používaný k určení MAC adresy dalšího routeru nebo zařízení na cestě


HTTPS (hyper text transfer protocol) = síťový protokol, který poskytuje zabezpečenou metodu komunikace mezi klientem a serverem

DNS = síťový protokol, který překládá jména internetových domén na IP adresy 

IEEE 802.11 (WiFi) = set standardů, které definují komunikaci pro bezdrázová LAN zařízení

WiFi protected Access (WPA) = bezdrátový bezpečnostní protokol pro zařízení připojených k internetu --> dnes WPA2 a WPA3

Firewall = zařízení pro zabezpečení sítě, které monitoruje datový provoz přicházející do sítě odcházející z ní

Port filtering = funkce firewallu, která blokuje nebo povoluje určité porty za účelem omezení nechtěné komunikace 

hardware firewall = fyzické zařízení které blokuje

software firewall = softwarová aplikace instalovaná na počítači nebo serveru

Cloud-based firewalls = software firewalls, které jsou hostovány na cloudu

Stateful = typ firewallu, který sleduje informace procházející skrz něj a aktivně filtruje hrozby

Stateless = typ firewallu, který funguje na základě předem definovaných pravidel a nesleduje informace z datových paketů

Výhody firewallů nové generace (NGFWs):
    hluboká kontrola paketů
    ochrana před průniky
    zpravodajství o hrozbách

VPN (virtual private network) = síťová bezpečnostní služba, který změní mojí veřejnou IP adresu a skryje mojí virtuální polohu, aby moje data zůstala soukromá při používání veřejné sítě, například internet

Encapsulation (zapouzdření) = proces prováděný VPN službou, který chrání naše data tak, že citlivá data zabalí do jiných datových paketů

Security zone = segment (část) sítě, která chrání interní síť před internetem

Network segmentation = bezpečnostní technika, která rozděluje síť na segmenty (části)

Uncontrolled zone = část internetu nebo sítě, kterou firma nemá pod kontrolou

Controlled zone = ochranná vrstva mezi nebezpečným internetem (uncontrolled zone) a vnitřní sítí firmy

Oblasti kontrolované zóny : Demilitarizovaná zóna (DMZ)
                            Interní síť
                            Zakázaná zóna

Subnetting = rozdělení jedné počítačové sítě na menší části, zvané podsítě (subnets)

Proxy server = server, který vyřizuje požadavky klienta tím, že je přeposílá na jiné servery, přidává zabezpečení

Forward proxy server = reguluje a omezuje přístup osoby k internetu, uživatel posílá požadavek na forward proxy server, ten ho pošle dál na cílový web, webová stránka neuvidí uživatele přímo, ale jen přes proxy server

Reverse proxy server = reguluje a omezuje přístup internetu k internímu serveru, uživatel posílá požadavek na proxy server, ale ten netuší, kolik a jakých serverů je "za ním"

NAT (network adress translation) = překládá IP adresy mezi soukromou a veřejnou sítí

WireGuard VPN = vysokorychlostní VPN protokol, pokročilé šifrování

IPSec VPN = VPN protokol, také šifruje data, je starší, více komplexní