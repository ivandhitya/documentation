# How to add additional HDD on linux Ubuntu

1. Plug your new hdd on your PC
2. Open "Disks" App
3. Ensure your hdd listed
4. Create auto mount when your PC booting
    + ```
      sudo vim /etc/fstab
      ```
    + Add your hdd configuration in that file
      ```
      UUID=B581-E667  /media/ivandhitya/DATAA1T1      vfat    umask=000       0  2
      ```
      You can see the value above on Disks App
    + ensure fstab processed properly
      unmount your disk through Disks App
      ```
      sudo mount -a
      ```
  
      

