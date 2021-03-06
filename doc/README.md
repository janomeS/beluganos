# Document index of Beluganos

## Install

- [install-guide.md](install-guide.md)
	- Install Beluganos and related OSS automatically

## Use case

After installing ([install-guide.md](install-guide.md)), you can check our use case to try Beluganos.

- [case1.md](example/case1/case1.md)
	- **Recommendation for beginner**
	- IGP router with MPLS
	- Create automatically not only Beluganos but also environment router
- [case2.md](example/case2/case2.md)
	- MPLS-VPN PE router with 2 VRF
	- Real white-box swithes and environment routers are required to try

## Setup & configure

After installing ([install-guide.md](install-guide.md)), you can configure Beluganos as you like.

- [setup-guide.md](setup-guide.md)
	- Hardware settings of Beluganos
- [configure-ansible.md](configure-ansible.md)
	- Configuration guide of IP/MPLS router by ansible.
- [configure-ansible-l3vpn.md](configure-ansible-l3vpn.md)
	- Configuration guide of MPLS-VPN PE router by ansible.
- [configure-netconf.md](configure-netconf.md)
	- Configuration guide of router by NETCONF.
- [operation-guide.md](operation-guide.md)
	- How to start/stop Beluganos
	- How to login routing engine's console

## NETCONF configure

- [netconf/etc/openconfig](https://github.com/beluganos/netconf/tree/master/etc/openconfig)
	- Yang files of Beluganos
- [netconf/doc/examples](https://github.com/beluganos/netconf/tree/master/doc/examples)
	- The examples of XML for NETCONF `<edit-config>`
- [netconf/doc/setup-guide](https://github.com/beluganos/netconf/blob/master/doc/setup-guide.md)
	- Initial settings about network-instance modules

## General

- [README.md](../README.md)
- [CONTRIBUTING.md](../CONTRIBUTING.md)
- [architecture.md](architecture.md)
	- Abstraction of Beluganos's architecture
- [function.md](function.md)
	- Function matrix of Beluganos