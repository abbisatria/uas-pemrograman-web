# UAS Pemrograman Web (Front-End)

## Cloning Project

Clone project yang telah disediakan pada link berikut:

> **Repository:** *(Isi dengan link Git Repository yang diberikan dosen)*

```bash
git clone <repository-url>
```

Setelah proses cloning selesai, buka project menggunakan Visual Studio Code, kemudian jalankan melalui browser menggunakan Live Server atau web server lainnya.

---

# Petunjuk Pengerjaan

1. Kerjakan seluruh soal pada project yang telah diberikan.
2. Tidak diperbolehkan mengubah struktur file maupun nama file yang sudah disediakan, kecuali jika memang diperlukan untuk menyelesaikan soal.
3. Seluruh data harus disimpan menggunakan **LocalStorage**.
4. Tidak diperbolehkan menggunakan framework JavaScript (React, Vue, Angular, dll.).
5. Gunakan JavaScript murni (Vanilla JavaScript).
6. Pastikan seluruh fitur berjalan dengan baik sebelum dikumpulkan.
7. Waktu pengerjaan mengikuti ketentuan yang diberikan oleh dosen/pengawas.

---

# Studi Kasus

Buat dan lengkapi aplikasi **Sistem Antrean Klinik** sesuai dengan ketentuan berikut.

---

# Bagian 1 — HTML Form

## Soal 1

Lengkapi form pendaftaran pasien sehingga memiliki field berikut:

- Nama Pasien
- Jenis Kelamin
- Poli
- Dokter
- Keluhan

### Ketentuan

- Seluruh field wajib diisi.
- Gunakan validasi sebelum data disimpan.

**Nilai: 10**

---

# Bagian 2 — Tambah Pasien

Lengkapi fungsi berikut:

```javascript
function tambahPasien()
```

### Ketentuan

Fungsi harus dapat:

- Membaca seluruh input form
- Melakukan validasi data
- Menyimpan data ke dalam array
- Menyimpan data ke LocalStorage
- Mengosongkan form setelah data berhasil disimpan

**Nilai: 15**

---

# Bagian 3 — Menampilkan Data

Lengkapi fungsi:

```javascript
tampilkanData()
```

### Ketentuan

Seluruh data pasien harus ditampilkan pada tabel.

Kolom **Aksi** harus berubah sesuai status pasien.

### Status Menunggu

Menampilkan tombol:

- Update
- Panggil
- Hapus

### Status Dipanggil

Menampilkan tombol:

- Selesai

### Status Selesai

Tidak menampilkan tombol aksi.

> Setelah fungsi selesai dibuat, hapus seluruh data contoh (sample data) yang terdapat pada elemen `<tbody>`.

**Nilai: 20**

---

# Bagian 4 — Update Data

Lengkapi fitur **Update Pasien**.

### Ketentuan

- Tombol **Update** hanya muncul apabila status pasien masih **Menunggu**.
- Saat tombol Update diklik, data pasien harus kembali tampil pada form sehingga dapat diedit.
- Setelah disimpan, data lama harus diperbarui.

**Nilai: 15**

---

# Bagian 5 — Ubah Status

Lengkapi fungsi:

```javascript
ubahStatus()
```

### Alur Perubahan Status

```
Menunggu
    ↓
Dipanggil
    ↓
Selesai
```

### Ketentuan

- Status harus berubah sesuai urutan di atas.
- Setiap perubahan harus langsung disimpan ke LocalStorage.

**Nilai: 10**

---

# Bagian 6 — Hapus Data

Lengkapi fungsi:

```javascript
hapusPasien()
```

### Ketentuan

- Hanya pasien dengan status **Menunggu** yang dapat dihapus.
- Setelah dihapus, data LocalStorage harus ikut diperbarui.

**Nilai: 10**

---

# Bagian 7 — Dashboard Statistik

Lengkapi fungsi:

```javascript
updateStatistik()
```

### Dashboard harus menampilkan:

- Total Pasien
- Menunggu
- Dipanggil
- Selesai

Setiap perubahan data harus langsung memperbarui statistik.

**Nilai: 10**

---

# Bagian 8 — Reset Form

Tambahkan fungsi reset pada form.

### Ketentuan

Saat tombol **Reset** diklik:

- Seluruh input kembali kosong.
- Data yang sedang diedit dibatalkan.

**Nilai: 5**

---

# Bagian 9 — LocalStorage

Seluruh perubahan data harus tersimpan secara otomatis ke **LocalStorage**.

Saat halaman dibuka kembali:

- Data pasien harus otomatis dimuat kembali.
- Dashboard statistik harus langsung diperbarui.

**Nilai: 5**

---

# Rubrik Penilaian

| No | Materi yang Dinilai | Nilai |
|----|----------------------|------:|
| 1 | Validasi Form | 10 |
| 2 | Tambah Pasien | 15 |
| 3 | Menampilkan Data | 20 |
| 4 | Update Data | 15 |
| 5 | Ubah Status | 10 |
| 6 | Hapus Data | 10 |
| 7 | Dashboard Statistik | 10 |
| 8 | Reset Form | 5 |
| 9 | LocalStorage | 5 |
| | **Total** | **100** |

---

# Ketentuan Pengumpulan

- Push seluruh hasil pengerjaan ke repository GitHub masing-masing.
- Pastikan seluruh source code sudah ter-update sebelum batas waktu pengumpulan.
- Sertakan link repository GitHub pada LMS sesuai instruksi dosen.

---

**Selamat mengerjakan.**
