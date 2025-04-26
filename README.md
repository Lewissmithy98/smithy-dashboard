# 🏡 Home Assistant Dashboard - Minimalist Smart Home

A complete, clean, minimal Home Assistant dashboard designed for an easy and stylish user experience.  
Built to be tablet-friendly and glanceable, while still powerful for daily use.

---

## ✨ Features

- **Beautiful minimalistic design** using the [Swakes Theme](https://github.com/Swakes/homeassistant-swakes-theme)
- **Custom vertical-stack layout** to organise quick controls, statuses, and calendar
- **Fully responsive** for tablets, laptops, and wall panels
- **Real-time Smart Home Controls**:
  - Heating (Hive Thermostat integration)
  - Velux window status and fridge door monitoring
  - Lights-on counter with dynamic popups
  - Quick all-lights off buttons
- **Upcoming Events View** with a modern calendar (using [Calendar Card Pro](https://github.com/finity69x2/calendar-card-pro))
- **Dynamic conditional cards** (only show controls when needed)
- **Pulse effects** for active warnings (e.g., lights left on)

---

## 🧩 Integrations and Custom Cards Used

- [button-card](https://github.com/custom-cards/button-card)
- [calendar-card-pro](https://github.com/finity69x2/calendar-card-pro)
- [browser_mod](https://github.com/thomasloven/hass-browser_mod) (for popups)
- [vertical-stack-in-card](https://github.com/ofekashery/vertical-stack-in-card)
- [mushroom-cards](https://github.com/piitaya/lovelace-mushroom)
- [layout-card](https://github.com/thomasloven/lovelace-layout-card)

---

## 🎨 Theme

- Using the **Swakes** Theme for Home Assistant
- Highly recommended for matching colours, styling, and clean UI
- 👉 [View the Swakes Theme Here](https://github.com/Swakes/homeassistant-swakes-theme)

---

## 🖥️ Screenshots

| Tablet View | Laptop View |
|:-----------:|:-----------:|
| ![Tablet View](url-to-your-tablet-screenshot) | ![Laptop View](url-to-your-laptop-screenshot) |

---

## 📁 Folder Structure

```
/dashboard
  ├── /dashboard.yaml
  ├── /button-card-templates.yaml
  ├── /themes/swakes.yaml
  ├── /images/
        ├── house-with-car.png
        ├── house-without-car.png
```

---

## 🚀 Setup Instructions

1. Install required HACS custom cards (listed above).
2. Download the [Swakes Theme](https://github.com/Swakes/homeassistant-swakes-theme) and install to your themes folder.
3. Copy the dashboard YAML files into your `/dashboard/` folder.
4. Set up your dashboard in Home Assistant UI:
   - **Configuration > Dashboards > Add Dashboard**
   - Choose your main `dashboard.yaml` as the source.
5. Enjoy your new clean, minimal dashboard!

---

## 🔥 Important Notes

- Designed for **Fixed Tablet Layouts**.
- Optimised for **Fully Kiosk Browser** wall tablets.
- Manual refresh / pull-down actions have been considered during the layout.
- Conditional cards will dynamically adjust the content without ruining the overall layout.

---

## 📜 Credits

- Huge thanks to **Swakes** for the beautiful Home Assistant theme!  
  [👉 View Swakes Theme on GitHub](https://github.com/Swakes/homeassistant-swakes-theme)
- Special thanks to the Home Assistant community for the endless inspiration.

---

## ❤️ Support

If you found this useful, feel free to ⭐ star the repository or share your setup ideas too!

---

> Designed with love for a clean, efficient, stylish Smart Home experience.
