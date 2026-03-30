# Setting Up A Cybersecurity Lab

_This repository is about installing and setting up a Kali Linux environment on a personal computer. The virtual machine will be used as a Cybersecurity Lab particularly dedicated for AWS PUP Cloud Department of Networking and Cybersecurity as an assignment._

* Ensure that the Oracle VM VirtualBox is already installed (not to be confused with Kali Linux VirtualBox installer). In this, the Oracle VirtualBox serves as a platform (Hypervisor) that allows you to run multiple Virtual Machines. If it's not yet already already done, just go to oracle vm virtualbox website or click this link to get redirected into this site [Oracle VM VirtualBox Installer](https://www.oracle.com/asean/virtualization/technologies/vm/downloads/virtualbox-downloads.html). Download an installer here based on your operating system, in my case, I downloaded the one that is compatible with Windows.
* Click the .exe or the executable file of the Oracle VirtualBox to set it up. Click the default settings in the Setup Wizard then it will start installing the software. When it's already done, proceed into downloading a Kali Linux Machine in the computer.
*To install a virtual machine on your computer, search the Kali Linux website, click the Virtual Machines button and select the appropriate Pre-built Virtual Machine to download. Choose between VMware and VirtualBox images then install it. Click this to get redirected in the site [Kali Linux Pre-built VM](https://www.kali.org/get-kali/#kali-virtual-machines).
* Unzip the Kali Linux Virtual Machine file and import it inside the Oracle Virtualbox. To import the file, click the add or export button then click the blue box file or the one that ends with .vbox.
* Click start in your Oracle VirtualBox in Machines section then wait for it to boot up. The username and password for this are the same, use "kali" for it.
* Once installed, go to the terminal emulator and run the following command prompt to update the tools:
  'sudo apt update && sudo apt upgrade'
* Lastly, run the following command to test out.
  'cat /etc/os-release && ip addr'


> Note: These files are in a compressed file and has a huge file size when unzipped so make sure to have a sufficient storage. 



