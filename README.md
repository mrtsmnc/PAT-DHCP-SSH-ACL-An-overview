# PAT-DHCP-SSH-ACL-An-overview
""PAT :(Port Address Translation) protocol allows multiple computers on a private IP-addressed network to access the Internet using the same public IP address. This protocol translates the private IP addresses of devices on the network into the public IP address, keeping the private IP addresses hidden in the outgoing Internet traffic."

"DHCP :(Dynamic Host Configuration Protocol) is a protocol that automatically assigns network configuration information such as IP address, subnet mask, default gateway, and DNS server to devices on the network.
The DHCP server assigns a unique IP address to each device on the network, eliminating the problem of IP address conflicts. DHCP automates the network configuration process, saving time for network administrators and allowing for quick management of changes made to the network.

"SSH (Secure Shell) is a protocol that enables secure communication between devices on a network. By encrypting data transmission between devices on the network, SSH prevents malicious individuals from intercepting or modifying data traffic.
SSH is also commonly used for remote management operations. By connecting to an SSH client, you can remotely manage a server on the network. The SSH client can also perform file transfers.

An ACL :(Access Control List) is a mechanism used to control incoming or outgoing traffic on network devices (such as routers, switches, firewalls, etc.). ACLs are used to filter traffic entering or exiting a specific network based on specific criteria, in order to control which devices in a network can access which resources.
ACLs typically control traffic based on certain criteria such as IP address, protocol type, source port, and destination port. For example, only allowing devices in a specific network to access the internet through a specific port while blocking all other ports.
Properly configuring ACLs is important for controlling traffic between devices on a network and increasing security.
