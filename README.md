# Can-anyone-tell-me-what-this-means-please-
unallocated.barefruit.co.uk: Name or service not known


#I get this error unallocated.barefruit.co.uk: Name or service not known#
#when i run this command hdfs namenode -format

#Fixed it by making network settings
#############################
Windows 10
Open the Control Panel.
Click Network and Internet.
Click Network and Sharing Center.
On the left pane, click Change adapter settings.
Right-click the network interface connected to the internet, then click Properties.
Choose Internet Protocol Version 4 (TCP/IPv4).
Click Properties.
Click Use the following DNS server addresses.
Click Advanced.
Enter 208.67.222.222 and 208.67.220.220 in the DNS server fields.
Click OK, then click Close.
