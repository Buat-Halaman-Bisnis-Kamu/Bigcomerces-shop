# Berkontribusi 

Hai yang disana! Kami senang Anda memiliki ide untuk meningkatkan topik dan koleksi. 
Anda membantu komunitas menemukan informasi berharga. Proyek ini mematuhi 
[Kode Etik Perjanjian Utama](CODE_OF_CONDUCT.md). 
Dengan berpartisipasi, Anda diharapkan untuk menjunjung tinggi kode ini. 
Ada beberapa cara Anda dapat berkontribusi: 
- Meningkatkan topik atau koleksi yang ada 
- Mengurasi topik atau koleksi baru Saat Anda menulis konten, periksa 

[Panduan Gaya](./docs/styleguide.md)

 untuk mempelajari apa artinya setiap bidang, dan bagaimana mereka harus diformat. 
Mengikuti panduan gaya akan meningkatkan peluang kontribusi Anda diterima. 

Catatan: Pembaruan tidak akan segera muncul setelah kami menggabungkan PR Anda. 
Kami melakukan perubahan ini secara teratur ke GitHub. 

## Meningkatkan topik atau koleksi yang ada Jika topik atau koleksi sudah ada, itu akan terdaftar di direktori masing-masing: 

- [topik/](https://github.com/github/explore/tree/master/topics) 
- [koleksi/](https://github.com/github/explore/tree/master/collections)

Topik atau nama koleksi harus cocok dengan URL-nya, 

mis.`https://github.com/topik/rails` 
sesuai dengan [`topik/rails`direktori](https://github.com/github/explore/tree/master/topics/rails). 
Untuk melakukan peningkatan, harap 

**buka permintaan tarik** 

dengan perubahan yang Anda usulkan: 

### Perbarui gambar Untuk memperbarui gambar, cukup ganti gambar di dalam direktori untuk topik atau koleksi. 

### Perbarui teks dan tautan Untuk memperbarui teks dan tautan,edit`index.md`di dalam topik atau direktori koleksi. 

File-file ini diformat menggunakan kombinasi

[Front Matter](https://jekyllrb.com/docs/frontmatter/) 
dan konten tubuh yang sederhana. Untuk **topik**, Anda akan melihat bahwa, dalam contoh-contoh seperti topik "

[algoritma](https://raw.githubusercontent.com/github/explore/master/topics/algorithm/index.md)," 

data seperti URL kanoniknya, URL Wikipedia, atau nama tampilan dipanggil dalam pasangan nilai kunci; sementara deskripsi terperincinya diperhitungkan dalam badan dokumen.

_/topics/algorithm/index.md_:
```
---
aliases: algorithms
display_name: Algorithm
short_description: Algorithms are self-contained sequences that carry out a variety of tasks.
topic: algorithm
wikipedia_url: https://en.wikipedia.org/wiki/Algorithm
---
Algorithms are detailed sets of guidelines created for a computer program to complete tasks efficiently and thoroughly.
```

---

Demikian pula, koleksi **seperti** "[musik](https://raw.githubusercontent.com/github/explore/master/collections/music/index.md)"panggil hal-hal seperti penulis dan nama tampilan mereka di Front Matter variabel-dengan deskripsi terperinci di badan dokumen. Namun yang paling penting, koleksi mengidentifikasi masing-masing item koleksi mereka di [daftar YAML](https://en.wikipedia.org/wiki/YAML#Basic_components) untuk "item" kunci.

_/collections/music/index.md_:

```
---
items:
 - beetbox/beets
 - scottschiller/SoundManager2
 - CreateJS/SoundJS
 - musescore/MuseScore
 - tomahawk-player/tomahawk
 - cashmusic/platform
 - mopidy/mopidy
 - AudioKit/AudioKit
 - Soundnode/soundnode-app
 - gillesdemey/Cumulus
 - metabrainz/picard
 - overtone/overtone
 - samaaron/sonic-pi
display_name: Music
created_by: jonrohan
---
Drop the code bass with these musically themed repositories.
```

---

[Template permintaan tarik](./.Github/PULL_REQUEST_TEMPLATE.md) juga memberikan panduan tentang informasi yang perlu Anda sertakan. 

**Silakan isi template permintaan tarik sepenuhnya.** 

Jika Anda tidak mengisi template, PR Anda akan ditutup. 
## Mengurasi topik atau koleksi baru Jika suatu topik atau koleksi belum dikuratori,itu TIDAK akan terdaftar di direktori masing-masing. 
Kami cenderung mempertimbangkan saran untuk menyusun topik atau koleksi yang berharga bagi komunitas GitHub. 
Topik yang berharga, misalnya, termasuk yang sudah [banyak digunakan oleh repositori](https://help.github.com/articles/classifying-your-repository-with-topics/),atau topik yang saat ini tidak memiliki informasi penting . 
Saat menyarankan konten, harap pertimbangkan bagaimana membuat kontribusi Anda bermanfaat secara luas dan relevan bagi orang lain, alih-alih melayani kasus penggunaan tertentu. 
Harap perhatikan bahwa semua saran harus mematuhi [Pedoman Komunitas GitHub](https://help.github.com/articles/github-community-guidelines/) dan [Ketentuan Layanan](https://help.github.com/artikel/persyaratan-layanan-github/).
Sesuai Ketentuan Layanan kami, [Anda bertanggung jawab](https://help.github.com/articles/github-terms-of-service/#d-user-generated-content) untuk konten yang Anda berkontribusi, dan Anda harus memiliki hak untuk menggunakannya. 
Untuk mengusulkan topik atau koleksi baru, silakan **buka permintaan tarik** dengan penambahan yang Anda usulkan. 
[API docs](./docs /API.md) dan [style guide](./docs/styleguide.md) memberikan panduan tentang informasi yang perlu Anda sertakan dan bagaimana formatnya. 
Repositori ini mencakup [daftar topik GitHub yang paling banyak digunakan yang belum memiliki konteks tambahan](topik-todo.md). 
Jika permintaan tarik Anda menambahkan salah satu dari topik ini, harap perbarui topik-todo.md sehingga topik tersebut diperiksa (ditandai selesai). **Harap isi template permintaan tarik sepenuhnya.** Jika Anda tidak mengisi template, permintaan tarik Anda akan ditutup.

## Guidelines

* Avoid conflicts of interest. Maintainers of a project cannot add a topic or collection for their own project. If a topic is popular enough to warrant inclusion, someone else will add or improve it.

## Running tests

There are some lint tests in place to ensure each topic is formatted in the way we expect. Travis
CI will run the tests automatically. If you want to run the tests yourself locally, you will need
Ruby and Bundler installed.

You can run the tests using:

```bash
script/cibuild
```
