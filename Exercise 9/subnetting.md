<H1> SUBNETTING </H1>

<B> 193.16.20.35/29 <B>
 <br>
 <ul> <B> What is the Network IP, number of hosts, range of IP addresses and broadcast IP from this subnet? <B> </ul>
  <br>
193.16.20.35 = 11000001.10101000.00010100.00100011
  <br>
 29 = 1111111.11111111.11111111.11111000
  <br>
      255.255.255.248
  <br>
  To get the Network ID we will compare the fourth octet between the given ip converted to binary and subnet mask 
  <br>
  which gave us = 00100000
  <br>
  If we convert this binary format we will get 32 
  <br>
  which gives us the fourth octet for our network ip below
  <br>
   <br>
<B> 1.Network IP=193.16.20.32 <B>
 <br>
 we have 3 host bits remaining i.e we are counting our binary subnet mask from the right. Let’s use our formula for calculating usable IP addresses:
 <br>
Usable IP addresses =  $2^h$ – 2
 <br>
 $2^3$ – 2 = 8 – 2 = 6 usable IPs
 <br>
This means we have a total of 8 IP addresses, with 6 usable Ip addresses
  <br>
  <br>
<B> 2. Number of hosts=6 <B>
  <br>
 Note: In IPv4, there are two IPs that cannot be assigned to any devices. These are the Network ID and the Broadcast IP address. Therefore, you need to subtract two addresses from the total IP formula.
 <br>
  <br>
<B> 3. Range of IP addresses=193.16.20.33 - 193.16.20.38 <B>
  <br>
  <br>
<B> 4. Broadcast IP=193.16.20.39 <B>
