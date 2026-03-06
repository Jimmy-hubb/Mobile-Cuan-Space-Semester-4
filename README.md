# 📱 Cuan Space Mobile – Platform UMKM Digital

**Cuan Space Mobile** merupakan aplikasi **mobile berbasis Flutter** yang dikembangkan untuk membantu pelaku **UMKM menjual produk secara online dengan lebih mudah** melalui perangkat smartphone.

Aplikasi ini memungkinkan pengguna untuk **melihat produk UMKM, melakukan komunikasi langsung dengan penjual melalui fitur chat, serta mengakses platform penjualan UMKM secara digital**.

Selain itu, pengguna yang ingin menjadi penjual dapat melakukan **login sebagai seller**, dan untuk pendaftaran UMKM akan diarahkan langsung ke **platform web Cuan Space**.

Project ini dikembangkan sebagai bagian dari **portfolio mobile developer** serta pembelajaran dalam membangun aplikasi mobile menggunakan **Flutter Framework**.

---

# 🚀 Features

Beberapa fitur utama dalam aplikasi **Cuan Space Mobile** antara lain:

### 🛍️ Katalog Produk UMKM
Menampilkan berbagai produk dari pelaku UMKM yang tersedia pada platform.

### 💬 Chat Penjual & Pembeli
Pengguna dapat melakukan **chat langsung dengan penjual** untuk menanyakan detail produk atau melakukan negosiasi.

### 🔐 Login Seller
Pelaku UMKM dapat login sebagai **seller** untuk mengakses sistem penjualan.

### 🏪 Daftar UMKM
Pengguna yang ingin mendaftarkan usaha akan diarahkan ke **platform web Cuan Space** untuk melakukan registrasi UMKM.

### 📦 Informasi Produk
Menampilkan detail informasi produk seperti:

- Nama produk
- Harga produk
- Deskripsi produk
- Gambar produk
- Informasi penjual

### 📱 User Friendly Interface
Aplikasi dirancang dengan tampilan sederhana agar mudah digunakan oleh pengguna.

### 🌐 Integrasi Web Platform
Beberapa fitur seperti **pendaftaran UMKM** akan diarahkan langsung ke **website Cuan Space**.

---

# 🛠 Tech Stack

Teknologi yang digunakan dalam pengembangan aplikasi ini:

| Technology | Description |
|-----------|-------------|
| Flutter | Framework untuk pengembangan aplikasi mobile |
| Dart | Bahasa pemrograman utama Flutter |
| HTTP / API | Komunikasi antara aplikasi dan backend |
| Firebase (Optional) | Backend service untuk chat / autentikasi |
| WebView | Untuk mengakses halaman web pendaftaran UMKM |

---

# 📂 Project Structure

Struktur folder utama pada project Flutter:

```
cuan-space-mobile
│
├── android
├── ios
├── linux
├── macos
├── windows
├── web
│
├── lib
│   ├── screens
│   ├── widgets
│   ├── models
│   └── main.dart
│
├── assets
│   ├── images
│   └── icons
│
├── fonts
├── test
│
├── pubspec.yaml
├── pubspec.lock
├── analysis_options.yaml
└── README.md
```

---

# ⚙️ Installation

Ikuti langkah berikut untuk menjalankan project secara lokal.

### 1. Clone Repository

```bash
git clone https://github.com/username/cuan-space-mobile.git
```

### 2. Masuk ke Folder Project

```bash
cd cuan-space-mobile
```

### 3. Install Dependency Flutter

```bash
flutter pub get
```

---

### 4. Jalankan Aplikasi

Hubungkan perangkat Android atau gunakan emulator.

```
flutter run
```

---

### 5. Build APK (Optional)

Untuk membuat file APK:

```
flutter build apk
```

---

# 📦 Dependencies

Beberapa dependency yang digunakan dalam project Flutter ini:

```
http
provider
firebase_auth
cloud_firestore
flutter_chat_ui
webview_flutter
```

Dependency dapat dilihat pada file:

```
pubspec.yaml
```

---

# 📸 Application Preview

Tambahkan screenshot aplikasi pada folder `assets/images`.

```
![Home Screen](assets/images/home.png)
![Product Page](assets/images/product.png)
![Chat Feature](assets/images/chat.png)
```

---

# 🎯 Project Goals

Tujuan utama dari pengembangan aplikasi ini:

- Membantu pelaku UMKM menjual produk secara digital
- Mempermudah komunikasi antara penjual dan pembeli
- Menghubungkan aplikasi mobile dengan platform web UMKM
- Mengembangkan keterampilan dalam pengembangan aplikasi menggunakan Flutter
