# Running Sensor System / Koşu Sensör Sistemi

---

## 🇬🇧 English

### Overview

ESP32-based wearable system for real-time running analysis using IMU sensor data. The system evaluates key biomechanical running metrics to provide feedback on running performance and technique.

The device is mounted on the top of the runner’s shoe and continuously collects motion data. Based on this data, it analyzes cadence, impact force (G-force), ground contact time (estimated), flight time, impact consistency, and running rhythm stability.

If inefficient or potentially harmful running patterns are detected, the system provides real-time feedback via vibration alerts and sends data to a mobile application through Bluetooth communication.

---

### Features
- Cadence tracking  
- Impact force (G-force) detection  
- Ground contact time estimation  
- Impact consistency analysis  
- Running rhythm stability evaluation  
- Real-time feedback (vibration + mobile app)

---

### Hardware
- ESP32 DevKit  
- MPU6050 IMU sensor  

---

### Goal
To improve running technique using a low-cost wearable system that provides real-time feedback based on motion analysis.

---

## 🇹🇷 Türkçe

### Genel Bakış

ESP32 tabanlı giyilebilir bir koşu analiz sistemidir. Sistem, IMU sensör verilerini kullanarak gerçek zamanlı koşu performansı ve teknik analizi gerçekleştirir.

Cihaz, koşucunun ayakkabısının üst kısmına monte edilir ve sürekli olarak hareket verilerini toplar. Bu veriler kullanılarak kadans, darbe kuvveti (G-kuvveti), yerle temas süresi (tahmini), uçuş süresi, darbe tutarlılığı ve koşu ritmi kararlılığı gibi temel biyomekanik metrikler analiz edilir.

Sistem, verimsiz veya potansiyel olarak zararlı koşu paternlerini tespit ettiğinde titreşim ile anlık geri bildirim verir ve verileri Bluetooth üzerinden mobil uygulamaya iletir.

---

### Özellikler
- Kadans takibi  
- Darbe kuvveti (G-kuvveti) ölçümü  
- Yerle temas süresi tahmini  
- Darbe tutarlılığı analizi  
- Koşu ritmi kararlılığı değerlendirmesi  
- Gerçek zamanlı geri bildirim (titreşim + mobil uygulama)

---

### Donanım
- ESP32 DevKit  
- MPU6050 IMU sensörü  

---

### Amaç
Düşük maliyetli giyilebilir bir sistem kullanarak, hareket analizi temelli gerçek zamanlı geri bildirim ile koşu tekniğini geliştirmek.
