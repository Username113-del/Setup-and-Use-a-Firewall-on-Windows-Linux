# Setup-and-Use-a-Firewall-on-Windows-Linux
Task  on Win7 &amp; Kali Linux honed firewall skills using Windows Firewall &amp; UFW. Blocked Telnet (port 23), allowed SSH (port 22), tested rules, &amp; documented. Learned traffic filtering, stateful vs. stateless firewalls, &amp; network security. Skills gained enhance ability to secure networks effectively. 
# Kali Linux Firewall Task Documentation
1. Checked UFW status: `sudo ufw status verbose`. Output: `firewall_rules_before.txt`, Screenshot: `firewall_rules_before.png`.
2. Blocked port 23: `sudo ufw deny 23`, enabled UFW: `sudo ufw enable`. Output: `block_port_23.txt`, Screenshot: `block_port_23.png`.
3. Tested rule: `telnet localhost 23` (failed as expected). Output: `telnet_test_fail.txt`, Screenshot: `telnet_test_fail.png`.
4. Allowed SSH: `sudo ufw allow 22`. Tested with `ssh <username>@<Kali_IP>`. Output: `allow_ssh_22.txt`, Screenshot: `allow_ssh_22.png`.
5. Removed block rule: `sudo ufw delete deny 23`. Output: `rules_after_removal.txt`, Screenshot: `rules_after_removal.png`.
