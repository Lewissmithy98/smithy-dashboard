# 🏡 Lewis's Home Assistant Dashboard

Welcome to my custom-built **Home Assistant Dashboard**!  
Designed mainly for a **wall-mounted Fire HD10 tablet** running **Fully Kiosk Browser**, but fully optimised for laptops and mobiles too.

This dashboard focuses on **style**, **functionality**, and **efficiency**, blending a minimalist design with powerful automations and smart interactions.

---

## 📸 Overview

| Feature                         | Description                                                  |
|:---------------------------------|:-------------------------------------------------------------|
| **Responsive Layout**           | Scales perfectly across wall tablets, laptops, and phones.   |
| **Modern Theme**                | Clean muted colours, soft shadows, rounded cards.            |
| **Dynamic Popups**              | Room-based light control with smooth popups.                 |
| **Quick Controls**              | Heating, scenes, alerts, and more on the home screen.         |
| **Calendar Integration**        | Upcoming events + UK holidays using calendar-card-pro.       |
| **Baby Countdown**              | Dynamic countdown widget with days left.                     |
| **Velux and Fridge Alerts**      | Conditional cards shown only when needed.                    |
| **Presence Detection**          | Car/home detection updating house icons live.                |
| **Optimised Tablet Experience** | Pull-to-refresh disabled, scroll areas managed carefully.    |

---

## 🛠 Requirements

You will need these integrations installed via [HACS](https://hacs.xyz/):

- [button-card](https://github.com/custom-cards/button-card)
- [browser_mod](https://github.com/thomasloven/hass-browser_mod)
- [calendar-card-pro](https://github.com/itcarroll/calendar-card-pro)
- [layout-card](https://github.com/thomasloven/lovelace-layout-card)
- [card-mod](https://github.com/thomasloven/lovelace-card-mod)
- *(Optional)* [bubble-card](https://github.com/CyberJunky/home-assistant-bubble-card)

⚙️ Fire HD10 tablet uses **Fully Kiosk Browser** for wall display.

---

## 📂 Repository Structure

```plaintext
📁 dashboards/
   └── main_dashboard.yaml     # Main dashboard layout
📁 popups/
   └── lights_on_popup.yaml     # Popup menu for lights control
📁 themes/
   └── swakes_theme.yaml        # Main minimalist theme
📁 images/
   └── dashboardicons/          # Custom home/car icons
📄 README.md                     # This file
