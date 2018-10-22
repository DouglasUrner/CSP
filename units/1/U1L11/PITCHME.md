## The Problem

How do we reliably send messages across an unreliable network?

---

## Today's Internet Simulator

Like the real Internet the simulator:

* Breaks messages into hunks called *packets.*
* Packets may be delivered out of order.
* Packets may get lost in transit - some packets may never be delivered.

**Our Challenge:** given these constraints, design a protocol that ensures reliable delivery of messages across the Internet.

---

## Develop Your Protocol

Guidelines: Make sure your protocol meets the following criteria:

* All communication must be done through the Internet Simulator.
* Your message must use at least 10 packets (80 ASCII characters). 
* Your protocol should allow for the possibility that the characters are entirely random.
* Do not assume the message is known beforehand.
* Both the sender and receiver must be confident the message was successfully transmitted and reconstructed.

Each member of your group should be on a **different** router.

---

## Present Your Protocol
