This code snippet will get Debian installed on an Arm Mac using Qemu.  I used it to do a network install of AMD64 Debian on a MacBook Pro with an M3 ARM processor.  You must first install MacPorts and Qemu for and make your drive.  sh-3.2# qemu-img create -f qcow2 myVirtualDisk.qcow2 60G will make a drive and this code will work to get you a working Debian system on MacOS.  