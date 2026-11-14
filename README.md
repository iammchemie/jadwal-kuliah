# Jadwal Kuliah — Semester 20261

Situs statis satu halaman untuk melihat jadwal kuliah semester 20261 (2026/2027 Ganjil).

- Tanpa build step, tanpa dependency: hanya `index.html`
- Tema terang/gelap (ikut setelan sistem, bisa diganti manual, tersimpan di browser)
- Status langsung: kelas yang sedang berlangsung, kelas berikutnya, dan sisa waktunya
- Responsif untuk HP dan siap dicetak (Ctrl/Cmd + P)

## Data

| Hari | Waktu | Mata kuliah | Ruang | Kelas | Dosen |
| --- | --- | --- | --- | --- | --- |
| Rabu | 07.50–10.20 | 01133 Sistem Informasi Perusahaan (3 SKS, Tatap Muka) | R5307 | IF-6/S1/VII | Anna Dara Andriana, S.Kom., M.Kom |
| Kamis | 11.10–13.40 | 01165 Analisis dan Desain Basis Data (3 SKS, Tatap Muka) | R5307 | IF-7/S1/III | Gentisya Tri Mardiani, S.Kom., M.Kom |
| Kamis | 14.30–17.00 | 01170 Penerapan Teknologi Internet (3 SKS, Praktikum) | LAB-5 | IF-5/S1/V | Donny Reza, M.Kom |

Sumber: SIAKAD kampus.

## Mengubah jadwal

Semua data ada di dalam `index.html`, di bagian `<article class="class" data-day="…" data-from="…" data-to="…">`.
`data-day` memakai penomoran JavaScript: 0 = Minggu, 1 = Senin, … 6 = Sabtu.

## Menjalankan lokal

```bash
python3 -m http.server 8000
# lalu buka http://localhost:8000
```
