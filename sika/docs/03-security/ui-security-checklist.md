# UI Security Checklist — SIKA Bab 2

| No | Pertanyaan | Status |
|----|-----------|--------|
| 1 | Data yang ditampilkan memang diperlukan? | ✅ |
| 2 | Menggunakan data dummy, bukan data nyata? | ✅ |
| 3 | Tidak ada credential/API key/token? | ✅ |
| 4 | Data sensitif tidak diletakkan di URL? | ✅ |
| 5 | Hidden input dipahami dapat dilihat via DevTools? | ✅ |
| 6 | HTML5 validation = usability, bukan security? | ✅ |

**Dua potensi paparan yang dicegah:**
1. Tidak ada komentar HTML berisi info sensitif.
2. Tidak menggunakan hidden input untuk rahasia.