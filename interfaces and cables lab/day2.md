# Day 2: Interfaces and Cables

Today's session focused on the fundamental aspects of network connectivity, specifically the types of cables and interfaces used to connect network devices. The hands-on Packet Tracer lab was an excellent way to apply the theoretical knowledge of Ethernet protocols for both UTP (Unshielded Twisted Pair) and fiber optic cables.

---

## Key Lessons Learned

### 1. Understanding Cable Types and Their Use Cases
I learned about the two primary types of copper Ethernet cables:

- **Straight-through cables**: Used to connect devices of different types (e.g., a PC to a switch, or a router to a switch).  
- **Switches** transmit data over Tx 3,6 and receive data over Rx 1, 2 with straight through cables. 
- **Routers** are the same as pcs they transmit over Tx 1,2 and Rx receive data over 3,6 
- **Crossover cables**: Used to connect devices of the same type (e.g., a switch to a switch, or a router to a router).  
  - This ensures that the transmit pins of one device connect to the receive pins of the other, and vice versa.

---

### 2. The Role of Auto MDI-X
- Modern networking equipment includes **Auto MDI-X**, which automatically detects the correct pin configuration.  
- This makes the choice between straight-through and crossover cables less critical.  
- For devices without Auto MDI-X, knowing the correct cable type remains essential for a successful connection.

---

### 3. Fiber Optic Cabling
I explored the use of fiber optic cables for long-distance connections:

- **Single-mode fiber**: Suitable for very long distances (kilometers), commonly used for wide-area or inter-campus networks.  
- **Multimode fiber**: Used for shorter distances (up to a few hundred meters), typically within a building or campus.

---

### 4. Practical Application in Packet Tracer
- The lab reinforced the importance of selecting the right medium.  
- **UTP** has a distance limitation of **100 meters**, whereas **fiber optic** supports longer distances.  
- Choosing the proper cable type ensures a reliable and efficient network connection.
