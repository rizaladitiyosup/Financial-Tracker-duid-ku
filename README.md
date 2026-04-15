# 💸 duid-ku — PRO Anti Bokek Framework

> Aplikasi tracker keuangan personal untuk anak muda Indonesia yang mau hidupnya *financially controlled*, bukan finansial chaos.

🔗 **Live Demo:** [duid-ku.web.app](https://duid-ku.web.app/)

---

## 📸 Preview

<!-- Ganti dengan screenshot nyata aplikasimu -->
![duid-ku Dashboard](./screenshots/dashboard.png)

---

## ✨ Fitur Utama

### 🆓 FREE
| Fitur | Keterangan |
|---|---|
| 📊 Dashboard Keuangan | Lihat pemasukan, pengeluaran, & sisa bersih bulan ini |
| 📝 Catat Transaksi | Catat uang masuk, keluar, dan tabungan dengan kategori |
| 💰 Budget Limit | Atur batas pengeluaran per kategori agar tidak bocor |
| 🎯 Target Tabungan | Buat tujuan finansial dan pantau progresnya |
| 🔐 Akun Pribadi | Data tersimpan per akun, aman dan privat |

### 🚀 PRO
| Fitur | Keterangan |
|---|---|
| 📈 Grafik Tren | Visualisasi keuangan 6 bulan terakhir |
| 📄 Export PDF | Download rekap keuangan dalam format PDF |
| 📊 Export Excel | Download data transaksi ke spreadsheet |
| 🤖 AI Financial Coach | Analisis keuangan personal berbasis AI |
| 📅 Rekap Bulanan | Laporan perkembangan finansial per bulan |

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript (Vanilla)
- **Auth & Database:** Firebase Authentication + Firestore
- **Hosting:** Firebase Hosting
- **Charts:** Chart.js
- **Export:** jsPDF, SheetJS

---

## 🚀 Cara Deploy Sendiri

### 1. Clone Repository
```bash
git clone https://github.com/username/duid-ku.git
cd duid-ku
```

### 2. Setup Firebase
1. Buat project baru di [Firebase Console](https://console.firebase.google.com/)
2. Aktifkan **Authentication** (Email/Password)
3. Aktifkan **Firestore Database**
4. Copy konfigurasi Firebase ke file config

```javascript
// firebase-config.js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

### 3. Deploy ke Firebase Hosting
```bash
npm install -g firebase-tools
firebase login
firebase init hosting
firebase deploy
```

---

## 📁 Struktur Proyek

```
duid-ku/
├── index.html          # Main app (single page application)
├── firebase-config.js  # Konfigurasi Firebase
├── style.css           # Styling utama
├── app.js              # Logic utama aplikasi
├── screenshots/        # Screenshot untuk README
└── README.md
```

---

## 🔐 Sistem Akses

duid-ku menggunakan sistem **approval manual** untuk mencegah akses tidak sah:

1. User mendaftar akun
2. Akun menunggu persetujuan admin
3. Admin mengaktifkan akses setelah konfirmasi pembayaran (untuk PRO)
4. User bisa login dan menggunakan fitur sesuai tier

---

## 💳 Pricing

| Tier | Harga | Akses |
|---|---|---|
| **FREE** | Gratis | Fitur dasar (dashboard, catat, budget, tabungan) |
| **PRO** | Hubungi admin | Semua fitur termasuk grafik, export, & AI coach |

> Untuk upgrade ke PRO, hubungi admin via Instagram: [@lupacaratiduur](https://www.instagram.com/lupacaratiduur/)

---

## 🤝 Kontribusi

Pull request dan issue sangat diterima! Untuk perubahan besar, buka issue terlebih dahulu untuk diskusi.

1. Fork repository ini
2. Buat branch fitur (`git checkout -b fitur/nama-fitur`)
3. Commit perubahan (`git commit -m 'Tambah fitur X'`)
4. Push ke branch (`git push origin fitur/nama-fitur`)
5. Buka Pull Request

---

## 📄 Lisensi

MIT License — bebas digunakan, dimodifikasi, dan didistribusikan.

---

## 👤 Author

**Rizal** · [@lupacaratiduur](https://www.instagram.com/lupacaratiduur/)

---

<div align="center">
  <p>Dibuat dengan ☕ dan semangat anti bokek 🇮🇩</p>
  <p>⭐ Kalau bermanfaat, kasih bintang ya!</p>
</div>
