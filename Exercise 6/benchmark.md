<h1> Review the CIS benchmark for ubuntu and try to implement 10 of the recommendations we made within the benchmark </h1>

<b> 1.  Ensure mounting of cramfs filesystems is disabled (Automated) </b>
<br>
<b>  Description: The cramfs filesystem type is a compressed read-only Linux filesystem embedded in small
footprint systems. A cramfs image can be used without having to first decompress the
image.</b>

![cramfs](https://user-images.githubusercontent.com/32138488/194711753-20a9e62b-9e04-4b83-ab2e-0faa9db0ca6d.PNG)

<b> 2. Ensure mounting of freevxfs filesystems is disabled (Automated) </b>
<br>
<b>  Description: The freevxfs filesystem type is a free version of the Veritas type filesystem. This is the
primary filesystem type for HP-UX operating systems </b>

![freevxfs](https://user-images.githubusercontent.com/32138488/194712621-6559fc7d-e5e5-4d2c-a08a-c612ff2ad73c.PNG)

<b> 3. Ensure mounting of jffs2 filesystems is disabled (Automated) </b>
<br>
<b> Description: The jffs2 (journaling flash filesystem 2) filesystem type is a log-structured filesystem used
in flash memory devices. </b>

![jffs2](https://user-images.githubusercontent.com/32138488/194713018-277cbd17-f8a0-423d-8da6-6a327957dd2b.PNG)

<b> 4.  Ensure mounting of hfs filesystems is disabled (Automated)   </b>
<br>
<b>  Description: The hfsplus filesystem type is a hierarchical filesystem designed to replace hfs that allows
you to mount Mac OS filesystems </b>

![hfs](https://user-images.githubusercontent.com/32138488/194714584-89938a41-6920-487a-8790-6dd329513506.PNG)

<b> 5.  Ensure mounting of udf filesystems is disabled (Automated)    </b>
<br>
<b>  Description: The udf filesystem type is the universal disk format used to implement ISO/IEC 13346 and
ECMA-167 specifications. This is an open vendor filesystem type for data storage on a
broad range of media. This filesystem type is necessary to support writing DVDs and newer
optical disc formats </b>

![udf](https://user-images.githubusercontent.com/32138488/194714742-cc328265-26ba-4600-bc56-6043a0f1635d.PNG)

<b> 6. Ensure AppArmor is installed (Automated)    </b>
<br>
<b>  Description: AppArmor provides Mandatory Access Controls </b>

![apparmor](https://user-images.githubusercontent.com/32138488/194715456-e0c26d3c-f9b9-483b-89c9-862e283bd8df.PNG)

<b> 7. Ensure updates, patches, and additional security software are
installed (Manual)     </b>
<br>
<b>  Description: Periodically patches are released for included software either due to security flaws or to
include additional functionality </b>

![apt](https://user-images.githubusercontent.com/32138488/194717162-83b7fa72-5873-4e57-a7e6-b48123d2d156.PNG)

<b> 8. Ensure NIS Client is not installed (Automated)  </b>
<br>
<b>  Description:The Network Information Service (NIS), formerly known as Yellow Pages, is a client-server
directory service protocol used to distribute system configuration files. The NIS client was
used to bind a machine to an NIS server and receive the distributed configuration files </b>

![NIS](https://user-images.githubusercontent.com/32138488/194717833-865e8c26-2dcd-4ba2-9cd3-c743db4cffa1.PNG)

<b> 9.  Ensure ufw is installed (Automated)  </b>
<br>
<b>  Description:The Uncomplicated Firewall (ufw) is a frontend for iptables and is particularly well-suited
for host-based firewalls. ufw provides a framework for managing netfilter, as well as a
command-line interface for manipulating the firewall </b>

![ufw](https://user-images.githubusercontent.com/32138488/194718270-1a89cfda-2628-454a-b5d5-e8363cddd1b1.PNG)

<b> 10.Ensure iptables-persistent is not installed with ufw (Automated)   </b>
<br>
<b>  Description:The iptables-persistent is a boot-time loader for netfilter rules, iptables plugin
 </b>

![iptables](https://user-images.githubusercontent.com/32138488/194718470-6f26160b-55b1-4fb4-8d4d-a27b89d6b8f8.PNG)











