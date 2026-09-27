# Cara Gabung Scene dalam Google Flow (SceneBuilder): shot list & skrip

Fail utama: `index.html` (buka, tekan **F** untuk skrin penuh, klik **Mula tutorial**, rakam skrin).
Visual: 6 frame rakaman sebenar Google Flow dalam `frames/` (dipotong daripada infografik yang dilampirkan). Tiada UI yang direka.

> **Penting:** fail screen recording penuh tidak sampai dalam sesi ini, jadi timestamp rakaman di bawah ditanda `TBD`.
> Beberapa frame masih ada anotasi merah daripada infografik asal. Kotak merah pada `f1` sebenarnya melingkungi *Add to prompt / Download / Copy*, bukan *Add to scene*.
> Tutorial ini menggunakan spotlight biru untuk menunjuk *Add to scene* yang betul.

## Analisis frame (apa yang benar-benar kelihatan)

| Frame | Isi (daripada rakaman) | Kawalan UI yang digunakan |
|---|---|---|
| f1 | Grid media dengan menu ⋮ terbuka pada satu klip | `Add to scene ›` (menu item ke-3) |
| f2 | "All media": kad baru **Untitled Scene 09-27 02:25:16** + toast **Added to scene** | Pautan `Switch to SceneBuilder` / `Dismiss` |
| f3 | SceneBuilder: dialog *Search assets* (Videos / Uploads, senarai klip) | `+` hujung timeline, `Add media` |
| f4 | SceneBuilder: preview + timeline (00:30) dengan `+` selepas klip | `+` |
| f5 | Timeline lengkap 00:40, kawalan play | Play, ikon Download (lokasi ikut bulatan dalam infografik) |
| f6 | Video akhir dimainkan dalam pemain (00:38) | — |

## Shot list, zoom & anotasi

| # | Durasi | Frame | Rakaman | Tindakan kamera / anotasi | Voice-over |
|---|---|---|---|---|---|
| Intro | ~7s | f4 (blur) | TBD | Tajuk + sub-tajuk atas latar UI kabur | Hai semua! Hari ni kita belajar cara gabung beberapa scene dalam Google Flow, guna SceneBuilder. |
| 1 | ~19s | f1 | TBD | Skrin penuh → cursor ke `Add to scene` → zoom 2.1× → spotlight biru → klik (ripple merah) → callout "Mulakan dengan Scene 1 dahulu" → zoom keluar | Okay, mula-mula kita pilih Scene 1. Buka menu pada klip pertama. / Klik Add to scene. |
| 2 | ~22s | f2 | TBD | Label toast "Added to scene ✓" → kotak biru "SceneBuilder · scene baru" (Untitled Scene) → kotak hijau "Scene 1 Original" → callout besar "Scene 1 original kekal selamat ✓" + jeda 1.8s | Tengok apa yang berlaku lepas Add to scene. / Kenapa kita buat macam ni? Supaya Scene 1 original kita tak terganggu. / Proses gabungan dibuat dalam SceneBuilder, bukan pada klip asal. |
| 3 | ~17s | f2 → f4 | TBD | Cursor ke `Switch to SceneBuilder` → zoom 2.6× → spotlight → klik → potong ke f4, label "Preview" & "Timeline" | Lepas tu baru kita masuk SceneBuilder. / Klik Switch to SceneBuilder. / Di sinilah semua klip akan disusun menjadi satu sequence. |
| 4 | ~35s | f3 → f4 | TBD | Klik `+` (cincin merah) → spotlight dialog → pilih klip → zoom `Add media` → klik → flow "Scene 1 → Scene 2" → klik `+` pada f4 → flow "Scene 1 → 2 → 3 → 4" + callout "Ulang untuk Scene 3, Scene 4…" | Sekarang klik tanda tambah di hujung timeline. / Tetingkap media akan terbuka. Pilih klip Scene 2. / Kemudian klik Add media. / Scene 2 masuk selepas Scene 1. / Ulang langkah sama untuk Scene 3, Scene 4 dan seterusnya. |
| 5 | ~16s | f5 | TBD | Zoom 1.6× ke timeline, garis putus-putus "Semak urutan scene" → zoom ke kawalan preview → klik Play | Dah siap semua? Semak urutan scene pada timeline. / Tekan Play dan preview keseluruhan video dulu sebelum download. |
| 6 | ~17s | f5 → f6 | TBD | Cursor ke ikon Download → zoom 2.4× → cincin merah + callout "Download" → klik → f6, kotak hijau "Video akhir" | Kalau semuanya dah okay, klik ikon Download di bahagian atas. / Semua scene tadi dah jadi satu video yang lengkap. Buka fail tu dan tonton sekali lagi. |
| Akhir | ~14s | — | — | Senarai aliran 6 langkah muncul satu-satu (ADD TO SCENE ditonjolkan) → "Siap! 🎬" | Ringkasnya: Scene 1, Add to scene, masuk SceneBuilder, tambah scene lain, preview, dan download. / Siap! Senang je kan? Selamat mencuba. |

Jumlah: ±2 min 30 s. Setiap butang ikut urutan: skrin penuh → cursor → zoom → highlight → klik → hasil → zoom keluar.

## Warna
Biru `#1d4e9e` / `#2f6fd6` untuk highlight & label; merah `#e0312b` **hanya** untuk lokasi klik; hijau `#1f9d55` untuk "selamat / hasil".

## Kawalan semasa main
`Space` jeda · `←/→` step · `R` ulang · `F` skrin penuh · `H` sembunyi kawalan · `V` voice-over · `C` sari kata.
Voice-over automatik guna suara pelayar (Bahasa Melayu atau Indonesia jika ada). Untuk suara sendiri, matikan dan baca skrip di atas.

## Kalau ada rakaman penuh
Ganti fail dalam `frames/` dengan frame beresolusi penuh (nama sama, nisbah 740×330 atau ubah `FW/FH` dalam `index.html`) dan isi lajur Rakaman dengan timestamp sebenar. Koordinat anotasi berada dalam senarai `scenes` dalam `index.html`.
