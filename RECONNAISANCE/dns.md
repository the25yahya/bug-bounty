### whois an reverse whois
- You might be able to find the associated
contact information, such as an email, name, address, or phone number:
$ whois facebook.com
- You could then conduct a reverse WHOIS search, searching a database by
using an organization name, a phone number, or an email address to find
domains registered with it. This way, you can find all the domains that belong
to the same owner. Reverse WHOIS is extremely useful for finding obscure or
internal domains not otherwise disclosed to the public. Use a public reverse
WHOIS tool like ViewDNS.info (https://viewdns.info/reversewhois/) to conduct
this search. WHOIS and reverse WHOIS will give you a good set of top-level
domains to work with.

### mapping ASN's to ip adressses 
- $ whois -h whois.cymru.com 157.240.2.20 : The -h flag in the whois command sets the WHOIS server to retrieve
information from, and whois.cymru.com is a database that translates IPs to
ASNs. If the company has a dedicated IP range and doesn’t mark those
addresses as out of scope, you could plan to attack every IP in that range.

### ssl certs parsing 
- Another way of finding hosts is to take advantage of the Secure Sockets Layer
(SSL) certificates used to encrypt web traffic. An SSL certificate’s Subject
Alternative Name field lets certificate owners specify additional hostnames
that use the same certificate, so you can find those hostnames by parsing this
field. Use online databases like crt.sh, Censys, and Cert Spotter to find certificates for a domain. 

