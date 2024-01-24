# PORT.md
### PROBLEM
What was the port number of the reverse shell of the server?

Please use the attachment of the first challenge.

Flag Format: KCTF{port}

### SOLUTION
we needed to find the port number on the pcap file.
in the same file in wireshark i scrolled down and found two ports talking to each other , so i tried both and one of them works to be the flag.

![Screenshot from 2024-01-25 01-05-18](https://github.com/adwait3/knight/assets/148553626/499cce4a-0169-4738-9c4a-be8e52915678)
 ### FLAG
 KCTF{6200}
