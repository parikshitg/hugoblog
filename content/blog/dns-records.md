---
title: "DNS records simplified"
date: 2019-10-30T15:59:40+05:30
author: "Naeem Hadiq"
featured_image: "/img/blog/dns-records.jpg"
categories: ["Web Development"]
type: "blog"
draft: false
---
<p>Confused by A, CNAME, ALIAS and all the sort of records??</p>
<p>Getting confused is easy. Let's try to go to the base of it and explain them one by one.</p>
<p><b>Domain Name System (DNS)</b> is the way search engines translate your website to the server address. which means translating a domain such as example.com to its IP address to communicate to.</p>
<p>When you register a domain there are multiple types of Domain Name Service Records you can set up.
</p>

<p>Each of these records has a Type, a Hostname and a Value</p>
<ul>
	<li>”Types” are Predefined</li>
	<li>“Host” represents the root(@) or a sub domain (www,test etc)</li>
	<li>“Value” is an IP or Web address or a text value.</li>
</ul>

<h2>A Record</h2>
<p>Maps a subdomain to its corresponding IPv4 address.
It is most commonly used at the root, and tells the browser where example.com lives.</p>

<h2>AAAA Record</h2>
<p>Its the IPv6 equivalent of an A Record.</p>

<h2>CNAME</h2>
<p>Maps a subdomain to another domain.
This can be a subdomain in the same site(www to root) or a totally different website such as an AWS Service or a Heroku instance where you run your app.CNAME however has a major disadvantage. Once a CNAME is defined for a subdomain no other records can be defined for the same subdomain.
CNAME implemented at root i.e(@) means you no longer can use any other records with the root domain.</p>

<h2>ALIAS or ANAME</h2>
<p>It is the workaround to a CNAME for subdomains that require other records to exist.
ALIAS or ANAME is exactly like a CNAME except it is a non-standard DNS Type and allows other records such as TXT & MX to exist.</p>

<h2>TXT Record</h2>
<p>It is a record that can pass extra information to a computer reading this DNS Record. It can be utilized to prove you own a domain as it can only be set up by the person with root-level/Owner level access to the configurator.</p>

<h2>MX Record</h2>
<p>It is a Mail eXchange Record used to specify that other servers such as Google or Microsoft exchange are used to manage and handle your emails.
MX records are unique and have options to point to multiple servers depending on the priority of each independent record.</p>

<p>The above said is the most commonly used DNS records the other types of records that exist are very rarely or never used in normal day to day use cases.
For each of the above records, we also specify a TTL (Time To Live) it basically tells the server, how long to cache DNS Values.
TTL is one of the reasons why new domain records take time to propagate and be valid.
DNS Servers, ISP’s and even system cache DNS records and keep serving old values till the TTL runs out and the server fetches the new records.</p>
