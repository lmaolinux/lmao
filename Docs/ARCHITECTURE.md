<p align="center">
  <img src="lmao.svg" width="200" alt="lmao" />
</p>

# ROADMAP

We track security posture, hardening changes, and kernel updates across Secureblue and upstream Fedora. 
If a fix is critical, we may apply it directly while working with upstreams.


>[!important]
> * To minimize the damage, operating systems has to be built with permanent enforcement of SELinux as setting it to permissive would be what a malware wants to do most of the times.
> * Privacy is a subset of security. compromised privacy ultimately leads to exploitation.

## CPM -  Containerized Package Manager
CPM, Containerized Package Manager routes Danified YUM (DNF) and Advanced Package Tool (APT) through seperate containers. It gives the security of an atomic operating system, tidiness of a containerized workflow, and a way to remove all packages in a single command along with vast range of software compatibility.
