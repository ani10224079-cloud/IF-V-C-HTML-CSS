# Jawaban Praktikum: <ANIANGGRAENI> (<10224079>)

## Bagian 1: Pemanasan
1.
2.
3.
4.
5.

## Bagian 3: Prediksi Selector Golf
P1.
P2.
Setelah diuji (hasil sebenarnya):

## Bagian 4: Box model
Q1 (content-box):
Q2 (border-box):
Pengecekan DevTools:

## Bagian 5: Tabel debug
| # | Baris | Bug | Perbaikan | Cara menemukannya |
|---|-------|-----|-----------|-------------------|

## Bagian 6: Tabel Code Review
| # | Baris | Masalah | Mengapa penting | Perbaikan saya |
|---|-------|---------|-----------------|----------------|

Refleksi:
1.
2.
3.

## Bagian 7: Exit ticket
1.
2.
3.
JAWAB A DAN B
Selector .box p akan memilih semua elemen <p> yang berada di dalam elemen ber-class .box, tidak peduli seberapa dalam tingkat pembungkusnya (descendant selector). Paragraf C dan D berada di luar <div class="box">, sehingga tidak ikut berwarna hijau.
3. Paragraf A dan B.
   Penjelasan: Selector `.box p` (descendant selector) memilih semua elemen `<p>` yang berada di dalam elemen dengan class `.box`. Paragraf A dan B berada di dalam `<div class="box">`, sedangkan Paragraf C dan D berada di luar.

4. Warnanya adalah **merah (red)**.
   Penjelasan: Berdasarkan aturan spesifisitas CSS (CSS Specificity), selector ID (`#title`) memiliki hirarki/bobot prioritas paling tinggi dibandingkan selector class (`.heading`) maupun selector elemen/tag (`h1`).

5. Kesalahannya adalah urutan penutupan tag (tag nesting) yang tumpang tindih. Tag `<strong>` dibuka di dalam `<p>`, sehingga harus ditutup sebelum tag `</p>` ditutup.
   Perbaikan: `<p>Hello <strong>world</strong></p>`
   p { color: blue; }, section p { color: green; }, dan .note { color: orange; }
   ## Bagian 4: Box model

Q1 (content-box):
Lebar yang terlihat dari tepi border ke tepi border adalah **334px**.
Perhitungan:
Lebar Total = Width + Padding Kiri + Padding Kanan + Border Kiri + Border Kanan
Lebar Total = 300px + 16px + 16px + 1px + 1px = 334px

Q2 (border-box):
Lebar total yang terlihat dari tepi border ke tepi border berubah menjadi tepat **300px**. Padding (16px) dan border (1px) dimasukkan ke dalam perhitungan `width`, sehingga elemen tidak membengkak melebihi 300px.

Pengecekan DevTools:
- content: 894px × (tinggi konten)
- padding: 16px (top, right, bottom, left)
- border: 1px (top, right, bottom, left)
- margin: 0px top/right, 24px bottom, 0px left