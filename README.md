# 🌤️ Project: ESP32 Weather Cloud

**Author:** Alexsander Gutierez  
**Date:** 27/12/2023  
**License:** MIT  
**Revision:** 1

ESP32-CAM reading and displaying temperature and humidity data on a 0.96-inch OLED display, and sending this data to **Arduino Cloud** and **Google Sheets**.

---

## 🧩 Step 1: Installation

1. Open this project in your IDE.  
2. Install the required libraries.  
3. Edit the file `arduino_secrets.h` with your credentials.  
4. Upload the project to your ESP32 board.  
5. Release to the world! 🚀

---

## 🔌 Step 2: Assemble the Circuit

> The `layout.png` file is under development...

---

## 💻 Step 3: Load the Code

Upload the code contained in this sketch onto your board.

### 📁 Folder Structure

ESP32_CAM_dec27a/ → Arduino sketch folder
├── arduino_secrets.h → File for your secrets (Wi-Fi, tokens)
├── ESP32_CAM_dec27a.ino → Main Arduino file
├── ReadMe.adoc → Original AsciiDoc version
├── README.md → This file
├── sketch.json → Arduino Cloud configuration file
└── thingProperties.h → Cloud properties and secrets usage

---

## 📜 License

This project is released under the **MIT License**.

---

## 🧾 Bill of Materials (BOM)

| ID | Part Name          | Quantity |
|----|--------------------|-----------|
| 1  | ESP32-CAM          | 1         |
| 2  | Display OLED 0.96" | 1         |
| 3  | DHT22 Sensor       | 1         |

---

## 🎬 Preview

[![Project preview animation](preview.gif)](preview.mp4)

Click the image above to watch the full demo video.

---

> 💡 Tip: To view live sensor data on **Arduino Cloud**, ensure your Thing properties are properly linked to your `thingProperties.h` file.
