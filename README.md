# 🎯 BASE SNIPER  
A clean and minimal precision-timing arcade game built with **HTML5 Canvas**, **pure JavaScript**, and **Farcade SDK** integration.  
Designed for mobile-first gameplay on Remix.gg and fully open-source for learning or extending.

---

## 🚀 Overview

**BASE SNIPER** is a reaction-based timing game where the player must tap **exactly when the rotating pointer enters the neon glowing arc**.

Every successful hit:
- increases your score  
- speeds up the pointer  
- shrinks the target zone  
- moves the target to a new random angle  
- triggers haptic feedback (Farcade supported devices)

A single mistake ends the game.

---

## 🕹️ Features

- ⚡ Smooth 60 FPS canvas animation  
- 🎯 Precision-based hit detection  
- 🔵 Neon Base-inspired visual theme  
- 📱 Mobile-first design with tap controls  
- 🔊 Integrated hit / miss / background music  
- 🎮 Full Farcade SDK support:
  - `gameOver()`  
  - `ready()`  
  - `hapticFeedback()`  
  - `toggle_mute` event  
  - `play_again` event  

---

## 📦 Project Structure

This project is intentionally **single-file** for simplicity:

