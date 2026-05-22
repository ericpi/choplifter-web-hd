# Choplifter HD (Web Edition)

![landing_image](images/og_image-v1.jpg)

An advanced web-based reimagining of the all-time arcade classic **Choplifter**. This project modernizes the beloved retro side-scrolling shoot-'em-up, delivering intense helicopter rescue operations directly inside modern web browsers with high-definition visual layouts and highly responsive flight physics.

Take command of three legendary rotorcraft, each possessing entirely unique flight characteristics, tactical advantages, and customized loadouts, to infiltrate hostile territory, neutralize anti-air defenses, and safely extract hostages.

## 🚀 Key Features

- **Classic Core Gameplay Reimagined**: Faithfully preserves the thrilling loop of the original *Choplifter*—fly deep behind enemy lines, clear out threats, land safely to board hostages, and return them safely to base.
- **Three Distinct Playable Helicopters**:
  - **Airwolf**: The legendary supersonic tactical interceptor. High speed, sleek armor, and devastating offensive capabilities—perfect for surgical strikes.
  - **CH-47 Chinook**: The heavy-lift powerhouse. Boasts massive hostage capacity and rugged endurance, allowing for large-scale evacuations under heavy fire.
  - **MD-500 Defender**: The ultra-nimble scout chopper. Exceptional maneuverability and tight turning radiuses, ideal for weaving through dense anti-aircraft networks and tight valleys.
- **Pure Web Technology**: Completely client-side execution, fully responsive, and optimized for instant play without any external downloads or plugin requirements.
- **Dynamic Battlegrounds**: High-intensity combat environments featuring multi-layered mountain terrains, localized explosions, changing weather elements, and scaling difficulty matrices.

## 🕹️ Controls & Mechanics

| Action             | Control (Keyboard) | Description                                            |
| ------------------ | ------------------ | ------------------------------------------------------ |
| **Thrust / Lift**  | `W`                | Increase altitude and rotor lift.                      |
| **Descend**        | `S`                | Decrease altitude / Land safely on level ground.       |
| **Fly Left**       | `A`                | Bank and accelerate to the left.                       |
| **Fly Right**      | `D`                | Bank and accelerate to the right.                      |
| **Primary Weapon** | `Spacebar`         | Fire forward-facing machine guns or heavy autocannons. |

### 💡 Tactical Flight Tips:

1. **Approach Speeds**: When landing to rescue hostages, ensure your vertical descent velocity is stable. Rough landings will damage your hull!
2. **Weight Mechanics**: Loading up the **CH-47 Chinook** with maximum capacity alters its inertia. Plan your banking angles early when heavily laden.
3. **High-RPM Stability**: Avoid extreme over-throttling during high-G evasive maneuvers to keep the flight control system stabilized.

## 🛠️ Technology Stack & Architecture

This project is engineered for optimal performance on web platforms utilizing modern front-end architecture.

- **Rendering Engine**: HTML5 Canvas / WebGL for smooth 60FPS high-definition performance.
- **Physics Framework**: Custom rigid-body and aerodynamic simulation handling lift, weight, drag, and rotor propulsion dynamics tailored for each helicopter asset.

## 📦 Getting Started & Installation

To run this project locally or deploy it to your own web hosting platform, follow these simple setup steps.

### Prerequisites

You only need a modern web browser and a lightweight local server environment.

### Local Setup

1. **Clone the Repository**:

   ```
   git clone https://github.com/ericpi/choplifter-web-hd.git
   cd choplifter-web-hd
   ```

2. **Launch a Local Server**: Since modern browsers restrict certain local file access via CORS, running the project through a local HTTP server is highly recommended.

   Using Python 3:

   ```
   python -m http.server 8080
   ```

   Using Node.js (`http-server` package):

   ```
   npx http-server -p 8080
   ```

3. **Play the Game**: Open your browser and navigate to `http://localhost:8080`.

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

*Disclaimer: This is a fan-driven web tribute to the classic Choplifter heritage, developed purely for educational and open-source demonstration purposes.*