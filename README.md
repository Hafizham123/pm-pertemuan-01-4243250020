# hello_unimed

A new Flutter project.

## identitas
Nama   : Hafizham Mufti Siregar

Nim    : 4243250020

Kelas  : PSIK 24D

## Keluaran Flutter --version
Flutter 3.47.7 • channel stable • https://github.com/flutter/flutter.git
Framework • revision abaf9c5237 (2 weeks ago) • 2026-10-08 09:51:21 -0700
Engine • hash d8a2d6c768c334d53e16277f837970ffa1e2de81 (revision deb287481e) (15 days ago) •
2026-10-07 17:09:12.000Z
Tools • Dart 3.13.5 • DevTools 2.60.0

## Tangkapan Layar flutter doctor & Aplikasi

### flutter doctor
<img width="703" height="465" alt="SS_Flutter version dan doctor" src="https://github.com/user-attachments/assets/e0af9508-1482-4623-a01d-a07c76f91b4e" />

### Aplikasi
<img width="720" height="1612" alt="SS_Aplikasi" src="https://github.com/user-attachments/assets/5e957387-5e32-4fe1-bb6b-b8d7f12ada3c" />

## 2 Kendala + Solusi
1. Awalnya saat run start debugging, loading Gradel selalu error atau FAILED/BUILD FAILED.
Solusi : ditemukan ndk yg digunakan program adalah versi 28.2 dan yg saya unduh awalnya versi terbaru 32, jadi harus ganti ndk di android studio.
2. Mengetik r, R, h dan q di terminal tidak memicu fungsi hot reload, hot restart, help dan quite.
Solusi : pada vs code terdapat tab atau icon (petir, reload, dll) di bagian atas jendela windows yang memiliki fungsi yang sama dengan r, R dan q. h tidak dibutuhkan lagi karena semua aksi atau perintah sudah muncul dalam bentuk icon atau tab.

## Pernyataan Penggunaan AI
AI Gemini digunakan dalam membantu untuk menyiapkan environment seperti pada instalasi git dan setting installasi android studio serta sdk platform dan sdk tools agar lebih ringan karena saya berencana menggunakan HP langsung sebagai tempat menjalan program, bukan virtual device atau emulator sebab kurangnya RAM laptop. AI Gemin juga digunakan dalam analisis error terutama saat loading Gradel yang awal nya sering error sebab versi ndk yg digunakan berbeda dengan yang dibutuhkan program. Gemini juga digunakan dalam mempelajari apa itu widget serta contohnya. Membantu Mencari Contoh kasus setiap pendekatan (Native, Hybird, dan Cross-Platform) serta memeriksa jumlah kata esai.

## Esai (179 Kata)
Pendekatan Native memiliki keunggulan dalam kinerja dibanding pendekatan lainnya. Sebab pendekatan ini hanya fokus pada satu platfrom tertentu saja. pengembangannya menggunakan bahasa pemrograman Khusus untuk Aplikasi Mobile seperti Kotlin(Android) atau Swift(iOS). Karena ini pendekatan ini menghasilkan performa tertinggi, sangat responsif dan memiliki akses penuh ke perangkat keras internal. Contoh: contohnya adalah Game berat dan online yang membutuhkan kinerja tinggi.

Pendekatan Hybrid memiliki keunggulan dalam kecepatan pembuatan dan hemat biaya. Ini dikarenakan pada pendekatan ini, pada dasarnya hanya membuat laman web lalu dibungkus kedalam aplikasi mobile sehingga bisa digunakan oleh platform mana pun. namun kekurangannya berupa performanya cenderung lambat dan akses terbatas ke perangkat keras internal terbaru. Contoh: Aplikasi Katalog Toko Online Skala kecil, versi awal Instagram atau Amazon Shop.

Sedangkan Pendekatan Cross-Platform memiliki keunggulan performa mendekati Native sambil bisa digunakan di Platform mana pun tanpa harus membuat program terpisah untuk setiap Platform atau hanya perlu membuat satu kode/program tunggal saja menggunakan Seperti Hybird. Kode/Program tunggal tersebut yang dibuat menggunakan Flutter atau React Native nantinya dikompilasi menjadi Komponen Native. Contoh: Tokopedia (Menggunakan React Native) dan J&T Express Indonesia (Menggunakan Flutter).

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Learn Flutter](https://docs.flutter.dev/get-started/learn-flutter)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Flutter learning resources](https://docs.flutter.dev/reference/learning-resources)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
