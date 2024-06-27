### DNS Providers

Without using a secure, privacy-centric DNS all your web requests can be
seen in the clear. You should configure your DNS queries to be managed by
a service that respects privacy and supports DNS-over-TLS, DNS-over-HTTPS or DNSCrypt.

- **[<img src='https://developers.cloudflare.com/assets/icon-512x512-fe4c8fe4.png' width='16' height='16' alt='icon' /> CloudFlare](https://developers.cloudflare.com/1.1.1.1/setting-up-1.1.1.1)** - One of the most performant options, Cloudflare's DNS supports DoH and DoT, and has a Tor
implementation, providing world-class protection. They have native cross-platform apps,
for easy set-up.
[…](https://awesome-privacy.xyz/networking/dns-providers/cloudflare "View full CloudFlare report") 
	- <details>
		<summary>Stats</summary>

		 [![Privacy Policy](https://shields.tosdr.org/en_893.svg)](https://tosdr.org/en/service/893) [![CloudFlare on Awesome Privacy](https://img.shields.io/badge/View%20Report-FC60A8?style=flat&logo=awesomelists&label=CloudFlare)](https://awesome-privacy.xyz/networking/dns-providers/cloudflare) 
🛡️ Security Audited ˙ 

		</details>
- **[<img src='https://cdn.adguard.info/website/adguard-dns.io/favicon.svg' width='16' height='16' alt='icon' /> AdGuard](https://adguard.com/en/adguard-dns/overview.html)** - Open-source DNS provider, specialising in the blocking of ads, trackers and malicious domains.
They have been independently audited and do not keep logs.
[…](https://awesome-privacy.xyz/networking/dns-providers/adguard "View full AdGuard report") 
	- <details>
		<summary>Stats</summary>

		 [![Privacy Policy](https://shields.tosdr.org/en_2776.svg)](https://tosdr.org/en/service/2776) [![AdGuard on Awesome Privacy](https://img.shields.io/badge/View%20Report-FC60A8?style=flat&logo=awesomelists&label=AdGuard)](https://awesome-privacy.xyz/networking/dns-providers/adguard) 
˙ 

		</details>
- **[<img src='https://nextdns.io/favicon.ico' width='16' height='16' alt='icon' /> NextDNS](https://nextdns.io)** - An ad-blocking, privacy-protecting, censorship-bypassing DNS. Also comes with analytics, and
the ability to shield kids from adult content.
[…](https://awesome-privacy.xyz/networking/dns-providers/nextdns "View full NextDNS report") 
	- <details>
		<summary>Stats</summary>

		 [![Privacy Policy](https://shields.tosdr.org/en_1959.svg)](https://tosdr.org/en/service/1959) [![NextDNS on Awesome Privacy](https://img.shields.io/badge/View%20Report-FC60A8?style=flat&logo=awesomelists&label=NextDNS)](https://awesome-privacy.xyz/networking/dns-providers/nextdns) 
˙ 

		</details>

<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> Using an encrypted DNS resolver will not make you anonymous, it just makes
it harder for third-partied to discover your domain history.
If you are using a VPN, take a [DNS leak test](https://www.dnsleaktest.com/),
to ensure that some requests are not being exposed.


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> - [Quad9](https://www.quad9.net) - A well-funded, performant DNS with a strong focus on privacy and security and easy set-up, however questions have been raised about the motivation of some of the financial backers.
> - [BlahDNS](https://blahdns.com) - (Japan, Finland or Germany) is an excellent security-focused DNS> - [OpenNIC](https://www.opennic.org/) - [NixNet DNS](https://nixnet.services/dns) and [UncensoredDNS](https://blog.uncensoreddns.org) are open source and democratic, privacy-focused DNS
> - [Unbound](https://nlnetlabs.nl/projects/unbound/about) - A validating, recursive, caching DNS resolver, designed to be fast and lean. Incorporates modern features and based on open standards
> - [Clean Browsing](https://cleanbrowsing.org) - A good option for protecting kids, they offer comprehensive DNS-based Content Filtering
> - [Mullvad](https://mullvad.net/en/help/dns-over-https-and-dns-over-tls) - Mullvads public DNS with QNAME minimization and basic ad blocking. It has been audited by the security experts at Assured. You can use this privacy-enhancing service even if you don't use Mullvad.
</details>

<details>
<summary>ℹ️ <b>Further Info</b></summary>

> #### DNS Protocols

DNS-over-TLS was proposed in [RTC-7858](https://tools.ietf.org/html/rfc7858)
by the IETF, then 2 years later, the DNS-over-HTTPS specification was outlined
in [RFC8484](https://tools.ietf.org/html/rfc8484) in October '18.
[DNSCrypt](https://dnscrypt.info/), is a protocol that authenticates communications
between a DNS client and a DNS resolver. It prevents DNS spoofing, through
using cryptographic signatures to verify that responses originate from the
chosen DNS resolver, and haven't been tampered with. DNSCrypt is a well
battle-tested protocol, that has been in use since 2013, and is still widely used.
</details>

### DNS Clients

- **[<img src='https://dnscrypt.info/favicon.ico' width='16' height='16' alt='icon' /> DNScrypt-proxy 2](https://dnscrypt.info)** - A flexible DNS proxy, with support for modern encrypted DNS protocols including DNSCrypt V2,
DNS-over-HTTPS and Anonymized DNSCrypt. Also allows for advanced monitoring, filtering, caching
and client IP protection through Tor, SOCKS proxies or Anonymized DNS relays.
[…](https://awesome-privacy.xyz/networking/dns-clients/dnscrypt-proxy-2 "View full DNScrypt-proxy 2 report") 
	- <details>
		<summary>Stats</summary>

		[![GitHub: DNSCrypt/dnscrypt-proxy](https://img.shields.io/github/stars/DNSCrypt/dnscrypt-proxy?style=flat&logo=github&label=dnscrypt-proxy&color=%235f53f4&cacheSeconds=3600)](https://github.com/DNSCrypt/dnscrypt-proxy)  [![DNScrypt-proxy 2 on Awesome Privacy](https://img.shields.io/badge/View%20Report-FC60A8?style=flat&logo=awesomelists&label=DNScrypt-proxy_2)](https://awesome-privacy.xyz/networking/dns-clients/dnscrypt-proxy-2) 
˙ 

		</details>
- **[<img src='https://nlnetlabs.nl/extra/favicons/favicon-196x196.png' width='16' height='16' alt='icon' /> Unbound](https://nlnetlabs.nl/projects/unbound)** - Validating, recursive, caching DNS resolve with support for DNS-over-TLS. Designed to be fast,
lean, and secure Unbound incorporates modern features based on open standards. It's fully open
source, and recently audited. (For an in-depth tutorial, see this article by DNSWatch.)
[…](https://awesome-privacy.xyz/networking/dns-clients/unbound "View full Unbound report") 
	- <details>
		<summary>Stats</summary>

		[![GitHub: NLnetLabs/unbound](https://img.shields.io/github/stars/NLnetLabs/unbound?style=flat&logo=github&label=unbound&color=%235f53f4&cacheSeconds=3600)](https://github.com/NLnetLabs/unbound) [![Privacy Policy](https://shields.tosdr.org/en_2519.svg)](https://tosdr.org/en/service/2519) [![Unbound on Awesome Privacy](https://img.shields.io/badge/View%20Report-FC60A8?style=flat&logo=awesomelists&label=Unbound)](https://awesome-privacy.xyz/networking/dns-clients/unbound) 
˙ 

		</details>
- **[<img src='https://raw.githubusercontent.com/Ch4t4r/Nebulo/master/app/src/main/res/mipmap-xxhdpi/ic_launcher.png' width='16' height='16' alt='icon' /> Nebulo](https://nebulo.app)** - Non-root, small-sized DNS changer utilizing DNS-over-HTTPS and DNS-over-TLS. (Note, since this
uses Android's VPN API, it is not possible to run a VPN while using Nebulo.)
[…](https://awesome-privacy.xyz/networking/dns-clients/nebulo "View full Nebulo report") 
	- <details>
		<summary>Stats</summary>

		[![GitHub: Ch4t4r/Nebulo](https://img.shields.io/github/stars/Ch4t4r/Nebulo?style=flat&logo=github&label=Nebulo&color=%235f53f4&cacheSeconds=3600)](https://github.com/Ch4t4r/Nebulo)  [![Nebulo on Awesome Privacy](https://img.shields.io/badge/View%20Report-FC60A8?style=flat&logo=awesomelists&label=Nebulo)](https://awesome-privacy.xyz/networking/dns-clients/nebulo) 
📦 Open Source ˙ 

		</details>
- **[<img src='https://rethinkdns.com/ico/app_icon.svg' width='16' height='16' alt='icon' /> RethinkDNS & Firewall](https://rethinkdns.com/app)** - Free and open source DNS changer with support for DNS-over-HTTPS, DNS-over-Tor, and DNSCrypt v3
with Anonymized Relays. (Note, since this uses Android's VPN API, it is not possible to run a
VPN while using RethinkDNS + Firewall.)
[…](https://awesome-privacy.xyz/networking/dns-clients/rethinkdns-and-firewall "View full RethinkDNS & Firewall report") 
	- <details>
		<summary>Stats</summary>

		[![GitHub: celzero/rethink-app](https://img.shields.io/github/stars/celzero/rethink-app?style=flat&logo=github&label=rethink-app&color=%235f53f4&cacheSeconds=3600)](https://github.com/celzero/rethink-app) [![Privacy Policy](https://shields.tosdr.org/en_4691.svg)](https://tosdr.org/en/service/4691) [![RethinkDNS & Firewall on Awesome Privacy](https://img.shields.io/badge/View%20Report-FC60A8?style=flat&logo=awesomelists&label=RethinkDNS_&_Firewall)](https://awesome-privacy.xyz/networking/dns-clients/rethinkdns-and-firewall) 
˙ 

		</details>
- **[<img src='https://github.com/s-s/dnscloak/blob/master/src/images/logo.png?raw=true' width='16' height='16' alt='icon' /> DNS Cloak](https://apps.apple.com/us/app/dnscloak-secure-dns-client/id1452162351)** - Simple all that allows for the use for dnscrypt-proxy 2 on an iPhone.
[…](https://awesome-privacy.xyz/networking/dns-clients/dns-cloak "View full DNS Cloak report") 
	- <details>
		<summary>Stats</summary>

		[![GitHub: s-s/dnscloak](https://img.shields.io/github/stars/s-s/dnscloak?style=flat&logo=github&label=dnscloak&color=%235f53f4&cacheSeconds=3600)](https://github.com/s-s/dnscloak)  [![DNS Cloak on Awesome Privacy](https://img.shields.io/badge/View%20Report-FC60A8?style=flat&logo=awesomelists&label=DNS_Cloak)](https://awesome-privacy.xyz/networking/dns-clients/dns-cloak) 
˙ 

		</details>
- **[<img src='https://dnsprivacy.org/images/favicon.png' width='16' height='16' alt='icon' /> Stubby](https://dnsprivacy.org/wiki/display/DP/DNS+Privacy+Daemon+-+Stubby)** - Acts as a local DNS Privacy stub resolver (using DNS-over-TLS). Stubby encrypts DNS queries sent
from a client machine (desktop or laptop) to a DNS Privacy resolver increasing end user privacy.
Stubby can be used in combination with Unbound - Unbound provides a local cache and Stubby manages
the upstream TLS connections (since Unbound cannot yet re-use TCP/TLS connections),
see example configuration.
[…](https://awesome-privacy.xyz/networking/dns-clients/stubby "View full Stubby report") 
	- <details>
		<summary>Stats</summary>

		[![GitHub: getdnsapi/stubby](https://img.shields.io/github/stars/getdnsapi/stubby?style=flat&logo=github&label=stubby&color=%235f53f4&cacheSeconds=3600)](https://github.com/getdnsapi/stubby)  [![Stubby on Awesome Privacy](https://img.shields.io/badge/View%20Report-FC60A8?style=flat&logo=awesomelists&label=Stubby)](https://awesome-privacy.xyz/networking/dns-clients/stubby) 
˙ 

		</details>
