# Seeder Data Repository

## Deskripsi

Repository ini berisi kumpulan data yang dapat digunakan untuk keperluan seeding dalam aplikasi atau sistem yang membutuhkan data dummy. Data yang tersedia mencakup berbagai kategori keterampilan yang dapat digunakan untuk mengisi tabel database atau sebagai contoh dalam proyek pengembangan perangkat lunak.

Data ini disusun dalam format JSON dan mencakup berbagai jenis keterampilan yang dibagi ke dalam kategori-kategori berikut:

- **Programming Language**
- **Framework**
- **Database**
- **Tool**
- **Soft Skill**
- **Language**
- **Other**

Data dalam repository ini bisa digunakan untuk:

- Menyediakan data awal untuk aplikasi berbasis keterampilan
- Mengisi tabel atau model dalam sistem manajemen data
- Sebagai contoh atau referensi dalam pengembangan aplikasi

## Format Data

Setiap data memiliki format yang konsisten sebagai berikut:

```json
{
  "skillName": "string",
  "skillCategory": "ENUM",
  "description": "string"
}
```

## Penjelasan

- **skillName**: Nama keterampilan atau keahlian, misalnya "Java", "Project Management", atau "SEO".
- **skillCategory**: Kategori keterampilan yang dipilih dari salah satu ENUM berikut:
  - `PROGRAMMING_LANGUAGE`: Keterampilan dalam bahasa pemrograman.
  - `FRAMEWORK`: Keterampilan dalam framework pengembangan perangkat lunak.
  - `DATABASE`: Keterampilan dalam penggunaan dan manajemen sistem database.
  - `TOOL`: Keterampilan menggunakan perangkat atau alat untuk pengembangan perangkat lunak dan pekerjaan profesional lainnya.
  - `SOFT_SKILL`: Keterampilan interpersonal atau soft skills.
  - `LANGUAGE`: Keterampilan dalam bahasa asing.
  - `OTHER`: Keterampilan yang tidak masuk ke dalam kategori di atas.
- **description**: Deskripsi singkat mengenai keterampilan tersebut.

## Penggunaan

Untuk menggunakan data ini sebagai seeder dalam aplikasi Anda, Anda dapat mengimpor file JSON yang sesuai dengan kategori yang diinginkan ke dalam sistem basis data Anda. Berikut adalah langkah-langkah umum yang dapat diikuti:

1. Pilih file JSON yang sesuai dengan kategori keterampilan yang Anda perlukan.
2. Gunakan data tersebut untuk mengisi database melalui script seeding atau migrasi.
3. Sesuaikan format dan data dengan kebutuhan aplikasi atau proyek Anda.
