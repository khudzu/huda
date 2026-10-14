# Panduan Lengkap Matematika Bisnis Modul 1–14

- [PDF final (38 halaman)](Panduan_Matematika_Bisnis_Modul_1-14.pdf)
- [Sumber LaTeX yang dapat diedit](Panduan_Matematika_Bisnis_Modul_1-14.tex)

Untuk mengunduh, buka berkas lalu pilih **Download raw file** di GitHub.

## Kompilasi

Gunakan XeLaTeX dengan font Latin Modern dan paket LaTeX standar yang disebutkan dalam sumber. Di Overleaf, unggah berkas `.tex`, tetapkan sebagai dokumen utama, lalu pilih compiler **XeLaTeX**.

Untuk kompilasi lokal, jalankan dua kali dari direktori ini:

```sh
xelatex -interaction=nonstopmode -halt-on-error Panduan_Matematika_Bisnis_Modul_1-14.tex
xelatex -interaction=nonstopmode -halt-on-error Panduan_Matematika_Bisnis_Modul_1-14.tex
```

Dokumen mencakup seluruh 14 modul, tabel ringkasan konsep, pengelompokan cabang matematika, penurunan rumus, contoh, latihan, dan glosarium. PDF telah diperiksa secara visual pada setiap halaman; 36 pemeriksaan numerik lulus.
