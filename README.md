# 📺 TV Remote Simulator

A Java project demonstrating **Object-Oriented Programming** concepts through a TV remote control simulation.

![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)

---

## 🎯 Purpose

This project practices working with **classes and object-orientation** by creating a `TV` class that simulates a television with controllable properties like volume, channel, and power state.

---

## 🏗️ Class Structure

### TV Class
```java
public class TV {
    // Properties
    boolean isOn = false;
    int channel = 1;      // Range: 1-120
    int volume = 0;       // Range: 0-7

    // Methods
    void turnOn()
    void turnOff()
    void setChannel(int newChannel)
    void setVolume(int newVolume)
    void channelUp()
    void channelDown()
    void volumeUp()
    void volumeDown()
}
```

---

## ✨ Features

- **Power Control:** Turn TV on/off
- **Channel Management:**
  - Set specific channel (1-120)
  - Channel up/down navigation
- **Volume Control:**
  - Set specific volume (0-7)
  - Volume up/down adjustment
- **State Validation:** Operations only work when TV is on

---

## 🧠 OOP Concepts Demonstrated

| Concept | Implementation |
|---------|----------------|
| **Encapsulation** | Private properties with public methods |
| **State Management** | `isOn` flag controls method behavior |
| **Validation** | Boundary checking for channel/volume |

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/nedmac99/TvRemote.git
cd TvRemote

# Compile
javac TV.java TvRemote.java

# Run
java TvRemote
```