# GSS Static Lab Base Configurations

The goal of this repo is to provide users of the static lab with base configs of an EVPN enviroment in the static lab in order to speed up recreates. This is a fork of the cldemo-evpn-symmetric demo that we are all familiar with: https://github.com/CumulusNetworks/cldemo-evpn-symmetric . I have modified the configs and Ansible playbook to what is physically cabled in the static GSS lab.

TO DO:
1) If we are doing checkouts by VTEP pair, I will need to add specific instructions to comment out the VTEPs that you are not using in the Ansible host file. Possibly, make the default that all leaf switches in the host file are commented out and that people will need to comment out the leaf switches that they are using.


The Network Topology is depicted below.


## Topology ##
![GSS_Static_Lab](https://github.com/SniffedPacket/GSS-Static-EVPN-POD/blob/master/RDU_Remote_Work_Lab_with_port-id_v2.png)





    



