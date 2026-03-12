<div align="center">

# ⚡ Gevako - Smart Home Hardware, Made in NL 🇳🇱

### *Because your house deserves better than being dumb*

<a href="https://www.gevako.com/shop/" target="_blank">🛒 Shop</a> • <a href="https://gevako.nl/ondersteuning/" target="_blank">📖 Documentation</a> • <a href="https://www.gevako.com/contact/" target="_blank">💬 Support</a> • <a href="https://www.youtube.com/@gevako" target="_blank">🎥 Tutorials</a>

![Made with ESPHome](https://img.shields.io/badge/ESPHome-000000?style=for-the-badge&logo=esphome&logoColor=white)
![Home Assistant](https://img.shields.io/badge/Home_Assistant-41BDF5?style=for-the-badge&logo=home-assistant&logoColor=white)
![Made in Netherlands](https://img.shields.io/badge/Made_in-Netherlands_🇳🇱-FF6C37?style=for-the-badge)
![Open Source](https://img.shields.io/badge/Open_Source-❤️-green?style=for-the-badge)

</div>

---

## 👋 Welcome to Gevako!

We make **smart switches that actually work** - no cloud nonsense, no monthly fees, just pure local control for your Home Assistant setup.

**Why Gevako?** Because we got tired of:
- 🚫 Cloud dependencies that break when WiFi hiccups
- 🚫 Proprietary firmware that locks you in
- 🚫 Products that need a PhD to install
- 🚫 "Smart" devices that aren't smart at all

**So we built our own.** Open source firmware (ESPHome), designed & manufactured in the Netherlands, and ready to rock your smart home in under 5 minutes.

---

## 🔥 Our Products

<table>
<tr>
<td width="50%">

### 🎛️ Gevako RS6
**6-Channel Smart Relay**

<img src="https://github.com/user-attachments/assets/b819c35c-6a3c-4872-b763-25836b1a37a5" width="200"/>

- ✅ 6× independent relays (16 A each)
- ✅ 250 VAC / 30 VDC max
- ✅ ESP32-C6 processor
- ✅ ESPHome native
- ✅ DIN-rail mountable

**Perfect for:** Pool pumps, outdoor lighting, zone control

<a href="https://www.gevako.com/shop/gevako-rs6-smart-switch-home-assistant/" target="_blank">📦 Get RS6</a> • [📚 Docs](https://github.com/gevako-nl/rs6)

</td>
<td width="50%">

### 🎚️ Gevako RS5
**5-Channel Smart Relay**

<img src="https://github.com/user-attachments/assets/089008c8-97aa-40c3-a091-e8da973dbac9" width="200"/>

- ✅ 5× relays (16 A each with common source)
- ✅ 250 VAC / 30 VDC max
- ✅ ESP32-C6 processor
- ✅ ESPHome native
- ✅ Compact design

**Perfect for:** Garden lighting, garage control, full-house automation

<a href="https://www.gevako.com/shop/gevako-rs5-smart-switch-home-assistant/" target="_blank">📦 Get RS5</a> • [📚 Docs](https://github.com/gevako-nl/rs5)

</td>
</tr>
</table>

---

## 🚀 Quick Start

**Got 5 minutes? You're basically done.**
```yaml
# 1. Add to ESPHome (takes 30 seconds)
esphome:
  name: gevako-rs6
  
esp32:
  board: esp32-c6-devkitc-1

# 2. Flash firmware (takes 2 minutes)
# 3. Add to Home Assistant (takes 1 click)
# 4. Start automating! 🎉
```

**Need help?** Check our <a href="https://www.youtube.com/@gevako" target="_blank">step-by-step tutorials</a> (in Dutch, with English subtitles coming soon!)

---

## 🎯 Why Developers Love Us

| Feature | Gevako | "Smart" Switches |
|---------|--------|------------------|
| **Open Source** | ✅ Full ESPHome | ❌ Proprietary |
| **Local Control** | ✅ 100% offline | ❌ Cloud required |
| **Home Assistant** | ✅ Native support | ⚠️ Via cloud/MQTT |
| **Update Control** | ✅ You decide | ❌ Forced updates |
| **Privacy** | ✅ Your data stays yours | ❌ Sent to servers |
| **Cost** | ✅ One-time purchase | ❌ Monthly subscription |

---

## 📺 Video Tutorials

We're building a YouTube channel with Home Assistant tutorials! (Dutch, but code is universal 😉)

**Latest:** <a href="https://www.youtube.com/watch?v=BqMmWnvCVKY" target="_blank">Automate Garden Lighting with RS5</a>

<a href="https://www.youtube.com/@gevako" target="_blank"><img src="https://img.shields.io/badge/YouTube-Subscribe-red?style=for-the-badge&logo=youtube" /></a>

---

## 🛠️ Technical Specs

**Processor:** ESP32-C6 (RISC-V, WiFi 6)  
**Firmware:** ESPHome (open source, customizable)  
**Power:** 230 VAC / 5 VDC (USB-C)  
**Switching:** 16A per channel @ 250VAC / 30VDC  
**Certifications:** CE marked  
**Mounting:** DIN-rail compatible  
**Made in:** Land van Maas en Waal, Netherlands 🇳🇱

---

## 💡 Real-World Projects

**What are people building?**

- 🌿 Garden lighting with sunset automation
- 🏊 Pool pump scheduling
- 🚗 Garage door control
- 🏡 Whole-house zone control
- 🎄 Holiday lighting (because manual switching is *so* 2020)

**Built something cool?** <a href="https://www.gevako.com/contact/" target="_blank">Show us!</a> We love seeing what you create.

---

## 🤝 Contributing

Found a bug? Want a feature? Have an idea?

- 🐛 [Report issues](https://github.com/gevako-nl/rs6/issues)
- 💡 [Request features](https://github.com/gevako-nl/rs5/issues)
- 📧 <a href="https://www.gevako.com/contact/" target="_blank">Email us</a>

All firmware is open source - fork it, modify it, make it yours!

---

## 📦 Where to Buy

🛒 **Official Webshop:** <a href="https://www.gevako.com/shop/" target="_blank">gevako.nl/webshop</a>

- ✅ Free shipping in NL (orders €75+)
- ✅ Fast delivery (usually next-day)
- ✅ Dutch support (we actually speak Dutch!, but also English 😉)
- ✅ No surprises (what you see is what you pay)

---

## 🌐 Community & Support

- 💬 **Email:** <a href="mailto:info@gevako.com">info@gevako.com</a>
- 📖 **Docs:** <a href="https://www.gevako.com/support/" target="_blank">gevako.nl/ondersteuning</a>
- 🎥 **YouTube:** <a href="https://www.youtube.com/@gevako" target="_blank">@gevako</a>
- 🏠 **Home Assistant Forum:** Coming soon!

---

## 📜 License

All firmware in these repositories is licensed under **MIT License** - do whatever you want with it!

Hardware designs are © Gevako B.V., but firmware is yours to hack. 🔓

---

## 🎉 Fun Facts

- 🌷 **100% Dutch-made** (from design to PCB assembly)
- ⚡ **ESP32-C6** was chosen because we love RISC-V (and WiFi 6 is cool)
- 🐕 **Our mascot is a German electrician** (we trust him with our life ❤️)
- ☕ **Customer support runs on coffee** - good coffee makes good support

---

<div align="center">

### Made with ❤️ (and way too much coffee) in the Netherlands

**Gevako B.V.** • KVK: 93569882 • BTW: NL866453428B01

<a href="https://www.gevako.com/" target="_blank">Website</a> • <a href="https://www.gevako.com/shop/" target="_blank">Shop</a> • <a href="https://www.gevako.com/support/" target="_blank">Support</a> • <a href="https://youtube.com/@gevako" target="_blank">YouTube</a>

⭐ **If you like what we're building, give us a star!** ⭐

</div>
