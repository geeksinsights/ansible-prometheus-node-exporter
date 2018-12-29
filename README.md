# ansible-prometheus-node-exporter

This playbook will install prometheus node exporter in the given hosts or group of hosts mentioned in the hosts file

**Notes for Host File grouping**

   - **Group the hosts as like below**
   
     [dev]
     devserver1.localdomain
     
     devserver2.localdomain
     
     [prod]
     devserver1.localdomain
     
     devserver2.localdomain
     
     
**Install the playbook**

  - Download or clone the playbook
  
**Run the playbook**

  - **Variables**
     - ansible_user: root or any other user you want to
     - node_exporter_version: 0.15.2 (used in the yml file)
     
  - Put the hosts group you want to
     - hosts: prd|dev|
