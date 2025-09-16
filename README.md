# 🏥 A Simulated SDN Environment for Remote Robotic Surgery

A simulation project that demonstrates **remote robotic surgery** using **Software Defined Networking (SDN)**.  
The project shows how latency-sensitive healthcare applications can be supported using SDN by ensuring fast feedback between surgeon and robot modules.  

---

## 📖 Summary
In remote robotic surgery, commands from the surgeon must be executed by the robot with **minimal latency**. If the robot’s response is delayed, a **Tactile Learner** provides predicted dummy feedback so the surgeon can continue the operation without interruption.  
This project simulates such an environment using **SDN architecture** and demonstrates how software-defined networks can meet the requirements of latency-critical applications.
---
## 🛠️ Technologies Used
### Languages
- **Python** → Surgeon module, Tactile learner, Timer, Mininet topology scripts  
- **NodeJS (JavaScript)** → Robot module (server-side)  

### Frameworks / Tools
- **Mininet** → Network emulator for SDN topology  
- **POX Controller** → SDN controller used in the simulation  
- **Tkinter (Python GUI)** → Simple interface for surgeon module  
- **Requests (Python library)** → HTTP communication between modules  
- **HTTP (protocol)** → For surgeon ↔ robot communication  

### Environment
- **Ubuntu (VirtualBox)** → Host operating system for Mininet + POX controller  
- **VirtualBox** → Used to run Ubuntu environment  
