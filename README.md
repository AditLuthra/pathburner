# 🔥 PathBurner

> Not just a line follower — a track killer.

**PathBurner** is a high-speed, all-PCB robot designed to dominate line-following and maze-solving challenges. With a curved sensor array, precision PID, and an ultra-light body, it burns paths — not batteries.

---

## ⚙️ Hardware Specs

- **MCU**: ESP32
- **Motors**: N20 geared with motor driver
- **Sensors**: 8x IR Reflective (curved layout)
- **Power**: 2S LiPo
- **Frame**: Custom PCB (integrated chassis)

---

## 🧠 Firmware Features

- 🔁 PID tuning via serial
- 🧠 Real-time calibration & compensation
- ⚡ High-speed logic loop with failsafe
- 🧪 Optional sensor fusion for curve prediction

---

## 📁 Repo Breakdown

| Folder        | Description |
|---------------|-------------|
| `/hardware`   | PCB layout, design files (KiCad), renders |
| `/firmware`   | All ESP32 firmware logic |
| `/control`    | PID theory, tuning logs, graphs |
| `/images`     | Build photos, wiring, silkscreen designs |

---

## 🚀 Roadmap


- [x] Stable PID control
- [ ] Dynamic turn prediction logic
- [ ] Bluetooth UI for runtime tuning
- [ ] Maze solving logic via waypoint memory

---

## 📜 License

MIT — burn tracks, not bridges.  
Feel free to remix, upgrade, and tag us when you race it.

---

> Built by [@AditLuthra](https://github.com/aditluthra) – because slow bots are boring.
