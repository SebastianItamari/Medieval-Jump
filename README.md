# Medieval Jump

**Medieval Jump** is a reimagined version of the classic game "Doodle Jump," set in a medieval world. The objective is to leap across platforms, climbing as high as possible while collecting coins to maximize your score. With its unique theme and engaging mechanics, this project offers a fresh twist on a classic favorite.

<p align="center">
  <img width="770" height="476" alt="image" src="https://github.com/user-attachments/assets/075bb2b1-c0d4-4da6-ae28-e5e6255e78e8" />
</p>

## How to Run the Game 🚀

To run **Medieval Jump** on your machine, follow these steps:

### 🛠️ Requirements

- **Unity Hub** installed  
- **Unity Editor** version `2022.3.20f1` or higher (recommended)

> ✅ *Make sure to use the recommended version in the project to avoid compatibility issues.*

### 📥 Clone the Repository

```bash
git clone https://github.com/SebastianItamari/Medieval-Jump.git
cd Medieval-Jump
```

### 🧩 Open in Unity
1. Launch Unity Hub.
2. Click on "Open" and select the cloned project folder.
3. Let Unity load the assets (this may take a few minutes).
4. Open the scene named **Start**.
5. Click the Play ▶️ button in the top center to run the game in the editor.

## About the Game 🎮
### 🗡️ Playable Characters
<table align="center">
  <tr>
    <td align="center">
      <img height="150" alt="Knight" src="https://github.com/user-attachments/assets/9030b53b-0538-4dac-86ce-1180090973d4"/><br/>
      <strong>Knight</strong>
    </td>
    <td align="center">
      <img height="150" src="https://github.com/user-attachments/assets/482f2122-7284-4b11-b0f7-29bccc88a6c6" alt="Lancer"/><br/>
      <strong>Lancer</strong>
    </td>
    <td align="center">
      <img height="150" alt="Axeman" src="https://github.com/user-attachments/assets/70940943-9db0-4bab-9921-47217d916c27"/><br/>
      <strong>Axeman</strong>
    </td>
  </tr>
</table>

### 🪙 Coins
  - Gold Coin: +30 points
  - Silver Coin: +20 points
  - Bronze Coin: +10 points

### 🧱 Platforms
<table align="center">
  <tr>
    <td align="center">
      <img height="100" alt="Platform 1" src="https://github.com/user-attachments/assets/209be40e-c193-4cd1-b6a8-c3ae8ba13820" /><br/>
      <strong>Platform 1 — Jump Height: 13</strong>
    </td>
    <td align="center">
      <img height="100" alt="Platform 2" src="https://github.com/user-attachments/assets/a12eefcb-c3fb-4356-9a68-085d4fd2153a" /><br/>
      <strong>Platform 2 — Jump Height: 22</strong>
    </td>
    <td align="center">
      <img height="100" alt="Platform 3" src="https://github.com/user-attachments/assets/f4c0204a-8d71-499d-b093-f10608a0fecf" /><br/>
      <strong>Platform 3 — Jump Height: 27</strong>
    </td>
  </tr>
</table>

## 📐 Levels Overview

The following table summarizes the key parameters of each level, including platform spacing, horizontal movement speed, and coin spawn frequency:

| Level   | Vertical Distance Between Platforms (`varY`) | Horizontal Speeds (`horizontalSpeeds`) | Coin Spawn Chance (`recurrenceCoin`) |
|---------|----------------------------------------------|----------------------------------------|------------------------------------|
| Level 1 | 2.5                                          | Platform 1: 0<br/>Platform 2: 2<br/>Platform 3: 1                                | 1 in 4 (25%)                  |
| Level 2 | 3.3                                         | Platform 1: 1<br/>Platform 2: 3<br/>Platform 3: 2                                | 1 in 8 (12.5%)                  |
| Level 3 | 4.1                                         | Platform 1: 2<br/>Platform 2: 4<br/>Platform 3: 3                                | 1 in 12 (8.33%)                  |
| Level 4 | 5                                          | Platform 1: 3<br/>Platform 2: 5<br/>Platform 3: 4                               | 1 in 16 (6.25%)                |

### 🕹️ Demo
https://github.com/user-attachments/assets/c1bd5960-8c3c-40fb-8875-9a5f84b1fa72

> ℹ️ *For demonstration purposes, level durations have been shortened. To extend them, increase the value of the `spaceBetweenLevels` variable in the `Medieval-Jump/Assets/Scripts/CameraScript.cs` file. The current value is set to `50`.*

## Authors 🧑‍💻
- [@SebastianItamari](https://github.com/SebastianItamari)
