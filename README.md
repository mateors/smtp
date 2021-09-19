# DNS Server

## Power DNS Setup Guide
https://damyan.blog/post/iac-series-dns-part-1/

## How to check a remote port open or not?
> nc -z -v -w5 <host> <port> \
> For a quick interactive check (with a 5 seconds timeout): \
> nc -z -v -w5 74.208.181.199 53 

## Raw DNS Query and Answer
https://github.com/vishen/go-dnsquery

Handwritye DNS
https://routley.io/posts/hand-writing-dns-messages/

https://datatracker.ietf.org/doc/html/rfc1035#page-26

## Protocols-dns-query
https://www.firewall.cx/networking-topics/protocols/domain-name-system-dns/160-protocols-dns-query.html

## Python-binascii-unhexlify-method
https://stackoverflow.com/questions/55699760/go-how-to-implement-python-binascii-unhexlify-method


https://www.jwillikers.com/opensmtpd-ubuntu

https://coderwall.com/p/eejzja/simple-smtp-server-with-opensmtpd
https://www.mailboxvalidator.com/resources/articles/smtp-commands-rfc/

https://marc.info/?l=python-bugs-list&m=128078525530978&w=2


## DNS Resolver Understanding 
https://ops.tips/blog/raw-dns-resolver-in-go/
https://github.com/cirocosta/rawdns/

## Golang DNS implementation
https://gist.github.com/walm/0d67b4fb2d5daf3edd4fad3e13b162cb


## Power DNS
https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-powerdns-with-a-mariadb-backend-on-ubuntu-14-04
https://www.linode.com/docs/guides/email-with-postfix-dovecot-and-mariadb-on-centos-7/

## Authoritative Nameserver
> An authoritative Nameserver is a nameserver (DNS Server) that holds the actual DNS records (A, CNAME, PTR, etc) for a particular domain/ address. A recursive resolver would be a DNS server that queries an authoritative nameserver to resolve a domain/ address.

## Setup PowerDNS on Ubuntu 20.04

https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-powerdns-with-a-mariadb-backend-on-ubuntu-14-04

https://kifarunix.com/easily-install-and-setup-powerdns-on-ubuntu-20-04/
https://www.claudiokuenzler.com/blog/1055/how-to-bulk-mass-change-dns-records-powerdns-mysql-backend

https://computingforgeeks.com/install-powerdns-and-powerdns-admin-on-ubuntu-debian/

https://doc.powerdns.com/authoritative/migration.html

https://doc.powerdns.com/authoritative/backends/generic-mysql.html

https://github.com/PowerDNS/pdns

## Database Schema
https://github.com/PowerDNS/pdns/blob/master/modules/gmysqlbackend/schema.mysql.sql

## Install Mariadb
https://www.digitalocean.com/community/tutorials/how-to-install-mariadb-on-ubuntu-18-04


## NSD
https://www.digitalocean.com/community/tutorials/how-to-use-nsd-an-authoritative-only-dns-server-on-ubuntu-14-04

## Check port 53
> netstat -apn|grep 53

## Go SMtP
https://github.com/matoous/gosmtp

## Maddy
https://github.com/foxcpp/maddy

## chasquid
https://github.com/albertito/chasquid

## docker-mailserver
https://github.com/docker-mailserver/docker-mailserver


## how_email_works
https://www.oasis-open.org/khelp/kmlm/user_help/html/how_email_works.html

https://www.computernetworkingnotes.com/networking-tutorials/how-email-works-step-by-step-explained.html

https://www.interserver.net/tips/kb/exactly-emails-works-steps-explanation/
