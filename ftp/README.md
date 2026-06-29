# FTP

That is one of the oldest protocols on the internet. It operates within the application layer of the TCP/IP protocol stack, hence it is on the same layer as HTTP or POP. These protocols work with the support of browsers or emailclients to perform their services.

When FTP is used to upload files or download files from a server two channels are opened. First, a control channel between the client and the server through TCP port 21. Then, both objects in this communication can establish the data channel via TCP port 20. This channel is used exclusively for data transmission.


Active and passive FTP exists. Active is when the connection is established described above via TCP port 21 and the client informs the server via which client-side port the server can transmit its response, but if firewall protects the client all responses and external connections will be blocked. That's where the passive mode comes in. In passive, the server announces a port through which the client can establish the data channel. That way the firewall does not block the transfer.



