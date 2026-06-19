Sistem Grading TBS dan Tenera Dura - Firebase Fixx Realtime Checked

Project Firebase:
- projectId: grading-fixx
- authDomain: grading-fixx.firebaseapp.com

Login aplikasi:
- Operator: 123456
- Staff: 456789

Catatan penting:
1. Deploy folder ini ke Firebase Hosting atau jalankan melalui localhost.
2. Jangan dibuka langsung via file:// untuk pemakaian realtime antar HP.
3. Authentication > Sign-in method > Anonymous harus Enabled.
4. Firestore Rules gunakan isi FIREBASE_RULES.txt lalu Publish.
5. Database yang dipakai adalah Cloud Firestore, bukan Realtime Database.
6. Collection yang otomatis dipakai/dibuat: gradingTransactions, teneraDuraTransactions, suppliers, drivers, settings, auditLogs.

Cara cek realtime:
- Buka link hosting yang sama di dua HP.
- Login di kedua HP.
- Input data di HP pertama.
- Di HP kedua buka Data Transaksi tanpa refresh. Data harus muncul otomatis.
