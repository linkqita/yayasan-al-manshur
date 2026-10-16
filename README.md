# Yayasan Al-Manshur Kebotohan

Website resmi Yayasan Al-Manshur Kebotohan. Situs statis dengan CMS berbasis `localStorage` (tanpa server).

## Live
https://linkqita.github.io/yayasan-al-manshur/

## Fitur
- **Profil Yayasan** - visi, misi, identitas, pimpinan, statistik
- **Unit Pendidikan** - 5 lembaga (PAUD KB Insan Rabbani, RA & MI Miftahul Ulum, TPQ Al-Falah, MDT Ula Riyadlotul Uqul Putri)
- **Berita, Program & Kegiatan, Pengumuman, Galeri**
- **Panel Admin (CMS)** - CRUD penuh + upload gambar + edit identitas + ganti sandi + backup/restore JSON

## Panel Admin
Tombol **Panel Admin** di header. Sandi bawaan: `admin123`.

## Struktur
- `index.html` - markup
- `style.css` - tema biru-putih
- `app.js` - data bawaan + render + CMS

## Catatan
Situs statis: data admin tersimpan di `localStorage` browser. Tidak tersinkron antar perangkat. Gerbang login hanya UI, bukan keamanan sungguhan. Backup/restore lewat JSON di tab Pengaturan.
