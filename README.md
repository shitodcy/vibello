# 🔔 Vibello – Gelang Getar untuk Teman Tunarungu

**Vibello** adalah perangkat wearable berupa gelang getar yang dirancang untuk membantu teman-teman Tunarungu merespons bel pintu secara **real-time**. Saat seseorang menekan bel, gelang akan memberikan **notifikasi berupa getaran hening** yang langsung dirasakan oleh pengguna.

---

## 🚀 Fitur Utama

* 🔔 **Deteksi Bel Otomatis** – Saat bel ditekan dan langsung mengirimkan sinyal ke gelang.
* 📳 **Getaran Notifikasi** – Gelang memberikan getaran sebagai respons terhadap sinyal dari bel.
* 📡 **Koneksi Nirkabel & Real-time** – Komunikasi cepat dan stabil antara bel dan gelang.
* 🔋 **Efisien dan Hemat Daya** – Desain hemat energi agar baterai tahan lebih lama.

---

## 💡 Motivasi

Banyak teman Tunarungu yang tidak menyadari saat bel pintu ditekan. **Vibello** hadir sebagai **solusi inklusif** yang membantu mereka tetap tanggap terhadap lingkungan sekitar, dengan **teknologi sederhana, terjangkau, dan mudah digunakan**.

---

## 🛠️ Komponen Perangkat Keras

| Komponen                         | Deskripsi                          |
| -------------------------------- | ---------------------------------- |
| **ESP32**                      | Otak dari sistem                   |
| **Push Button 12mm**           | Tombol fisik untuk bel             |
| **LED Hijau**                  | Indikator visual pada bel          |
| **DC Power Jack 2.1mm Female** | Input daya                         |
| **DC Step-Up XL6009**          | Pengatur tegangan DC               |
| **Switch On/Off**              | Saklar utama pada gelang           |
| **TP4056 Type-C**              | Modul pengisian daya baterai       |
| **Baterai Li-Po 3.7V 1000mAh** | Baterai utama untuk gelang dan bel |
| **Box Plastik 100×60×25 mm**   | Casing gelang                      |
| **Box Plastik 125×80×32 mm**   | Casing bel                         |

---

## 🔧 Cara Kerja Singkat

1. Tombol bel ditekan oleh pengunjung.
2. ESP32 mengirimkan sinyal secara nirkabel ke gelang.
3. Gelang menerima sinyal dan mengaktifkan motor getar.
4. Pengguna merasakan getaran sebagai notifikasi adanya tamu.
