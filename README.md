# Awesome Computer Networking Resources [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
An [awesome list](https://github.com/sindresorhus/awesome) of resources to design, implement and operate computer networks.

# Contents
- [Network Design Resources](#network-design-resources)
- [Network Implementation](#network-implementation)
  - [Routing](#routing)
  - [Switching](#switching)
  - [VPN](#vpn)
  - [Network Services](#network-services)
  - [Network Simulators and Traffic Generators](#network-simulators-and-traffic-generators)
- [Network Operations](#network-operations)
  - [Network Change Management](#network-change-management)
  - [Network Automation](#network-automation)
  - [Network Monitoring](#network-monitoring)
  - [Security Monitoring](#security-monitoring)
  - [Network Inventory](#network-inventory) 
- [Related resources](#related-resources)
  - [DevNet Tools](#devnet-tools)
  - [DevNet Monitoring](#devnet-monitoring)
  - [DevNet Knowledgebase](#devnet-knowledgebase)
  - [DevNet Inventory](#devnet-inventory)
  - [Knowledge Resources](#knowledge-resources)
  

# Network Design Resources
- [Cisco Design Zone](https://www.cisco.com/c/en/us/solutions/design-zone.html#~stickynav=1)
- [Cumulus Networks Validated Design Guides](https://cumulusnetworks.com/learn/web-scale-networking-resources/?validated-design-guides) 
- [Juniper Solution Center](https://www.juniper.net/documentation/en_US/release-independent/solutions/information-products/pathway-pages/solutions/index.html)



# Network Implementation
## Routing
- [Free Range Routing](https://frrouting.org/) - IP routing protocol suite for Linux and Unix platforms which
includes protocol daemons for BGP, IS-IS, LDP, OSPF, PIM, and RIP.
- [VyOS](https://vyos.io/) - Open source network operating system that can be installed on physical hardware or a virtual machine on your own server, or a cloud platform.

### SD-WAN
- [Silver Peak](https://www.silver-peak.com/) - SD-WAN Solution(Commercial).
## Switching
- [snabb](https://github.com/snabbco/snabb) - Snabb (formerly "Snabb Switch") is a simple and fast packet networking toolkit.

## VPN
- [PiVPN](http://www.pivpn.io/) - Simplest OpenVPN setup and configuration, designed for Raspberry Pi.

## Network Services
- [Pi-Hole](https://pi-hole.net/) - Network-wide ad blocking via your own Linux hardware.

## Network Simulators and Traffic Generators
- [GNS3](https://www.gns3.com/) - Network software emulator that allows the combination of virtual and real devices, used to simulate complex networks.
- [Mininet](http://mininet.org/) - Instant Virtual Network on your Laptop.
- [WANem](http://wanem.sourceforge.net/) - Wide Area Network Emulator.
- [Ostinato](https://ostinato.org/) - Packet crafter, network traffic generator and analyzer with a friendly GUI.
- [SIPp](http://sipp.sourceforge.net/index.html) - Free Open Source test tool / traffic generator for the SIP protocol.
- [StarTrinity SIP Tester™](http://startrinity.com/VoIP/SipTester/SipTester.aspx) - VoIP monitoring and testing tool, VoIP recorder.
- [Multi-Generator](https://www.nrl.navy.mil/itd/ncs/products/mgen) - Open source software that provides the ability to perform IP network performance tests and measurements using TCP and UDP/IP traffic.
- [Network-Conditions-Emulator](https://github.com/marty90/Network-Conditions-Emulator) - Artificially limit uplink and downlink bandwidth, delay and loss rate on selected interfaces.
- [snabb](https://github.com/snabbco/snabb) - Snabb (formerly "Snabb Switch") is a simple and fast packet networking toolkit.
- [vqfx10k-vagrant](https://github.com/juniper/vqfx10k-vagrant) - Vagrant files to bring up Juniper virtual QFX instances


# Network Operations
## Network Change Management
- [Batfish](https://github.com/batfish/batfish) - Network configuration analysis tool that can find bugs and guarantee the correctness of (planned or current) network configurations.
- [Oxidized](https://github.com/ytti/oxidized) - Network device configuration backup tool. It's a [RANCID](http://www.shrubbery.net/rancid/) replacement.
- [Netshot](http://www.netfishers.onl/netshot) - Network configuration and compliance management software.
- [Jazigo](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple devices, similar to rancid, fetchconfig, oxidized, Sweet.
- [fetchconfig](https://github.com/udhos/fetchconfig) - fetchconfig is a Perl script for retrieving configuration of
	multiple devices
- [sweet](https://github.com/AppliedTrust/sweet) - Network device configuration backups and change alerts for the 21st century - inspired by RANCID!
## Network Automation
- [Napalm](https://napalm-automation.net/) - Vendor neutral, cross-platform open source project that provides a unified API to network devices.
- [netmiko](https://github.com/ktbyers/netmiko) - Multi-vendor library to simplify Paramiko SSH connections to network devices.
- [trigger](https://github.com/trigger/trigger) - Robust network automation toolkit written in Python that was designed for interfacing with network devices.
- [Ansible](https://github.com/ansible/ansible) - IT automation platform that makes your applications and systems easier to deploy by using SSH, with no agents to install on remote systems.
- [nornir](https://github.com/nornir-automation/nornir) - Pluggable multi-threaded framework with inventory management to help operate collections of devices

## Network Monitoring
- [perfSONAR](https://www.perfsonar.net) - Network measurement toolkit designed to provide federated coverage of paths, and help to establish end-to-end usage expectations.
- [UDPing](https://github.com/yahoo/UDPing) - Measure latency and packet loss across a link.
- [Vaping](https://github.com/20c/vaping) - vaping is a healthy alternative to smokeping!
- [veryflow](https://www.veriflow.net/) - Continuous network verification system.
- [Forward Networks](https://www.forwardnetworks.com/) - Network Behavior Analysis (Commercial).
- [ToDD](https://github.com/toddproject/todd) - Distributed, testing-on-demand system focused on testing network related conditions.
- [pmacct](http://www.pmacct.net/) - Small set of multi-purpose passive network monitoring tools, including Netflow or IPFIX generation.
- [LibreNMS](https://www.librenms.org/) - Network monitoring system that supports automatic discovery, alerting, distributed polling and others.
- [Observium](http://observium.org/) - Low-maintenance auto-discovering network monitoring platform.

## Security Monitoring
- [Smart Investigator](http://www.smart-investigator.com/) - Event Identification and Management (Commercial).
- [cPacket](https://www.cpacket.com) - Performance monitoring solutions that deliver real-time analysis and coverage (Commercial).
- [Proxmox Mail Gateway](https://www.proxmox.com/en/proxmox-mail-gateway) - Open-source email security solution helping you to protect your mail server against all email threats the moment they emerge.
- [FastNetMon](https://fastnetmon.com/) - DDoS detection tool (Open Source or Commercial).
- [PyREBox](https://github.com/Cisco-Talos/pyrebox) - Python scriptable Reverse Engineering Sandbox, a Virtual Machine instrumentation and inspection framework based on QEMU
- [Canary](https://canary.tools/) - Honeypot solution (commercial)
- [CanaryTokens](https://canarytokens.org/generate) - Free honeytoken
- [Malcolm](https://github.com/idaholab/Malcolm) - Malcolm is a powerful, easily deployable network traffic analysis tool suite for full packet capture artifacts (PCAP files) and Zeek logs.

## Network Inventory
- [phpipam](https://phpipam.net/) - Open-source web IP address management application (IPAM).
- [nsot](https://github.com/dropbox/nsot) - Network Source of Truth is an open source IPAM and network inventory database.
- [netbox](https://github.com/digitalocean/netbox) - IP address management (IPAM) and data center infrastructure management (DCIM) tool.
- [nornir](https://github.com/nornir-automation/nornir) - Pluggable multi-threaded framework with inventory management to help operate collections of devices
- [ipfabric](https://ipfabric.io/product/network-mapping) - Network Topology Mapping & Visualization (Commercial)
- [drawthe.net](https://github.com/cidrblock/drawthe.net) - Draws network diagrams dynamically from a text file describing the placement, layout and icons.

# Related resources
## DevNet Tools
- [Celery](http://www.celeryproject.org/) - Asynchronous task queue/job queue based on distributed message passing.	It is focused on real-time operation, but supports scheduling as well.
- [Ajenti](http://ajenti.org/) - Manage a remote Linux box at any time using everyday tools like a web terminal, text editor, file manager and others.
- [ProxMox Virtualiation Platform](https://www.proxmox.com/en/proxmox-ve) - Open-source platform for enterprise virtualization that tightly integrates KVM hypervisor and LXC containers, software-defined storage and networking functionality on a single platform, and easily manages high availability clusters and disaster recovery tools with the built-in web management interface.
- [ops_tcpdump_handler](https://github.com/cerner/ops_tcpdump_handler) - Chef Cookbook to test network connectivity 

## DevNet Monitoring
- [netdata](https://github.com/firehol/netdata) - Distributed real-time performance and health monitoring.
- [Grafana](https://grafana.com/) - Open source software for time series analytics.
- [monit](https://mmonit.com/monit/) -Small Open Source utility for managing and monitoring Unix systems. Monit conducts automatic maintnance and repair and can execute meaningful causal actions in error situations.
- [Prometheus](https://prometheus.io/) - Open-source systems monitoring and alerting toolkit originally built at SoundCloud.
- [sensu](https://sensuapp.org/) - Monitor servers, services, application health, and business KPIs. Collect and analyze custom metrics. Get notified about failures before your users do. Give your business the competitive advantage it deserves. (Open Source or Commercial)
- ELK Stack
  - [Elasticsearch](https://github.com/elastic/elasticsearch) - Open Source, Distributed, RESTful Search Engine.
  - [LogStash](https://github.com/elastic/logstash) - Transport and process your logs, events, or other data.
  - [Kibana](https://github.com/elastic/kibana) - Analytics and search dashboard for Elasticsearch.
- [Graylog](https://www.graylog.org/) - Parse and enrich logs, wire data, and event data from any data source (Commercial, Free for less than 5GB/day).

### DevNet Knowledgebase
- [ITGlue](https://www.itglue.com/) - IT focused documentation solution (Commercial).

### DevNet Inventory
- [Snipe IT](https://snipeitapp.com/) - Open Source Asset Management tool.

### Knowledge Resources
- [Packet Pushers Podcast](http://packetpushers.net/) - Podcast about data networking by network architects. Deeply technical & unabashedly nerdy.
- [Risky Business Podcast](https://risky.biz/) - Features news and in-depth commentary from security industry luminaries.
- [Software Gone Wild Podcast](https://www.ipspace.net/Podcast/Software_Gone_Wild/) - Software Gone Wild is focusing on architectures, solutions and technologies that real networking engineers use in production networks
- [Cisco DevNet Basics](https://developer.cisco.com/video/net-prog-basics) - Learn network programmability basics


