Panduan Menggunakan Markdown

1. Pengertian Markdown

Markdown adalah bahasa markup ringan untuk memformat teks menggunakan simbol sederhana. Markdown sering digunakan untuk membuat README, dokumentasi proyek, catatan, dan deskripsi Pull Request di GitHub.

2. Heading atau Judul

Gunakan tanda # untuk membuat judul. Semakin banyak tanda #, semakin rendah tingkat heading-nya.

# Judul Utama
## Subjudul
### Subjudul Tingkat 3

3. Format Teks

**Teks tebal**
*Teks miring*
~~Teks dicoret~~
`Kode singkat`

Hasilnya:

Teks tebal

Teks miring

Teks dicoret

Kode singkat

4. Membuat Daftar

Daftar tidak berurutan:

- Git
- GitHub
- Markdown

Daftar berurutan:

1. Buat perubahan.
2. Jalankan git add.
3. Buat commit.

5. Membuat Link dan Gambar

Link:

[Dokumentasi GitHub](https://docs.github.com/)

Gambar:

![Deskripsi gambar](images/contoh.png)

Pastikan lokasi gambar benar dan file gambarnya memang tersedia di repository.

6. Membuat Blockquote

Gunakan tanda > untuk menampilkan kutipan.

> Dokumentasi yang baik membantu orang memahami proyek.

7. Menampilkan Kode

Gunakan tiga backtick sebelum dan sesudah blok kode. Nama bahasa dapat ditambahkan untuk syntax highlighting.

```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "Hello, GitHub!";
    return 0;
}
```

8. Membuat Tabel

| Perintah | Fungsi |
|---|---|
| git status | Memeriksa kondisi repository |
| git add . | Menyiapkan perubahan |
| git commit | Menyimpan perubahan |

9. Membuat Checklist

- [x] Membuat repository
- [x] Membuat README
- [ ] Menyelesaikan dokumentasi

10. Tips Dokumentasi di GitHub

Gunakan heading secara berurutan agar struktur mudah dipahami.

Pisahkan bagian berdasarkan topik.

Gunakan blok kode untuk contoh perintah.

Pastikan link dan gambar tidak rusak.

Periksa tampilan Markdown melalui preview di VS Code atau halaman repository GitHub.

Kesimpulan

Markdown membantu kita menyusun dokumentasi yang rapi, mudah dibaca, dan konsisten. Menguasai Markdown merupakan keterampilan dasar yang berguna ketika mengelola proyek di GitHub.