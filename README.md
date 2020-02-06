# on-premise-coreos-kubernetes analytic with webspoon, clickhouse and apache superset
vmware vsphere implementation coreos kubernetes, 

steps to install:
1. prepare coreos ignition config file
2. coreos install.sh config file
3. vmware workstation
4. ovftool to convert sha256

explanation:
1. prepare coreos ignition config file: this file is my creation from 3.5 years research, it's not perfect but it's good enough for production
2. coreos install.sh config file: https://raw.githubusercontent.com/coreos/init/master/bin/coreos-install
3. vmware workstation: need to modify gateway and dns
4. ovftool to convert sha256: free download

we used on-premise coreos kubernetes for analytic webspoon, clickhouse and apache superset
