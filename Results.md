# Results

- Can we really recover from a failure?
    - If we receive a bad packet and get lost, can we recover?
    - Is it better to reover or to close the connection?
- Advantages of using poll vs threads handlers
    - Which handler type can handle more packets?
    - Which handler type can handle more concurrent clients?
- Performace when sending packets
    - Differences when using a dedicated thread to send packets
- How the load balancer affects packet handling?
    - Is the performace the same when using a lb?
    - Can we really handle more clients / packets with 2 services and one lb?