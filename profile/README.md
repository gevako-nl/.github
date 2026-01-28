<div align="center">

# ⚡ Gevako - Smart Home Hardware, Made in NL 🇳🇱

### *Because your lights deserve better than being dumb*

[🛒 Webshop](https://gevako.nl/webshop/) • [📖 Documentation](https://gevako.nl/ondersteuning/) • [💬 Support](https://gevako.nl/contact/) • [🎥 Tutorials](https://www.youtube.com/@gevako-nl)

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

- ✅ 6× independent relays (16A each)
- ✅ 250 VAC / 30 VDC max
- ✅ ESP32-C6 processor
- ✅ ESPHome native
- ✅ DIN-rail mountable

**Perfect for:** Pool pumps, outdoor lighting, zone control

[📦 Get RS6](https://gevako.nl/shop/gevako-rs6-slimme-schakelaar-home-assistant/) • [📚 Docs](https://github.com/gevako-nl/rs6)

</td>
<td width="50%">

### 🎚️ Gevako RS5
**5-Channel Smart Relay**

<img src="https://github.com/user-attachments/assets/089008c8-97aa-40c3-a091-e8da973dbac9" width="200"/>

- ✅ 5× independent relays (16A each)
- ✅ 250 VAC / 30 VDC max
- ✅ ESP32-C6 processor
- ✅ ESPHome native
- ✅ Compact design

**Perfect for:** Garden lighting, garage control, full-house automation

[📦 Get RS5](https://gevako.nl/shop/gevako-rs5-slimme-schakelaar-home-assistant/) • [📚 Docs](https://github.com/gevako-nl/rs5)

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

**Need help?** Check our [step-by-step tutorials](https://www.youtube.com/@gevako-nl) (in Dutch, with English subtitles coming soon!)

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

**Latest:** [Automate Garden Lighting with RS5](https://www.youtube.com/watch?v=BqMmWnvCVKY)

<a href="https://www.youtube.com/@gevako-nl"><img src="https://img.shields.io/badge/YouTube-Subscribe-red?style=for-the-badge&logo=youtube" /></a>

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

**Built something cool?** [Show us!](https://gevako.nl/contact/) We love seeing what you create.

---

## 🤝 Contributing

Found a bug? Want a feature? Have an idea?

- 🐛 [Report issues](https://github.com/gevako-nl/rs6/issues)
- 💡 [Request features](https://github.com/gevako-nl/rs5/issues)
- 🔧 Submit pull requests (we review fast!)
- 📧 [Email us](https://gevako.nl/contact/)

All firmware is open source - fork it, modify it, make it yours!

---

## 📦 Where to Buy

🛒 **Official Webshop:** [gevako.nl/webshop](https://gevako.nl/webshop/)

- ✅ Free shipping in NL (orders €75+)
- ✅ Fast delivery (usually next-day)
- ✅ Dutch support (we actually speak Dutch!, but also English 😉)
- ✅ No surprises (what you see is what you pay)

---

## 🌐 Community & Support

- 💬 **Email:** [info@gevako.nl](mailto:info@gevako.nl)
- 📖 **Docs:** [gevako.nl/ondersteuning](https://gevako.nl/ondersteuning/)
- 🎥 **YouTube:** [@gevako-nl](https://www.youtube.com/@gevako)
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
- 🚚 **We ship fast**
- ☕ **Customer support runs on coffee** - good coffee makes good support

---

<div align="center">

### Made with ❤️ (and way too much coffee) in the Netherlands

**Gevako B.V.** • KVK: 93569882 • BTW: NL866453428B01

[Website](https://gevako.nl) • [Shop](https://gevako.nl/webshop) • [Support](https://gevako.nl/ondersteuning) • [YouTube](https://youtube.com/@gevako)

⭐ **If you like what we're building, give us a star!** ⭐

</div>
