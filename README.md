# 3ch4tapp-pb
# Chat Publik Firebase

Aplikasi chat publik menggunakan **Firebase Realtime Database**.  
Dibuat untuk belajar dan berbagi, semua orang dapat mengirim dan menghapus pesan tanpa login.

---

## 🚀 Fitur
- Wajib isi nama sebelum chat
- Kirim pesan maksimal **200 karakter**
- Pesan lama otomatis dihapus jika jumlah pesan > 20
- Hapus pesan satuan (long press) atau hapus semua (tombol)
- Nada dering custom + pengaturan volume
- **Anti-spam** (minimal jeda 5 detik antar pesan)

---

## 🔐 Tentang Firebase API Key

Project ini menggunakan **Firebase Web API key** yang **terlihat di kode**.  
Firebase API key **bukan rahasia** untuk aplikasi web dan memang harus dibagikan agar browser bisa menghubungkan aplikasi ke Firebase.

📌 **Catatan Penting:**
- API key ini **tidak bisa** digunakan untuk mengakses akun Firebase atau Google saya.
- Keamanan database diatur lewat **Firebase Security Rules**, bukan dengan merahasiakan API key.
- Untuk project ini, aturan database **sengaja dibuat publik** (`.read: true`, `.write: true`) agar semua orang bisa ikut chat.
- API key ini berbeda dengan API key layanan lain seperti Google Maps, Stripe, atau OpenAI yang sifatnya rahasia.

🔗 Referensi resmi Firebase:  
[Firebase: API keys are safe to expose](https://firebase.google.com/docs/projects/api-keys)

---

## ⚠️ Peringatan
Karena chat ini **publik**, semua orang bisa:
- Membaca semua pesan
- Mengirim pesan baru
- Menghapus pesan yang ada

Gunakan hanya untuk tujuan belajar atau komunitas yang terkontrol.

---

## 📄 Lisensi
Bebas digunakan dan dimodifikasi untuk pembelajaran.
