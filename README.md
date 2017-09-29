# Linux_Patching_w_Ansible
Project tracks the progress of an ansible playbook used to patch RHEL based Linux system patching
This playbook patches then reboots as many systems are listed in the hosts section.  The script applies all updates including kernel updates.  If kernel updates are not desired, then a modification can be made to the yum.conf file of the patched system.
       yum update --exclude=kernel*
More on this can be found at this link - https://access.redhat.com/solutions/10185
  
  
