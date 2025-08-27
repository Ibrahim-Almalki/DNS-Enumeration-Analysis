# DNS-Enumeration-Analysis
Overview

This project explores the process of DNS enumeration, analyzing records for domains such as example.com and google.com. Using tools like Amass, it uncovers name server (NS) records, CNAME records, and IP addresses through both passive and active scanning techniques.

Details

Tools Used: Amass

Domains Analyzed:

example.com (NS records: a.iana-servers.net, b.iana-servers.net; CNAME: www.example.com-v4.edgesuite.net)

google.com (NS records: ns1.google.com, ns2.google.com, etc.; IP addresses: 216.239.32.10, etc.)

Techniques: Passive and active enumeration

Purpose

The goal is to demonstrate how DNS enumeration can reveal critical infrastructure details, useful for security research and network analysis.

Screenshots

example.com DNS Results

google.com DNS Results

Getting Started



Run enumeration: amass enum -passive -d example.com or amass enum -active -d google.com
