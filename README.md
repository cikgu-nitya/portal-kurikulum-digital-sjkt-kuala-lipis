# Portal Pengurusan Kurikulum Digital SJKT Kuala Lipis

Ini ialah versi GitHub Pages + Firebase Ready untuk Portal Pengurusan Kurikulum Digital.

## Fail utama

- `index.html` — fail portal utama. GitHub Pages akan baca fail ini sebagai laman utama.
- `firestore.rules` — rules Firestore untuk kawalan keselamatan Firebase.
- `.nojekyll` — fail kosong untuk memastikan GitHub Pages paparkan fail statik tanpa proses Jekyll.

## Cara guna ringkas

1. Buka `index.html`.
2. Cari bahagian `firebaseConfig`.
3. Tampal konfigurasi Firebase sebenar daripada Firebase Console.
4. Upload semua fail dalam folder ini ke GitHub repository.
5. Aktifkan GitHub Pages melalui Settings → Pages → Deploy from a branch → main → /root.
6. Buka link GitHub Pages yang diberi oleh GitHub.

## Nota penting

GitHub Pages hanya host portal. Data sebenar portal disimpan di Firebase Firestore.
Jangan simpan kata laluan admin dalam fail HTML.
Kawalan siapa boleh edit dibuat melalui Firebase Authentication dan Firestore Rules.
