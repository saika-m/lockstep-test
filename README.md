# Lockstep Test

> A Unity-based implementation for deterministic multiplayer simulations

LockstepTest is a specialized Unity project that implements and tests a lockstep architecture for creating perfectly synchronized multiplayer experiences. This architecture is particularly optimized for x86-based processors and ensures consistent gameplay across all connected clients.

## ✨ Features

- **🔒 Deterministic Lockstep Simulation** — Guarantees all clients remain perfectly synchronized by processing inputs in fixed time steps
- **🎮 Unity Integration** — Seamlessly integrates with Unity's powerful engine for efficient development and testing
- **⚙️ x86 Architecture Optimization** — Performance-tuned for x86-based processors to ensure reliable execution

## 📋 Prerequisites

- **Unity** — Version 2020.3 or higher
- **Git** — For repository management and version control

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/saika-m/locksteptest.git
cd locksteptest
```

### 2. Open in Unity

- Launch Unity Hub
- Click on "Add" and navigate to the cloned `locksteptest` folder
- Select and open the project

### 3. Run the Simulation

- Navigate to `Assets/Scenes` and open the `MainScene`
- Press the Play button in the Unity Editor to start the simulation

## 📁 Project Structure

| Directory | Contents |
|-----------|----------|
| `Assets/` | Game assets, scripts, scenes, and project resources |
| `Packages/` | Unity package dependencies |
| `ProjectSettings/` | Unity project configuration files |

## ⚙️ How It Works

The lockstep architecture follows this synchronized workflow:

1. **Input Collection** — Each client captures and records player inputs for the current frame
2. **Network Broadcasting** — All inputs are transmitted to either a central server or through a peer-to-peer network
3. **Input Synchronization** — The collective inputs are gathered and distributed to ensure uniformity across clients
4. **Deterministic Simulation** — Every client processes the identical input set simultaneously, maintaining perfect state synchronization

This methodical approach ensures that all clients experience the exact same game state, as each system processes identical inputs in the same sequence and timing.

## 👥 Contributing

We welcome contributions to improve LockstepTest! Here's how to get involved:

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add some amazing feature'`
4. Push to your branch: `git push origin feature/amazing-feature`
5. Open a pull request

## 📄 License

This project is licensed under the Apache 2.0 License. See the [LICENSE](LICENSE) file for details.

---

**Tags**: `unity` `lockstep` `deterministic` `multiplayer` `simulation` `x86` `synchronization`
