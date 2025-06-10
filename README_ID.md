<p align="center">
  <a href="README.md">🇬🇧 English</a> | <a href="README_ID.md">🇮🇩 Indonesia</a>
</p>

<p align="center">
  <img src="assets/bypass-angle-vulkan-preview.png" alt="Bypass ANGLE Vulkan Preview" style="border-radius: 8px;">
</p>

<h1 align="center">Bypass ANGLE Vulkan</h1>
<p align="center"><b>Buka Kunci Rendering GPU ANGLE + Vulkan Penuh di Android — Tanpa Root, Aman, dan Sangat Cepat</b></p>

<p align="center">
  <img alt="Topic: angle" src="https://img.shields.io/badge/topic-angle-blue?style=flat-square">
  <img alt="Topic: vulkan" src="https://img.shields.io/badge/topic-vulkan-red?style=flat-square">
  <img alt="Topic: gpu-acceleration" src="https://img.shields.io/badge/topic-GPU--acceleration-green?style=flat-square">
  <img alt="Topic: android" src="https://img.shields.io/badge/topic-android-yellow?style=flat-square">
  <img alt="Topic: setprop" src="https://img.shields.io/badge/topic-setprop-lightgrey?style=flat-square">
  <img alt="Topic: script" src="https://img.shields.io/badge/topic-script-blue?style=flat-square">
  <img alt="Topic: realme" src="https://img.shields.io/badge/topic-realme-orange?style=flat-square">
  <img alt="Topic: unisoc" src="https://img.shields.io/badge/topic-unisoc-red?style=flat-square">
  <img alt="Topic: webview-android" src="https://img.shields.io/badge/topic-webview--android-blueviolet?style=flat-square">
  <img alt="Topic: chrome" src="https://img.shields.io/badge/topic-chrome-silver?style=flat-square"><br>
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/rhaditbhule92/bypass-angle-vulkan?style=flat-square">
  <img alt="GitHub forks" src="https://img.shields.io/github/forks/rhaditbhule92/bypass-angle-vulkan?style=flat-square">
  <img alt="GitHub license" src="https://img.shields.io/github/license/rhaditbhule92/bypass-angle-vulkan?style=flat-square">
</p>

---

## Apa ini?

> **Bypass ANGLE Vulkan** adalah modifikasi sistem yang direkayasa sepenuhnya menggunakan `setprop` untuk membuka **rendering backend Vulkan** pada perangkat Android kelas bawah dengan batasan ANGLE — **tanpa root, unlock bootloader, atau alat PC**.

Dirancang untuk melepaskan akselerasi GPU penuh menggunakan pendekatan asli yang bersih melalui **shell EngineerMode**, dengan aman melewati batasan Android Go.

---

## Perangkat yang Diuji

- **Realme C33**
  - Unisoc Tiger T612 (8-core)
  - GPU Mali-G57
  - RAM 2GB + 2GB Extended
  - Android 13 Go Edition
  - *Tanpa root / bootloader tetap terkunci / tanpa ADB*

Dikonfirmasi berfungsi dengan:
- **Chrome Dev** — Backend ANGLE Vulkan
- **Android System WebView** — Jalur Vulkan aktif
- **System UI & HWUI** — Rendering yang dipercepat GPU

---

Rilis ini mencakup semua yang kamu butuhkan untuk mengaktifkan rendering berbasis GPU sepenuhnya menggunakan **ANGLE Vulkan** di perangkat Android low-end — tanpa perlu akses root.

## Fitur Utama:

- Mengaktifkan sistem rendering ANGLE Vulkan secara menyeluruh.
- Membuka kemampuan rendering GPU bahkan pada perangkat low-end berbasis Android Go.
- Menonaktifkan thermal throttling dan watchdog untuk performa yang konsisten.
- Chrome Dev dan WebView telah dioptimalkan untuk rendering Vulkan.
- Tweak audio bawaan untuk menyinkronkan Equalizer PoweRamp tanpa perlu izin DUMP.
- **100% Tanpa Root** — Hanya menggunakan ADB Shell lewat EngineerMode.

