# openvpn-client-netns
Start OpenVPN connection from within a network namespace.

These scripts are taken from https://austinjadams.com/blog/running-select-applications-through-openvpn/.
The difference is a copy of the OpenVPN systemd script and modified to fire off the namespace service.
This lets you use OpenVPN as you normally would, while being able to start new instances in a namespace.
