# EL-TCP-States-1
Here we explore TCP connection states during a normal TCP connection at both client and server. The visible states for a client program in general are ESTABLISHED and TIME_WAIT (assuming client initiates the connection closure). Similarly,  connection States at TCP server are LISTEN and ESTABLISHED, and when client initiates the connection close, the TCP Connection at server is closed and nothing is visible.

When the underlying network connecting a client and server drops some packets for some reasons for example firewall implementation issues and poses challenges in a succeful connection setup, then other states for TCP connection are visible for client and server. Client will remain in SYN_SENT state and connection on server side may witness SYN_RCVD state.

The article provides an insight into TCP State transtions. The digrams for TCP State transitions are
available in file **EL-TCP-State-Transitions.pdf**.
