# ☕ Java Projects

A collection of Java projects demonstrating various programming concepts and techniques.

![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)

---

## 📁 Projects

### 📺 TV Remote Simulator

A project demonstrating **Object-Oriented Programming** concepts through a TV remote control simulation.

#### 🎯 Purpose

This project practices working with **classes and object-orientation** by creating a `TV` class that simulates a television with controllable properties like volume, channel, and power state.

#### 🏗️ Class Structure

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

#### ✨ Features

- **Power Control:** Turn TV on/off
- **Channel Management:**
  - Set specific channel (1-120)
  - Channel up/down navigation
- **Volume Control:**
  - Set specific volume (0-7)
  - Volume up/down adjustment
- **State Validation:** Operations only work when TV is on

#### 🧠 OOP Concepts Demonstrated

| Concept | Implementation |
|---------|----------------|
| **Encapsulation** | Private properties with public methods |
| **State Management** | `isOn` flag controls method behavior |
| **Validation** | Boundary checking for channel/volume |

#### 🚀 Running the TV Remote

```bash
# Compile
javac TV.java TvRemote.java

# Run
java TvRemote
```

---

## 🔜 More Projects Coming Soon

This repository will be updated with additional Java projects over time. Stay tuned!