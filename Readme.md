Windows Update Management Solution (WUMS)
=========================================

This set of scripts and tools is meant to help you manage WSUS Updates in larger environments with multiple Active Directory Forests.

It consists of multiple parts:

Client
------
Scripts which run on the WSUS clients and trigger WSUS detect, download and install.

Server
------
The Webserver part and brains of the thing. All configuration and scripts are maintained on this server and the clients request all information to run here.

WSUS
----
A set of optional scripts to automate all approvals. It allows you more granular control than using the WSUS Console, which is 'suboptimal'.