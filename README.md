# Assignment 1 – Basic Network Topologies (Cisco Packet Tracer)
## Author
- **Name:** Vaibhav Kedia  
- **Semester:** IV  
## Course Information
- **Course Code:** ENCS304 – Computer Networks  
- **Program:** B.Tech CSE (AI & ML)  
- **Experiment:** Assignment 1  
- **Tool Used:** Cisco Packet Tracer  

---

## Objective
To design and analyze basic LAN topologies using Cisco Packet Tracer and understand
how network topology affects connectivity, performance, and fault tolerance.

---

## Topologies Implemented

### 1. Star Topology (Switch-Based)
- One switch connected to four PCs
- Each PC assigned a unique IPv4 address
- Successful ICMP communication verified using ping

### 2. Bus-like Topology (Hub-Based)
- Switch replaced with a hub
- Same IP addressing scheme maintained
- Observed broadcast behavior and packet flooding

### 3. Ring-like Topology (Loop)
- Three switches connected in a loop
- PCs attached to each switch
- Communication tested across multiple switches

### 4. Failure Test
- One link in the ring topology was disconnected
- Network continued to function using alternate path
- Demonstrated fault tolerance in ring topology
  
---

## How to Run the Experiment
1. Open Cisco Packet Tracer
2. Load `exp1_topologies.pkt`
3. Switch between **Realtime** and **Simulation** mode
4. Use **Command Prompt** on PCs to test connectivity using `ping`

---

## Conclusion
This experiment demonstrated how different network topologies impact communication,
performance, and fault tolerance. Ring topology showed better reliability compared to
star and bus layouts.

---

