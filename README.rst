The networking-cisco project's goal is to provide support for Cisco networking
hardware and software in OpenStack deployments. This includes ML2 drivers and
agents for neutron, as well as other pieces of software which interact with
neutron to best utilise your Cisco products with OpenStack.

* Free software: Apache license
* Documentation: http://networking-cisco.readthedocs.io/en/latest
* Source: http://git.openstack.org/cgit/openstack/networking-cisco
* Bugs: http://bugs.launchpad.net/networking-cisco

Drivers for Cisco Products
==========================

* Nexus 9000 Series Switches

  * ML2 Mechanism driver - cisco_nexus
  * ML2 VXLAN Type driver - nexus_vxlan

* UCS Manager

  * ML2 Mechanism driver - cisco_ucsm

* ASR 1000 Series

  * Neutron Service Plugins - cisco_l3_routing

* Nexus 1000v

  * *Deprecated.* To be removed in release 6.0.0
  * ML2 Mechanism driver - cisco_n1kv
  * Neutron Service plugins - cisco_n1kv_profile, cisco_n1kv_net_profile
  * ML2 Extension driver - cisco_n1kv_ext

* Network Convergence System (NCS)

  * *Deprecated.* To be removed in release 6.0.0
  * ML2 Mechanism driver - cisco_ncs

* Service Advertisement Framework (SAF)

  * *Deprecated.* To be removed in release 6.0.0
  * Firewall drivers - native, phy_asa
  * Applications - fabric-enabler-server, fabric-enabler-agent, fabric-enabler-cli

* Prime Network Registrar (CPNR)

  * *Deprecated.* To be removed in release 6.0.0
  * Applications - cpnr-rootwrap, cpnr-dns-relay-agent, cpnr-dns-relay, cpnr-dhcp-relay-agent, cpnr-dhcp-relay

* Application Policy Infrastructure Controller (APIC)

  * *No longer supported.* Removed in release 5.0.0
  * Code removed by commit 10b124d39fde4085a695d5c6652c8fb6e0620ece
  * Driver now hosted in repo https://github.com/noironetworks/apic-ml2-driver

Releases and Version Support
============================

From Mitaka forward, networking-cisco is branchless and releases will be made
from master. We have a goal to maintain compatibility with multiple versions of
OpenStack for as long as possible starting from version 4.0.0 which is
compatible with both Mitaka and Newton OpenStack releases.

* 5.X.X Mitaka, Newton, Ocata
* 4.X.X Mitaka, Newton, Ocata
* 3.X.X Mitaka
* 2.X.X Liberty
