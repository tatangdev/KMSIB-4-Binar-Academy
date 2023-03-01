# Exercises and Challenges

## Chapter 1

## Chapter 2

## Chapter 3

### Topic 1 | Database

#### Intruksi

Pada topik ini, kita akan mengenal simbol-simbol yang digunakan untuk membuat ERD. Kamu cukup memperhatikan contoh yang diberikan oleh facil dan mengulangnya agar dapat mengingatnya dengan mudah.

**Personal Note:**

> _-_

### Topic 2 | DBMS

#### Intruksi

Sebuah platform memiliki fitur post, like dan comment

Informasi User yang disimpan adalah sebagai berikut :

- ID user
- nama user, dan
- profile user

User-user ini dapat membuat banyak postingan. Informasi post yang disimpan adalah sebagai berikut :

- ID komponen
- url media
- deskripsi postingan
- jumlah like, dan
- komentar dari user lainnya

Buatlah ERD untuk menunjukkan bagaimana kamu akan menyimpan informasi ini.

#### Asumsi

- **user** dapat eksis tanpa membuat **post**.
- data **post** harus dikaitkan dengan **user**.
- Sebuah **komentar** tidak dapat eksis tanpa **user**.
- Sebuah **like** tidak dapat eksis tampa **user**.

**Personal Note:**

> _-_

### Topic 3 | Query languages

#### Intruksi

Pada topik ini kita akan berlatih menggunakan query language, kamu cukup memperhatikan contoh yang diberikan oleh facil dan mengulangnya agar dapat mengingatnya dengan mudah.

**Personal Note:**

> _-_

### Topic 4 | RDBMS

#### Intruksi

Setelah di topik 2 kita mevisualisasikan bagaimana data platform media sosial akan disimpan didalam database, kita akan latihan untuk mengimplementasikannya didalam database SQL:

- Membuat database
- Membuat table
- Membuat perintah CRUD

**Personal Note:**

> _-_

### Challenge

#### Intruksi

Pabrikan sebuah perusahaan manufaktur menghasilkan produk.

Informasi produk yang disimpan adalah sebagai berikut :

- ID produk
- nama produk, dan
- kuantitas

Produk-produk ini terdiri dari banyak komponen. Setiap komponen dapat dipasok oleh satu atau lebih pemasok.

Informasi komponen yang disimpan adalah sebagai berikut :

- ID komponen
- nama komponen
- deskripsi
- pemasok yang memasoknya
- produk yang menggunakannya

Buatlah ERD untuk menunjukkan bagaimana kamu akan menyimpan informasi ini.

#### Asumsi

- Pemasok dapat eksis tanpa menyediakan komponen.
- Komponen tidak harus dikaitkan dengan pemasok.
- Komponen tidak harus dikaitkan dengan produk.
- Tidak semua komponen digunakan dalam produk.
- Suatu produk tidak dapat eksis tanpa komponen.

#### Point penilaian

- Membuat ERD **(40 Point)**
- Membuat table dengan DDL **(30 Point)**
- Membuat CRUD dengan DML **(30 Point)**

**Personal Note :**

> source: https://opentextbc.ca/dbdesign01/back-matter/appendix-b-erd-exercises/

## Chapter 4 - RESTful api

### Topic 1 | Node JS

LikeInsta adalah sebuah aplikasi seperti instagram, sebagai permulaan kita akan menambahkan sebuah tabel post berisikan kolom sebagai berikut:

- id
- content_url
- description

#### Intruksi

1. Buatlah sebuah database dummy database dengan nama /db/post.json
2. Buatlah project dengan menggunan NodeJS.
3. Buatlah fungsi CRUD untuk database yang telah dibuat dengan menggunan package [File system](https://nodejs.org/api/fs.html)

**Personal Note:**

> _-_

### Topic 2 | Express JS

#### Intruksi

1. Buatlah project dengan menggunakan ExpressJS.
2. Konversikan program CRUD yang telah dikerjakan pada latihan Chapter 1 menjadi project ExpressJS

**Personal Note:**

> _-_

### Topic 3 | RESTful

#### Intruksi

Pada chapter sebelumnya kita telah membuat program Express JS. Namun kita hanya menggunakan method GET dalam pembuatan endpointnya.
Konversikan program tersebut menjadi sebuah program RESTful API yang lengkap.

**Personal Note:**

> _-_

### Topic 4 | ORM

#### Intruksi

Pada chapter sebelumnya kita telah membuat program Express JS dengan menerapkan konsep RESTful API. Disana kita melakukan CRUD data dengan menggunakan RAW query, ORM adalah teknik yang dapat membantu kita melakukan CRUD data dengan lebih mudah.
Konversikan lah CRUD yang sudah kita buat dengan menggunakan ORM.

**Personal Note:**

> _-_

### Challenge

**Personal Note:**

> Sudah ditambahkan di slide

## Chapter 5 - on progress

### Topic 1 |

### Topic 2 |

### Topic 3 |

### Topic 4 |

### Challenge

## Chapter 6

### Topic 1 | Testing

1. Buatlah test case dalam CRUD table post
2. Buatlah script testing untuk masing-masing case yang sudah digunakan

### Topic 2 | Cloud and Server

Tidak perlu diberi latihan karena disini hanya berisi materi konsep.

### Topic 3 | CI/CD

Pada latihan kali ini, kita akan mendistribusikan(deployment) aplikasi yang sudah kita kerjakan kedalam server. Tujuan pendistribusian ini adalah agar aplikasi kita dapat digunakan oleh pengguna. Untuk pendistribusian aplikasi, kita akan menggunakan beberapa platform berikut:

1. GitHub
2. Github Action
3. Vercel

Agar proses deployment dapat berjalan dengan lancar, tahap-tahap yang harus dikerkakan adalah:

- Membuat repository
- Membuat project didalam Railway
- Setup github action (ci/cd script)
- Setup environment variabel didalam Railway
- Setup database didalam Railway

### Topic 4 | Debugging dan Logging

Pada latihan sebelumnya, kita telah mendistribusikan aplikasi kita dengan menggunakan Railway. Saat aplikasi kita sudah berjalan secara online, kita akan mendapatkan kendala dalam memonitoring aplikasi kita terlebih saat terjadi error. Kita tidak akan bisa melakukan debugging saat terjadi error didalam aplikasi kita.

Untuk membantu kita dalam melakukan debugging dan logging. kita dapat menggunakan Sentry. Tahap yang bisa dikerjakan adalah sebagai berikut:

- Buat sebuah project sentry baru
- Setup sentry didalam aplikasi RESTful api kita
- Setup env agar kita dapat membedakan apakah error terjadi di dalam env test atau production
- Setup Error handling dengan menggunakan sentry
- Tambahkanlah konfigurasi trace agar kita dapat memonitoring traffic didalam apklikasi kita

### Challenge

## Chapter 7 - on progress

### Topic 1 |

### Topic 2 |

### Topic 3 |

### Topic 4 |

### Challenge
