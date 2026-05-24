# Networking for Enterprise Infrastructure

This section focuses on real-world networking concepts required for enterprise DevSecOps, platform engineering, cloud infrastructure and Kubernetes operations.

Most infrastructure issues eventually become networking issues.

The goal is not only learning protocols, but understanding how production systems communicate, fail and recover.

---

# Topics Covered

## Core Networking Fundamentals
- OSI model
- TCP/IP
- ports and protocols
- CIDR and subnetting
- routing basics
- NAT
- ARP
- MTU

---

## Enterprise Networking
- VPC architecture
- private/public subnets
- VPN
- Direct Connect
- hybrid networking
- Transit Gateway
- network segmentation
- bastion architecture

---

## DNS
- DNS resolution flow
- authoritative vs recursive DNS
- Route53
- CoreDNS
- split-horizon DNS
- DNS troubleshooting

---

## TLS / SSL
- TLS handshake
- certificates
- certificate chains
- mTLS
- reverse proxy TLS termination
- certificate rotation
- HTTPS debugging

---

## Reverse Proxy & Load Balancing
- NGINX
- HAProxy
- Envoy
- L4 vs L7 load balancing
- ingress controllers
- sticky sessions
- traffic routing

---

## Kubernetes Networking
- CNI
- pod networking
- service networking
- ingress
- network policies
- service mesh basics
- kube-proxy

---

## Packet Analysis & Troubleshooting
- tcpdump
- Wireshark
- packet capture analysis
- DNS debugging
- latency analysis
- SYN flood basics
- retransmissions
- connection tracing

---

## Security Concepts
- firewalls
- WAF
- DDoS basics
- Zero Trust networking
- segmentation
- network policies
- VPN security

---

# Enterprise Relevance

Networking knowledge is critical for:
- Kubernetes troubleshooting
- cloud architecture
- GitOps delivery systems
- CI/CD connectivity
- ingress troubleshooting
- service mesh operations
- observability systems
- hybrid enterprise infrastructure

Many production outages are caused by:
- DNS failures
- expired certificates
- ingress misconfiguration
- firewall rules
- subnet/routing issues
- load balancer problems

---

# Recommended Learning Resources

## YouTube Channels

### Hussein Nasser
https://www.youtube.com/@hnasr

### David Bombal
https://www.youtube.com/@davidbombal

### ByteByteGo
https://www.youtube.com/@ByteByteGo

### NetworkChuck
https://www.youtube.com/@NetworkChuck

---

# Recommended GitHub Repositories

## Anton Putra Tutorials
https://github.com/antonputra/tutorials

---

# Recommended Books

- TCP/IP Illustrated
- Designing Data-Intensive Applications
- Computer Networking: A Top-Down Approach

---

# Practical Labs

## Beginner
- subnetting practice
- configure DNS locally
- basic packet capture analysis
- NGINX reverse proxy setup

## Intermediate
- ingress troubleshooting
- TLS debugging
- HAProxy load balancing
- Kubernetes networking debugging

## Advanced
- analyze packet loss
- debug production latency
- mTLS troubleshooting
- service mesh traffic analysis
- hybrid cloud networking design
- enterprise VPC architecture