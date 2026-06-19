GRADING TENERA - FIREBASE FIXX REALTIME V2

Perbaikan fokus realtime:
1. Firebase config memakai project grading-fixx.
2. Auth Anonymous wajib aktif.
3. Cloud Firestore wajib aktif, bukan Realtime Database.
4. HTML memakai cache-busting agar HP tidak membuka app.js lama setelah deploy.
5. Pesan gagal Firebase dibuat spesifik: unauthorized-domain, rules, anonymous auth, firestore belum aktif, network, dan API key.
6. Simpan/edit/hapus tetap diarahkan ke Cloud Firestore.

Deploy ke Firebase Hosting project grading-fixx, lalu buka link yang sama di semua HP.
Jika masih gagal, baca pesan lengkap yang muncul di login dan cocokkan dengan checklist.
