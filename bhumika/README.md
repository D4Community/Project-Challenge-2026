# 🏠 Smart Home Dashboard

> **Assigned to:** Bhumika  
> **Difficulty:** Intermediate  
> **Estimated Time:** 6-8 hours (1-2 hours/day for 4 days)  
> **Deadline:** January 10, 2026

---

## 📌 Project Overview

Build a web-based smart home dashboard to control virtual IoT devices! Toggle lights, adjust thermostats, view sensor data—all with a beautiful real-time updating interface.

### Virtual Devices:
- 💡 Smart Lights (on/off, brightness)
- 🌡️ Thermostat (temperature control)
- 🚪 Door Lock (locked/unlocked)
- 📹 Security Camera (active/inactive)
- 🔌 Smart Plugs (on/off)

---

## 🎯 What You'll Learn

| You Already Know | You Will Learn |
|------------------|----------------|
| Python | Flask REST API |
| IoT concepts | AJAX for real-time updates |
| Git & GitHub | JSON state management |

---

## ✅ Tasks

- [ ] Set up Flask project
- [ ] Create device state storage (JSON file or in-memory)
- [ ] Build API endpoints for each device:
  - GET /api/devices - all device states
  - POST /api/device/:id/toggle - toggle on/off
  - POST /api/device/:id/set - set value (brightness, temp)
- [ ] Create beautiful dashboard HTML/CSS
- [ ] Add device cards with icons
- [ ] Use JavaScript/AJAX to call API without page refresh
- [ ] Update UI immediately when device toggled
- [ ] Add status indicators (green=on, red=off)
- [ ] Add slider for brightness/temperature
- [ ] Deploy on Render/PythonAnywhere

---

## 🌟 Bonus Challenges

- [ ] **+5 points:** Add device schedules (turn on at specific time)
- [ ] **+10 points:** Add "scenes" (Movie mode = dim lights, etc.)
- [ ] **+10 points:** Add simulated sensor data (temperature readings)
- [ ] **+5 points:** Add activity log (history of actions)

---

## 📦 Deliverables

1. Working dashboard with all devices
2. Real-time toggle without refresh
3. Clean, intuitive UI
4. Deployed live link
5. Code pushed to GitHub

---

**Good luck! 🚀**
