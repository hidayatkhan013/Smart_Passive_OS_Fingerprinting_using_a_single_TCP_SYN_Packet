# Smart_Passive_OS_Fingerprinting_using_a_single_TCP_SYN_Packet
Smart_Passive_OS_Fingerprinting_using_a_single_TCP_SYN_Packet

Abstract—The tools available for active OS fingerprinting (such
as nmap) send a large number of probes to the target system
to identify its OS. If there are no open ports in the target
system, it will be nearly impossible to detect its OS by using
these techniques. We can overcome this problem by using passive
techniques. The tools available for passive OS fingerprinting
such as p0f3, Ettercap, Saturi but these tools only analyze the
HTTP traffic coming to the host system and it identifies the
sender’s OS by using TCP SYN-ACK packet. They have a very
limited database of signatures and some of these signatures are
duplicates of each other. The solution we are proposing is to use
a single TCP SYN packet to identify the OS of the target system
without disturbing the network traffic. We have generated the OS
fingerprints of 11 eleven different signatures including Windows
7, Windows 10, Android 9, 10, 11, LINUX. After testing it, we
have come to the conclusion that it is working properly.
Index Terms—OS Fingerprinting, TCP/IP, ARP, Linux

VI. CONCLUSION
This paper develops and evaluates a methodology that uses
several features in network traffic for identifying the OS on
the sending device. This OS fingerprinting can be used for
detecting tethering and more generally deployment of network
address translation. The proposed methodology includes a
probabilistic approach to combine multiple features to enhance
detection accuracy. We evaluate the effectiveness of individual
features and find TTL, TCP timestamp, and TCP window
size scale factors are more accurate, while clock frequency
and boot time are less accurate. Furthermore, we proposed a
solution for generating dataset for signature effectively.


VII. FUTURE WORK
Our system cannot detect the OS of those systems whose
signature is not stored in the database. We can use AI
techniques for generalizing our existing signature so that we
can use it for those devices. Also, fuzzy searching can be
enabled. This includes, for example, capabilities for searching
similar requests on the base of a fingerprint’s substring, using
a wildcard search, or searching depending on the importance
of fingerprint elements. Another direction is to use our system
as a basis for request clustering mechanisms, which can help
to uncover new relations between requests.
