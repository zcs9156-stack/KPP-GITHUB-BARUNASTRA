# Materi GitHub

## 1. Pengertian Git dan GitHub

**Git** adalah sistem version control yang digunakan untuk melacak perubahan file dalam proyek. Dengan Git, kita dapat melihat riwayat perubahan, membuat branch, dan mengembalikan file ke versi sebelumnya.

**GitHub** adalah platform berbasis internet untuk menyimpan repository Git, berkolaborasi dengan orang lain, dan mengelola proyek perangkat lunak.

Perbedaan utama:
- Git bekerja untuk mencatat dan mengelola perubahan versi.
- GitHub menyediakan tempat untuk menyimpan repository secara daring dan berkolaborasi.

## 2. Istilah Penting

- **Repository:** tempat menyimpan file proyek beserta riwayat perubahannya.
- **Commit:** rekaman perubahan yang disimpan dalam riwayat Git.
- **Branch:** jalur pengembangan terpisah dari branch lain.
- **Merge:** menggabungkan perubahan dari satu branch ke branch lain.
- **Remote:** repository yang berada di lokasi lain, misalnya di GitHub.
- **Clone:** menyalin repository remote ke komputer lokal.
- **Push:** mengirim commit lokal ke repository remote.
- **Pull:** mengambil dan mengintegrasikan perubahan dari remote.
- **Fetch:** mengambil informasi terbaru dari remote tanpa langsung menggabungkannya.
- **Staging area:** tempat menyiapkan perubahan sebelum dibuat menjadi commit.

## 3. Alur Kerja Dasar Git

Alur kerja yang umum digunakan:

1. Mengubah atau menambahkan file.
2. Memeriksa perubahan dengan `git status`.
3. Menyiapkan file dengan `git add`.
4. Menyimpan perubahan dengan `git commit`.
5. Mengirim commit ke GitHub dengan `git push`.

## 4. Perintah Dasar

| Perintah | Fungsi |
|---|---|
| `git init` | Membuat repository Git lokal |
| `git clone URL` | Menyalin repository remote |
| `git status` | Memeriksa kondisi repository |
| `git add nama-file` | Menyiapkan file untuk commit |
| `git add .` | Menyiapkan perubahan dalam direktori saat ini |
| `git commit -m "pesan"` | Menyimpan commit dengan pesan |
| `git log --oneline` | Melihat ringkasan riwayat commit |
| `git branch` | Melihat branch lokal |
| `git switch nama-branch` | Berpindah branch |
| `git switch -c nama-branch` | Membuat dan berpindah ke branch baru |
| `git fetch origin` | Mengambil informasi terbaru dari remote |
| `git pull` | Mengambil dan mengintegrasikan perubahan remote |
| `git push -u origin nama-branch` | Mengirim branch ke remote sekaligus mengatur upstream |

## 5. Mengapa Menggunakan Branch?

Branch memungkinkan kita mengembangkan fitur atau dokumentasi secara terpisah tanpa langsung mengubah `main`.

Contoh pembagian branch:
- `docs/materi-github`: materi dasar GitHub.
- `docs/sejarah-github`: sejarah dan perkembangan GitHub.
- `docs/markdown`: panduan penulisan Markdown.
- `docs/penggunaan-github`: praktik penggunaan GitHub sehari-hari.

Setelah perubahan selesai dan diperiksa, branch dapat digabungkan ke `main` menggunakan merge.

## 6. Praktik yang Baik

1. Gunakan nama branch yang menggambarkan tujuannya.
2. Buat commit kecil dengan pesan yang jelas.
3. Periksa `git status` sebelum commit.
4. Jangan memasukkan password, token, atau secret ke repository.
5. Ambil perubahan terbaru sebelum mulai bekerja jika repository digunakan bersama.
6. Periksa hasil merge untuk memastikan tidak ada konflik atau file yang hilang.

## 7. Kesimpulan

Git membantu melacak perubahan proyek, sedangkan GitHub membantu menyimpan dan mengembangkan repository secara daring. Pemahaman tentang repository, staging, commit, branch, merge, dan remote merupakan dasar penting untuk bekerja secara terstruktur dalam sebuah proyek.