DOCUMENTATION FOR MAC ADDRESS CHANGER.

*What is MAC address?
.It stands for Media Access Control address.
.It is assigned by IEEE and the manufacturer.
.It is unique.
.It is used to identify the identity locally i.e. is Local Area Network(LAN).
.It is a 12 digit hexadecimal number.
.It is a layer 2 of OSI(Open System Interconnection) model i.e. data link layer.
.It is assigned on a NIC(Network Interface Card).
.It is a physical address.

*Types of MAC addresses:
1.Unicast MAC: It is attached to a specific NIC on the local network. This address is used only when a frame is sent from a single transmitting device to a single destination device.
2.Multicast MAC: A source device can transmit data frame to multiple devices by using a Multicast. IP address is assigned to devices belonging to the multicast group.
3.Broadcast MAC: This address every device on a given network. Main purpose of Broadcast domain is to  enable a source device to send data to every device on the network using the Broadcast address as the destination MAC address.

*Project Description:
1. O.S used is Kali Linux
2. Language used is python.
3. IDE used is PyCharm
4. Modules used are:
   . subprocess
   . optparse
   . re 


*Why Kali Linux:
. Released in 2013.
. Debian based Linux distribution operating system mainly used by penetration testers and digital forensic experts.
. Cyber security tools is maintained and funded by offensive Security limited.
. Availability of more than 600 tools.
. Completely free.
. Multi Language support.
. Entirely customization.
. ARMEL and ARMHF support: .Allows hacking without any hassles.
                           .These are Processor Architecture.
                           .ARM stands for Acorn Risc Machine.(Reduced Instruction Set Computer)
                           .Most mobile devices use ARM processor cores.
. We have 3 ARM ports:
1.ARMel port: supports older 32 bit ARM processors without hardware FPU(Floating Point Unit).
2.ARMhf port: supports at least ab ARM 32 bit processor with ARMv7 architecture.

. Open source model.

*Why Python is used in Cyber security.
. Simplicity
. Flexibility
. Extensive library support
. Ability to automate repetitive task


*subprocess module:
. It is used to execute external programs using python scripts or system commands.
. Capture the output generated by the command using stdout or sdterr.

*What is subprocess Popen ? 
. It is a low level interface for running subprocesses.
. subprocess.run is a high level wrapper around a Popen intended for ease of use.
. It allow us to start a new process and interact with its standard input, output, and error streams.

*optparse module:
. A module that makes easy to write command line tools.
. It make it easy to handle the command line argument.
. It allows dynamic data input to change the output.

*re module:
. This module provides regex matching operations similar to those found in perl.
. It is basically used to like select a desired content from any form of strings.
. In our python script we have used this module to filter the mac address.
