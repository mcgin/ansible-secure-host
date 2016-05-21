Script to configure basic security on a new ubuntu box
 - Changes ssh port to 21222
 - Sets up a firewall with no incoming connections allowed
 - Disables password authentication/root login over ssh
 - Installs fail2ban
 - Sets up logwatch to email daily summary
 - The logwatch destination email is best specified in the inventory file per host
