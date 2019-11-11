# NFS RAID Template ReadMe

Build a CycleCloud custom template to deploy an NFS server backed by 4 Managed Disks in RAID0.

Import this template to CycleCloud Server with the following command (assumes Cycle CLI installed):

  cyclecloud import_template -f nfs-raid.txt --force
  
Once imported it will be available to deploy as a Filesystem within CycleCloud
