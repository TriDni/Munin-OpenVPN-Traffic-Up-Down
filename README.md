Munin-OpenVPN-Traffic-Up-Down
=============================

Two Munin's plugins which allows to graph bytes received/transmitted for each users.

Installation
===

Just link the plugins files in your /etc/munin/plugins/ and restart munin-node service.

ln -s /home/openvpn_userTrafficRx /etc/munin/plugins/.
sudo service munin-node restart

Line 16 of each plugins, there is the openvpn-status.log's path. Check if it's right or correct it with the real path.