## Apa Saja yang Disertakan:

- `Angle_Vulkan_Config_Setprop.txt`: Skrip setprop lengkap untuk menyuntikkan properti sistem yang telah dioptimalkan melalui ADB shell EngineerMode.
- `script.sh`: Skrip ADB shell siap pakai dengan 20 tahapan konfigurasi yang tersinkronisasi.
- `README.html` / `index.html`: Pratinjau bertema gelap kompatibel dengan GitHub Pages, lengkap dengan tautan langsung dan tombol navigasi.
- `Screenshot_Angle_Vulkan.png`: Bukti nyata bahwa ANGLE Vulkan aktif tanpa rendering berbasis software sama sekali.
- `Player.html`: Pemutar audio sederhana yang tertanam untuk memutar koleksi musik dalam format **HI-Res MP3 320Kbps** di lengkapi Equalizer yang disertakan dalam rilis ini.

- `PoweRamp.apk`: Versi Lengkap
- `PoweRamp Equalizer.apk`: Premium
- Konfigurasi Equalizer PoweRamp:
  - `PoweRamp+PresetEqualizer-Settings`
  - `PoweRampEqualizer+PresetEqualizer-Settings`

**300+ Channel Radio Online Nasional + Internasional**  
- Preset Radio Online:
  - `List of My Favorite Online Radio Stations.m3u8`
  
### BONUS KOLEKSI MUSIK (MP3)

**Rilisan ini juga menyertakan koleksi musik pribadi saya dalam format MP3 320kbps berkualitas tinggi:**

- `80s Rock Ballads`
Hits legendaris dari Air Supply, Alex Porat, Alter Bridge, Audioslave, Bad English, Bon Jovi, Bonnie tyler, Bryan Adams, Creed, Creep, Deep Purple, Dokken, Dream Theater, Eric Clapton, Europe, Evanescence, Extreme, Firehouse, Foreigner, Gary Moore, Guns N' Roses, Heart, Heaven, Helloween, Kansas, McAuley Schenker Group, Metallica, Michael Buble, Mr. Big, Muse, Nazareth, Nirvana, Poisen, REO Speedwagon, Richard Marx, Rockwell, Scorpions, Seether, Skid Row, Steelheart, The Eagles, The Goo Goo Dolls, The Offspring, The Police, The Rolling Stones, White Lion, Whitesnake.

- `Rock Klasik Malaysia`
Balada rock Melayu abadi dan hits akustik dari Amy Search, Arrow, Asahan, AXL'S, Bumi Putra Rockers, Damasutra, Data, Rahmat Ekamantra, Ella, Exists, EYE, Ezad Lazim, Iklim (Saleem), Lestari, Mega, Pearl, Scan, Screen, Slam, Spoon, Spring, Stings, Succes, Thomas Arya, U.K's, Wings.

---

## Screenshot, Panduan, dan Video Demo:

> Kunjungi GitHub Pages:  
> **[Lihat Panduan Lengkap (Dark Mode) – Tersedia dalam Dua Bahasa](https://sfl.gl/UAZeN6)**

---

<p align="center">
  <strong>Punya pertanyaan atau saran?</strong><br>
  Jangan ragu untuk membuka issue di
  <a href="https://github.com/Rhaditbhule92/Bypass-ANGLE-Vulkan/issues">
    GitHub Issues
  </a>
  — tidak ada pertanyaan yang bodoh, dan saya dengan senang hati akan membantu!
</p>

---

[Tentang Proyek Ini](https://rhaditbhule92.github.io/Bypass-ANGLE-Vulkan/about.html).

---

[MIT License](https://github.com/Rhaditbhule92/Bypass-ANGLE-Vulkan/blob/main/LICENSEE).  

---

[FAQ](https://rhaditbhule92.github.io/Bypass-ANGLE-Vulkan/faq.html)

---