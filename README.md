CE Janus - Transition to OpenStack Next
=======================================

This project intendes to support the automation of an updated baseline 
OpenStack environment, incorporating all of the Sungard specific
modifications and enhancements.

The general model:
 - Enable an install server as a VM, either on a new physical install server
   when the environment is new, or on a shared physical install server
 - Deploy an infrastructure composition service to enable the service
   infrastructure, at a minimum stand up the physical and virtual 
   compute resources. The goal is to manage all infrastructure.
 - Deploy the current "latest" OpenStack bits from RedHat (OSP 9 to start)
 - Add on and modify the baseline environment to meet Sungard 
   security and operabiltiy guidelines


