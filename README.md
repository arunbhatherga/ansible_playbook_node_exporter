# ansible_playbook_node_exporter
This playbook installs Node Exporter

Give execution permission to connectivity_test.sh and install_node_exporter.sh

Run connectivity_test.sh to check connectivity between control node and host 

Run install_node_exporter.sh to install node exporter in the host 

Node exporter will be exposed in 9100 port by default 

run curl command to verify installation curl http://<hostname>:9100/metrics
