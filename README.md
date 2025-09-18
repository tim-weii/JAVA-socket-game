#  Multiplayer Online Bomb Game

https://github.com/tim-weii/JAVA-socket-game/assets/66638719/3a1d9d41-fd08-4c77-9da3-6a4bb8f17c68.mp4  

---

##  Project Overview  
This project was developed as the **final assignment** for the *Network Programming* course.  
It is a **multiplayer real-time bomb game** implemented in **Java** using **Socket programming**.  

The game focuses on **real-time synchronization** between multiple players, handling state updates such as movement, collisions, and health across different clients.  
Key challenges include:  
- Ensuring **low-latency synchronization** over sockets  
- Handling **multi-threading** for concurrent player actions  
- Managing **game events** (bomb explosion, health deduction, player elimination)  

Despite the difficulties, the system successfully supports **up to 10 players** playing simultaneously with real-time interactions.  

---

##  Gameplay Rules  
- Use **Arrow Keys (↑ ↓ ← →)** to control movement.  
- Combine directions (e.g., ↑ + →) to move diagonally.  
- Colliding with a **bomb** deducts **20 HP**.  
- Each player starts with **100 HP** → hit **5 times** = eliminated.  

---

## 🖼 Screenshots  

### Bombs  
<p align="center">
  <img src="https://github.com/tim-weii/JAVA-socket-/assets/66638719/c71c86df-c535-425e-9299-21b39fa93124" width="300"/>
  <img src="https://github.com/tim-weii/JAVA-socket-/assets/66638719/7f1f3013-b65a-468c-af20-14d15f50bef8" width="300"/>
</p>

### Explosion  
<p align="center">
  <img src="https://github.com/tim-weii/JAVA-socket-/assets/66638719/5c540472-e867-430d-86ba-075866f306d3" width="400"/>
</p>

### Health Bar  
<p align="center">
  <img src="https://github.com/tim-weii/JAVA-socket-/assets/66638719/033750d9-a617-4a0d-b299-3685ea62771a" width="400"/>
</p>

### Bubble Counter  
<p align="center">
  <img src="https://github.com/tim-weii/JAVA-socket-/assets/66638719/ec696704-521d-4dae-828e-44f7560d1f1c" width="400"/>
</p>

### Keyboard Control & Player Orientation  
<p align="center">
  <img src="https://github.com/tim-weii/JAVA-socket-/assets/66638719/433d76cb-2000-4cd5-8320-27a7c4848743" width="300"/>
  <img src="https://github.com/tim-weii/JAVA-socket-/assets/66638719/055e1eb1-bb59-4a11-84b6-c2dcc19c3e23" width="300"/>
</p>

---

## ⚙ Tech Stack  
- **Language:** Java  
- **Networking:** Socket (TCP)  
- **Concurrency:** Multi-threading for client-server communication  
- **Game Logic:** Collision detection, health management, player state synchronization  

---

##  Outcome  
- Successfully deployed a **real-time multiplayer game** supporting 10 concurrent players.  
- Implemented **synchronized gameplay** with socket-based communication.  
- Learned deeply about **sockets, threading, synchronization, and latency handling** in real-time systems.  
- More than just a course project — finishing it felt like survival rather than just achievement! 
