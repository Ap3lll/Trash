# PilahAI — Asisten Pemilahan Sampah Cerdas ♻️

PilahAI adalah aplikasi web interaktif berbasis AI yang membantu memilah dan mengklasifikasikan sampah secara cerdas menggunakan Google Gemini AI Vision.

## ✨ Fitur Utama
- **AI Vision & Live Object Tracking**: Pelacakan objek kamera secara *real-time* dengan Augmented Reality (AR) bounding box menggunakan TensorFlow.js, COCO-SSD, dan MobileNet.
- **Deteksi Cerdas & Akurat**: Klasifikasi presisi untuk berbagai jenis sampah (Organik, Anorganik, Residu seperti tisu/masker/styrofoam, hingga Limbah B3).
- **Multi-Tier Vision Engine**:
  1. *Edge AI (Offline/Lokal)*: Berjalan otomatis di browser via MobileNet v2 & COCO-SSD tanpa perlu API key.
  2. *Cloud Vision (Opsional)*: Dukungan integrasi Google Gemini Multimodal Vision API untuk pemindaian awan.
  3. *Visual Feature Heuristics*: Analisis luminansi dan tekstur pintar untuk akurasi maksimal.
- **Rekomendasi Penanganan Standar**: Panduan warna tempat sampah, langkah pemilahan, dan tips daur ulang ramah lingkungan.
- **Interface Modern & Responsif**: Dibangun dengan Tailwind CSS dan desain interaktif yang nyaman digunakan di perangkat desktop maupun mobile.

## 🚀 Cara Menjalankan
1. Clone repositori ini:
   ```bash
   git clone https://github.com/Ap3lll/Trash.git
   ```
2. Buka file `index.html` langsung di browser Anda (atau gunakan ekstensi Live Server di VS Code).
3. Anda dapat langsung mengaktifkan kamera untuk memindai objek dengan Live Tracking, atau memasukkan Gemini API Key (opsional) melalui tombol pengaturan di navigasi.

## 🛠️ Teknologi
- HTML5 & CSS3
- Tailwind CSS
- TensorFlow.js (COCO-SSD & MobileNet)
- JavaScript Modern (ES6+)
- Google Gemini Multimodal Vision API (Opsional)


