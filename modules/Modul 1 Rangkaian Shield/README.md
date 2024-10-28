# 🌐 IoT Project - Modul 1 Rangkaian Shield
Ini adalah gambaran secara umum modul 1 mengenai rangkaian dasar isolation shield ESP32.

---

## 🔍 Tentang Optocoupler untuk Digital Input dan Output di ESP32

![Optocoupler](images/optocoupler.png)  <!-- Ganti dengan path gambar yang sesuai -->

Optocoupler? Yap, komponen ini adalah pahlawan diam-diam dalam dunia elektronik, terutama ketika kita perlu "mengisolasi" satu sirkuit dari sirkuit lainnya. Bayangkan, kamu punya dua perangkat yang perlu 'ngobrol' tapi gak mau saling mengganggu. Nah, di sinilah optocoupler beraksi!

### 🎯 Apa Itu Optocoupler?
Optocoupler, atau sering juga disebut optoisolator, adalah komponen elektronik yang menghubungkan dua sirkuit listrik tanpa kontak fisik langsung. Ini bikin aliran listrik dari satu sirkuit gak akan "loncat" ke sirkuit yang lain – jadi aman buat perangkat kamu!

### ⚙️ Cara Kerja Optocoupler
Di dalam optocoupler, ada dua bagian utama:
1. **LED (Light Emitting Diode)** di satu sisi, yang nyala saat ada arus.
2. **Phototransistor** di sisi lainnya, yang mendeteksi cahaya dari LED itu.

Ketika arus mengalir melalui LED, dia akan memancarkan cahaya yang diterima phototransistor. Hasilnya, phototransistor akan nyala, yang artinya sinyal bisa "dikirim" dari satu sirkuit ke sirkuit lainnya – tanpa sambungan fisik alias aman!

### 🌐 Link Referensi
- [Datasheet Optocoupler 4N35](https://www.vishay.com/docs/83725/4n35.pdf)
- [Pengantar tentang Optocoupler - SparkFun](https://learn.sparkfun.com/tutorials/intro-to-optocouplers)
- [Cara Kerja Optocoupler - ElectroSome](https://electrosome.com/working-of-optocoupler/)

---

Semoga bermanfaat dan bisa langsung kamu aplikasikan di proyek IoT kamu! 🚀
