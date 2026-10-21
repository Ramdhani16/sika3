# Form Field Specification — SIKA Bab 2

| Field    | Tujuan                   | Type   | Wajib | Batas        |
|----------|--------------------------|--------|-------|--------------|
| nim      | Identitas unik mahasiswa | text   | Ya    | min=8, max=15 |
| nama     | Nama lengkap             | text   | Ya    | min=3        |
| email    | Kontak surel             | email  | Ya    | —            |
| prodi    | Program studi            | select | Ya    | —            |
| angkatan | Tahun masuk              | number | Ya    | 2020–2030    |
| status   | Status akademik          | radio  | Ya    | —            |