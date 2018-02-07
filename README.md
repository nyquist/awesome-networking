# Awesome Networking Resources [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
An [awesome list](https://github.com/sindresorhus/awesome) of resources to design, implement and operate computer networks.

# Contents
- [Network Design Resources](#network-design-resources)
- [Network Implementation](#network-implementation)
  - [Routing](#routing)
    - [SD-WAN](#sd-wan)
  - [Switching](#switching)
  - [VPN](#vpn)
  - [Network Services](#network-services)
  - [Network Simulators and Traffic Generators](#network-simulators-and-traffic-generators)
- [Network Operations](#network-operations)
  - [Network Automation](#network-automation)
  - [Network Monitoring](#network-monitoring)
  - [Security Monitoring](#security-monitoring)
  - [Network Inventory](#network-inventory) 
- [Related resources](#related-resources)
  - [DevOps Tools](#devops-tools)
  - [DevOps Monitoring](#devops-monitoring)
  - [DevOps Knowledgebase](#devops-knowledgebase)
  - [DevOps Inventory](#devops-inventory)

# Network Design Resources
- [Cisco Design Zone](https://www.cisco.com/c/en/us/solutions/design-zone.html#~stickynav=1) - Cisco Design Guides

# Network Implementation
## Routing
- [VyOS](https://vyos.io/) - VyOS is an open source network operating system that can be installed on physical hardware or a virtual machine on your own server, or a cloud platform
### SD-WAN
- [Silver Peak](https://www.silver-peak.com/) - SD-WAN Solution(Commercial)
## Switching

## VPN
- [PiVPN](http://www.pivpn.io/) - Simplest OpenVPN setup and configuration, designed for Raspberry Pi.

## Network Services
- [Pi-Hole](https://pi-hole.net/) - Network-wide ad blocking via your own Linux hardware

## Network Simulators and Traffic Generators
- [GNS3](https://www.gns3.com/) - Graphical Network Simulator-3 is a network software emulator first released in 2008. It allows the combination of virtual and real devices, used to simulate complex networks. It uses Dynamips emulation software to simulate Cisco IOS
- [Mininet](http://mininet.org/) - An Instant Virtual Network on your Laptop
- [WANem](http://wanem.sourceforge.net/) - WANem is a Wide Area Network Emulator
- [Ostinato](https://ostinato.org/) - Ostinato is a packet crafter, network traffic generator and analyzer with a friendly GUI
- [SIPp](http://sipp.sourceforge.net/index.html) - SIPp is a free Open Source test tool / traffic generator for the SIP protocol.
- [StarTrinity SIP Tester™](http://startrinity.com/VoIP/SipTester/SipTester.aspx) - (call generator, simulator) - VoIP monitoring and testing tool, VoIP recorder

# Network Operations
## Network Automation
- [Napalm](https://napalm-automation.net/) - Napalm is a vendor neutral, cross-platform open source project that provides a unified API to network devices
- [netmiko](https://github.com/ktbyers/netmiko) - Multi-vendor library to simplify Paramiko SSH connections to network devices
- [trigger](https://github.com/trigger/trigger) - Trigger is a robust network automation toolkit written in Python that was designed for interfacing with network devices.
- [Ansible](https://github.com/ansible/ansible) - Ansible is a radically simple IT automation platform that makes your applications and systems easier to deploy. Avoid writing scripts or custom code to deploy and update your applications— automate in a language that approaches plain English, using SSH, with no agents to install on remote systems.

## Network Monitoring
- [perfSONAR](https://www.perfsonar.net) - perfSONAR is a network measurement toolkit designed to provide federated coverage of paths, and help to establish end-to-end usage expectations
- [UDPing](https://github.com/yahoo/UDPing) - The purpose of UDPing is to measure latency and packet loss across a link
- [veryflow](https://www.veriflow.net/) - continuous network verification
- [Forward Networks](https://www.forwardnetworks.com/) - Network Behavior Analysis (Commercial)
- [ToDD](https://github.com/toddproject/todd) - "Testing on Demand: Distributed!"
- [pmacct](http://www.pmacct.net/) - pmacct is a small set of multi-purpose passive network monitoring tools

## Security Monitoring
- [Smart Investigator](http://www.smart-investigator.com/) - Event Identification and Management (Commercial)
- [cPacket](https://www.cpacket.com) - cPacket Networks provides performance monitoring solutions that deliver real-time analysis and coverage (Commercial)
- [Proxmox Mail Gateway](https://www.proxmox.com/en/proxmox-mail-gateway) - Proxmox Mail Gateway is the leading open-source email security solution helping you to protect your mail server against all email threats the moment they emerge.

## Network Inventory
- [phpipam](https://phpipam.net/) - phpipam is an open-source web IP address management application (IPAM)
- [nsot](https://github.com/dropbox/nsot) - Network Source of Truth is an open source IPAM and network inventory database
- [netbox](https://github.com/digitalocean/netbox) - IP address management (IPAM) and data center infrastructure management (DCIM) tool.


# Related resources
## DevOps Tools
- [Celery](http://www.celeryproject.org/) - Celery is an asynchronous task queue/job queue based on distributed message passing.	It is focused on real-time operation, but supports scheduling as well.
- [Ajenti](http://ajenti.org/) - An admin's tool for a more civilized age, providing you with a fast and secure way to manage a remote Linux box at any time using everyday tools like a web terminal, text editor, file manager and others.
- [ProxMox Virtualiation Platform](https://www.proxmox.com/en/proxmox-ve) - Proxmox VE is a complete open-source platform for all-inclusive enterprise virtualization that tightly integrates KVM hypervisor and LXC containers, software-defined storage and networking functionality on a single platform, and easily manages high availability clusters and disaster recovery tools with the built-in web management interface.

## DevOps Monitoring
- [netdata](https://github.com/firehol/netdata) - netdata is a system for distributed real-time performance and health monitoring.
- [Grafana](https://grafana.com/) - open source software for time series analytics
- [monit](https://mmonit.com/monit/) - Monit is a small Open Source utility for managing and monitoring Unix systems. Monit conducts automatic maintnance and repair and can execute meaningful causal actions in error situations.
- [Prometheus](https://prometheus.io/) - Prometheus is an open-source systems monitoring and alerting toolkit originally built at SoundCloud
- [sensu](https://sensuapp.org/) - Monitor servers, services, application health, and business KPIs. Collect and analyze custom metrics. Get notified about failures before your users do. Give your business the competitive advantage it deserves. (Open Source or Commercial)
- ELK Stack
  - [Elasticsearch](https://github.com/elastic/elasticsearch) - Open Source, Distributed, RESTful Search Engine 
  - [LogStash](https://github.com/elastic/logstash) - Logstash - transport and process your logs, events, or other data
  - [Kibana](https://github.com/elastic/kibana) - Kibana analytics and search dashboard for Elasticsearch

### DevOps Knowledgebase
- [ITGlue](https://www.itglue.com/) - IT focused documentation solution (Commercial)

### DevOps Inventory
- [Snipe IT](https://snipeitapp.com/) - Open Source Asset Management



