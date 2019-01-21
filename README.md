# VPN-Roulette
Script for randomizing a VPN conf file and starting OpenVPN with that conf file.

Written to be executed in tcsh which is usually the default shell in FreeBSD. 

Some preperation is needed before running the script

* Have a dir with the name confs in `/usr/local/etc/openvpn/`
* Put all of your different VPN confs in the `confs`dir

Then run the script! Easy as that! You could also easily add it as a cronjob and let it execute every X amount of minutes/hours etc.

Perfect if you feel extra paranoid, set it up for your jail with firewall rules that tells it strictly to communicate when a VPN connection is up and you are all set!

# Contributers
[@troligtvis](https://github.com/troligtvis)
