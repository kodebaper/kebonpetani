---
title: "🚚 Tracking Produk"
date: 2023-11-12T16:26:19+07:00
draft: false
mermaid: true
---

------
> Seluruh jadwal dan mekanisme Penjualan serta distribusi hasil dari petani lokal yang sedang dalam proses penanganan oleh PetaniBangkit dapat di lihat informasinya melalui halaman ini ya!

-----------------
>**Berikut merupakan Jadwal Distribusi Buah periode kirim Desember 2023**
| Produk      |        Waktu            | Tujuan
| ----------- | -----------             |--------
| Durian      | 25 November             | close
| Durian      | 28 November             | Close
| Durian      | Minggu I Desember       | Depok
| Durian      | Minggu II Desember      | Depok
| Durian      | Minggu 3 Desember       | Jakarta utara
| Salak       | Minggu 2 Desember       | Depok
-----------------
`````
Info pengiriman lain bulan Desember

`````

-----------------
>**Berikut merupakan Jadwal Distribusi Produk lain periode kirim Desember 2023**
| Produk         |        Waktu            | Tujuan
| -----------    | -----------             |--------
| Gula Aren      | Minggu 3 Desember       | Depok
| -              |         -               | -
| -              | -                       |  -
| -              | -                       | -
-----------------

> #### TRACKING DALAM PERJALANAN
>> Tracking pengiriman durian ke depok 28 November 2023
>
>{{< mermaid >}}
    stateDiagram
    [*] --> 📑27_November_Panen
    📑27_November_Panen -->📑27_November_sore_packing
    📑27_November_sore_packing --> 🕐28_November_siang_Pengiriman
    🕐28_November_siang_Pengiriman --> 🚚Paket_dalam_perjalanan
    🚚Paket_dalam_perjalanan --> 🚚29_November_sampai_Depok
    🚚29_November_sampai_Depok
{{< /mermaid >}}


> #### Tracking Pengriman lain
>> {{< mermaid >}}
stateDiagram
    [*] --> 📑Belum_Tersedia    
    📑Belum_Tersedia -->📑Belum_ada_jadwal
    📑Belum_ada_jadwal --> 🕐Tidak_ada_Pengiriman
    🕐Tidak_ada_Pengiriman --> 🚚Belum_tersedia_distribusi
    {{< /mermaid >}}
