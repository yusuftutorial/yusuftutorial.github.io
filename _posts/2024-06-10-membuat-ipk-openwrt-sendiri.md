---
title: Membuat Ipk OpenWRT Sendiri
author: Wikipedia Master
date: 2024-06-10
category: Openwrt
layout: post
mermaid: true
---

Ada dua cara utama untuk membuat ipk OpenWRT sendiri:

## 1. Menggunakan OpenWRT SDK

Cara ini lebih kompleks, tetapi memungkinkan Anda untuk membuat `ipk` dari kode sumber `GitHub`. Berikut langkah-langkahnya:

- Instal `OpenWRT SDK`.
- `Clone repositori GitHub` dari paket yang ingin Anda buat `ipk`.
- Buat file `Makefile` yang sesuai.
- Build ipk dengan perintah `make`.

## 2. Menggunakan OpenWRT Image Builder

Cara ini lebih mudah, tetapi tidak memungkinkan Anda untuk membuat ipk dari kode sumber GitHub. Berikut langkah-langkahnya:

- Download `OpenWRT Image Builder`.
- `Extract` file Image Builder.
- Masukkan file `ipk kustom` ke folder `packages`.
- Build image `OpenWRT` dengan perintah `make`.

Sumber Daya Tambahan:

- [Cara Install File Ipk Openwrt](https://radenku.com/custom-openwrt-23-05-build-by-radenku-com/)
- [OpenWRT Image Builder](https://downloads.openwrt.org/)
- [OpenWRT SDK](https://openwrt.org/docs/guide-developer/toolchain/using_the_sdk)

Sebelum memulai, pastikan Anda memahami `arsitektur CPU router` Anda dan pilih `image builder` yang sesuai.

Apakah Anda ingin mempelajari lebih detail tentang cara membuat ipk OpenWRT dengan metode tertentu?
