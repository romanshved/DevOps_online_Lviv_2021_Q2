TASK2.1

Part 1
1.What are the most popular hypervisors for infrastructure virtualization?
The most popular hypervisors for infrastructure virtualization are:
VMware vSphere Hypervisor
Microsoft Hyper-V
Citrix XenServer
Oracle VirtualBox
Red Hat Enterprise Virtualization Hypervisor (REVH)
KVM
Parallels
Qemu

2.Briefly describe the main differences of the most popular hypervisors
The main difference between the most popular hypervisors is that they belong to two different types of hypervisors (Type 1 and Type 2)
Type 1 has some features that distiunguish it from the second one. Type 1 hypervisors are installed directly on top of the physical server and respectively on the underlying hardware. That means that there is no operating system or any other software in between.
Unlike Type 1, Type 2 has one layer of software between hypervisor and hardware. For example, it could be an operating system (Windows, Linux, etc.)

Part 2
1.With your permission, I'll skip first few steps, because I've already had installed VirtualBox on my laptop.
So I created a new VM, called it as in the task instruction and learned the main possibilities f the VM control. Then I cloned an existing VM by creating VM2, created a group and made few snapshots after changing VM1 state. The results of the previous steps you can see in the picture <img src="screenshots/Screenshot_8">
Also I expoted and imported the Roman_Shved.ova file.
2.Here I explored VM configuration options, configured the USB to connect the USB ports of the host machine to the VM and configured a shared folder to exchange data between the virtual machine and the host. The results of the last two steps you can see here <img src="screenshots/Screenshot_12">
Then I checked connection between VM1, VM2, Host and NET/LAN using different network modes: <img src="screenshots/Screenshot_14">
3.Here I ran the cmd and tried some basic commands of VBoxManage:<img src="screenshots/Screenshot_15">

Part 3
I downloaded Vagrant, followed steps 1-7 and here are the results:
Initialized environment with "vagrant init hashicorp/precise64" and run "vagrant up" results: <img src="screenshots/Screenshot_19">
Connected with PuTTY and recorded date: <img src="screenshots/Screenshot_22">
Halt and destroy commands result: <img src="screenshots/Screenshot_13">
Creation of my own Vagrant box result: <img src="screenshots/Screenshot_16">


