MITRE STEM CTF Summer 2012
Grab Bag 300 – Combined Aspects
Flag: MCA-D51CD2A3

Description of challenge:
Participants are provided with a packet capture (pcap) file and an encrypted 7zip archive, entitled enterUsername.7z. Archives are used in this challenge to emulate interfaces with physical machines, which, due to the current constraints of the architecture, are not readily available. The packet capture represents a login session by the fictional protagonist of the story (Security Sam) between his home machine and his work machine. The capture is a telnet conversation, so pulling out his username and password are trivial.

These credentials are required to decrypt and decompress two levels of archive. Once this has been accomplished, Sam’s ‘home folder’ is revealed. Inside, a variety of files and folders are provided to the participant. These include random Escher drawings, a scan of a tattered note, a mail directory, a ‘my friend’ directory and ‘baconbuddyshare.7z,’ an archive holding the dump of the home directory of Sam’s friend, B. Budstein (aka baconbuddy). The Escher drawings are just things that Sam, who is a fan, has downloaded into his home directory. The mail directory holds typical mail messages that one can find in the workplace of Business Webs, a fictional company. In particular, the drama focuses on the cancellation of the annual employee barbecue. Sam, a security guard at Business Webs, doesn’t have many friends. His one friend, B. Budstein, apparently had made no plans in lieu of the BBQ. However, due to a mishap with the shredder, Sam receives a note that isn’t intended for him, indicating that his best friend has betrayed him. What else is someone sitting in front of CCTVs and a computer all day to do? Start collecting (somewhat creepy) data on his friend and try to hack into his account.

So, to represent this, baconbuddy’s share is provided via an encrypted 7z archive. The password is B’s eldest child, Jula. The subsequent layers of encryption are protected by his next two children, Amby and Quella. What did Sam do when he got into B’s file? It’s up to the participant to decide, but we’re left with a series of bacon-related images. These images, if trolled for strings, will easily yield the flag (with a little assistance from a hex editor).

Programs required:
A text editor
An image viewer that supports JPEG and PNG files
7zip or comparable archival program

Files included:

Challenge:
enterUsername.7z
securityDump.pcap