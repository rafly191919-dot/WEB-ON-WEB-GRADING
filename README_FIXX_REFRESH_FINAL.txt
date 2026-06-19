GRADING TENERA - FIREBASE FIXX REALTIME REFRESH FINAL

Project Firebase:
- projectId: grading-fixx
- authDomain: grading-fixx.firebaseapp.com
- hosting: grading-fixx.web.app / grading-fixx.firebaseapp.com

User login aplikasi:
- Operator: 123456
- Staff: 456789

Database yang dipakai:
- Cloud Firestore, bukan Realtime Database

Collection Firestore:
- gradingTransactions
- teneraDuraTransactions
- suppliers
- drivers
- plates
- settings
- auditLogs

Perbaikan final:
1. Semua config lama grading-tenera-dura dibersihkan.
2. index.html memakai app.js versi cache-busting agar HP tidak membaca JS lama.
3. Tombol Refresh Data ditambahkan tanpa menu baru.
4. Refresh Data mengambil ulang data langsung dari server Firestore dan render ulang tabel.
5. Listener onSnapshot tetap aktif untuk realtime otomatis antar perangkat.
6. Pesan error Firebase lebih jelas untuk membantu cek Auth, Rules, domain, dan koneksi.

Catatan deploy:
- Upload index.html, styles.css, app.js ke Firebase Hosting project grading-fixx.
- Buka dari https://grading-fixx.web.app atau https://grading-fixx.firebaseapp.com.
- Jangan buka dari file://.
- Setelah deploy, buka HP dalam mode incognito/private sekali untuk menghindari cache.
