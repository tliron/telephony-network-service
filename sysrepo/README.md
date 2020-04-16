Parallel builds (in C++) require a lot of RAM


# Netopeer

https://hub.docker.com/r/sysrepo/sysrepo-netopeer2

## NETCONF libraries

https://github.com/CESNET/Netopeer2GUI
https://github.com/CESNET/Netopeer2
https://github.com/CESNET/libnetconf2
https://github.com/CESNET/libyang

## Datastore for YANG

https://github.com/sysrepo/sysrepo
https://www.sysrepo.org/
https://netopeer.liberouter.org/doc/sysrepo/master/

# Go

https://github.com/andaru/netconf
https://github.com/Juniper/go-netconf

## netconf-console

netopeer2-cli
connect
vagrant
get --filter-xpath=/ietf-interfaces:interfaces-state/interface[name='eth100']

https://github.com/CESNET/Netopeer2/issues/437
https://www.vutbr.cz/www_base/zav_prace_soubor_verejne.php?file_id=132147

# https://pypi.org/project/netconf-console/
sudo dnf install -y patch ncurses-devel
pip install netconf-console --user
netconf-console --port 830 --user vagrant --password vagrant
get-schema ietf-interfaces
get -x /ietf-interfaces:interfaces/interface[name='eth100']/description
urn:ietf:params:xml:ns:yang:ietf-interfaces

# librouter-gui
sudo dnf install libffi-devel npm
package.json
ng serve --proxy-config proxy.json --host 0.0.0.0

# pyroute2
https://pyroute2.org/
