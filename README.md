# Windows Imaging & Deployment Lab

Home-lab environment for practicing enterprise Windows imaging and 
deployment workflows.

## Objectives

1. - [x] Build a Windows Server 2019 VM acting as domain controller, DHCP 
   server, and Windows Deployment Services (WDS) host on an isolated 
   internal network.

2. - [x] Configure a Windows 11 reference VM as a corporate workstation 
   baseline, generalize it with Sysprep, and capture it to a WIM file.

3. - [ ] Import the captured image into WDS and deploy it to a fresh target 
   VM via PXE network boot—no installation media required.

4. - [ ] Verify deployed images restore all applications, settings, and 
   machine identity regeneration on dissimilar "hardware."
