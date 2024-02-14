<h1 align="center">Cybersecurity Home-Lab.</h1>

As part of my learning experience at TKH, I designed and implemented a Cybersecurity Home Lab to demonstrate my knowledge and technical skills. I used Linux Terminal Operations, Networking Fundamentals, and Cybersecurity Concepts and Tools to set up a secure home network. 

In this Project I had learned how to create a cybersecurity home-lab from scratch. I used Gliffy to create a network diagram that showed the topology and configuration of my security home lab. Also, I use VirtualBox to run Ubuntu desktop as your host machine and install pfSense as a firewall to protect your network simulations.I used configure Snort as an intrusion detection system and use Splunk as a security information and event management (SIEM) tool, use Metasploitable2 as target/victim Virtual machine. Finally,I had set up Kali Linux as an attacker machine to perform various penetration testing scenarios.


###
<h3 align="center">Documentation of the Home-lab

 
 ##
 My paper provides a comprehensive overview of the tools and services that I use in my security home lab. I describe the functionality, purpose, and relevance of each tool and service in the context of the security industry.I also demonstrate how I can apply them to real world scenarios and challenges that security professionals face. My paper intends to showcase my skills and knowledge in security testing, analysis, and research.

#### Here's a fragment of my detail- paper:
##

![Screenshot 2024-02-14 005729](https://github.com/luzritacco/Cybersecurity-Home-Lab/assets/151267325/011388ef-0c84-47f1-a19e-cddeee69a776)


##
<h3 align="center"> Here's the network diagram -layout- topology of my cybersecurity Home-lab setup:

 
 ##

![Screenshot 2024-01-03 191635](https://github.com/luzritacco/Cybersecurity-Home-Lab/assets/151267325/0022d569-361b-457e-8f87-cc7ddd4f88e6)

##
<h3 align="center"> Setting and preparing the Virtual Home-Lab


 ##
+ The first component of our virtual home lab is the Host PC. It must meet the minimum hardware/software requirements to support the tasks and configuration we will perform.
+ I use VirtualBox Workstation, which allows us to run multiple virtual machines simultaneously on one system.
+ I set up a secure network environment using Ubuntu, pfSense, and Snort. First, I installed Ubuntu desktop on a host machine and configured its settings according to lab needs.
+ I installed pfSense firewall on another machine and connected it to the host machine. pfSense firewall is a powerful tool that allows us to create network  segments and apply security policies to them.
+ I also installed Snort on the pfSense machine, which is a software that monitors network traffic and detects intrusions, threats, and anomalies. By using these tools, we were able to create a comprehensive solution for network security and management.
+ I installed and configure Splunk on an ubuntu terminal, as well Splunk forwarder packets server as the home lab SIEM tool. That grabs data from different areas  of your lab such as firewalls or servers and sends it to Splunk. This lets us check the network’s safety by reviewing the collected data.
+ I installed and configure Metasploitable 2 in the VirtualBox to create   a virtual machine intentionally vulnerable for testing security tools and demonstrating common vulnerabilities.
+ I installed and  prepared Kali Linux, to be the attacker machine since it a potent tool designed for conducting penetration testing and security audits.

#### Virtual Box
![virtual](https://github.com/luzritacco/Cybersecurity-Home-Lab/assets/151267325/6aff4d11-5782-4649-a436-336cadb0c21a)

![vitual lab](https://github.com/luzritacco/Cybersecurity-Home-Lab/assets/151267325/4fb33b0d-400c-4d5a-8995-cc2ed65ec714)



#### Kali Linux
![kali-metas 2](https://github.com/luzritacco/Cybersecurity-Home-Lab/assets/151267325/dad5014c-3f4c-40b1-99ad-b3467a32c111)

![kali-metasploitable](https://github.com/luzritacco/Cybersecurity-Home-Lab/assets/151267325/6c75bcfb-52a3-4204-8712-83a9d9132813)

#### Metasploitable 2
![metasploitable-vitual](https://github.com/luzritacco/Cybersecurity-Home-Lab/assets/151267325/60bb7994-84dd-49a1-be0d-54121d8eb728)


#### Splunk

![splunk fowarder installation](https://github.com/luzritacco/Cybersecurity-Home-Lab/assets/151267325/95db411c-f7cc-4338-96d2-bb3ebc4e5ea0)

#### pFsense

![pfsense-ubutu](https://github.com/luzritacco/Cybersecurity-Home-Lab/assets/151267325/67c6a95c-97a7-45d3-b564-5739e2268221)

#### The Virtual Home-Lab

![My homelab](https://github.com/luzritacco/Cybersecurity-Home-Lab/assets/151267325/bf8237b2-fe49-4324-8b1e-58d19472b189)


##

<h3 align="center"> Here some issues I went into during the installation and setting up process:

##
**☑ Metasplitable2 installation** I had some issues installing Metasploitable2 in the VirtualBox such as:
+ The virtual machine gets stuck at the startup screen.
+ The installation process fails due to an error.
+ The virtual machine does not boot after installation.

