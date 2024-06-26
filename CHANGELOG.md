# **CHANGELOG**

## **1.0.5** 
### **CHANGES**
- Updated login node and nfs storage node to use RHEL 8.8 stock image instead of RHEL 8.6 stock image.
- Bug related to Slurm cluster creation from hpc_workspace_config.json through IBM Cloud Schematics has been resolved.

## **1.0.4** 
### **CHANGES**
- OS upgrated to Ubuntu 22.04 for Slurm Management node and Worker node.
- Support for Baremetal worker.
- Support for Scale filesystem.
- Support for OS tunables.
- Support for HDF5.
- Support for Openmpi.

## **1.0.3** 
### **CHANGES**
- Updated login node and nfs storage node to use RHEL 8.6 stock image instead of RHEL 8.2 stock image.

## **1.0.2**
### **CHANGES**
- Renamed master to management as part of "Words Matter Initiative"

### **BUG FIXES**
- Fixed bug related to metadata files not getting copied from management host to worker nodes

## **1.0.1**
### **CHANGES**
- Changes to post provisioning scripts to mitigate Polkit Local Privilege Escalation Vulnerability (CVE-2021-4034).

## **1.0.0**
- Initial Release
