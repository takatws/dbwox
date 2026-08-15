# DbWox

**DbWox** adalah database client desktop gratis untuk membantu koneksi, eksplorasi, query, dan analisis berbagai database dari satu aplikasi. Proyek ini bersifat *freeware* dan didistribusikan dalam bentuk binary; source code tidak disertakan pada repository ini.

## Versi saat ini

**DbWox 1.0.0**

Silakan buka halaman [Releases](../../releases/latest) untuk mengunduh versi terbaru.

## Fitur utama

- Koneksi ke PostgreSQL, MySQL, Microsoft SQL Server, DB2, ClickHouse, Oracle, Microsoft Access, H2, dan DBF.
- Database Explorer: database, schema, table, view, function, procedure, key, grant, dan properti koneksi.
- SQL Query Editor dengan syntax highlighting, formatter SQL, autocomplete table/kolom, find/replace, undo/redo, dan hasil query streaming.
- Browse Data, Describe Table/View, DDL, grants, relasi foreign key, dan ER Diagram.
- Copy table antar koneksi serta dump database ke SQL.
- Dukungan GeoParquet dari file lokal, HTTP(S), dan Amazon S3.
- Workspace: simpan, impor, ekspor, backup, restore, serta reset workspace/settings.
- AI Assistant opsional dengan mode BYOK (*Bring Your Own Key*) untuk OpenAI atau Google Gemini.
- Penguncian aplikasi opsional untuk melindungi akses lokal.
- Tema terang/gelap serta antarmuka desktop yang dioptimalkan untuk pekerjaan database sehari-hari.

## Unduhan dan instalasi

| Platform | File | Catatan |
| --- | --- | --- |
| Windows | `DBWox-<versi>.msi` | Jalankan installer, lalu buka **DBWox** dari Start Menu. |
| macOS | `DBWox-<versi>-macos-distribution.zip` | Extract di Mac, kemudian jalankan `build-macos.sh` menggunakan JDK 26 untuk membuat DMG sesuai arsitektur Mac. |
| Linux | `DBWox-<versi>-linux-distribution.zip` | Extract di Linux, lalu jalankan `build-linux.sh` menggunakan JDK 26 untuk membuat `.deb`, `.rpm`, atau app-image. |

> Build native macOS dan Linux perlu dilakukan pada sistem operasi tujuan agar runtime dan arsitektur CPU sesuai.

## Kebutuhan sistem

- Windows: installer sudah menyertakan runtime Java yang diperlukan.
- macOS/Linux: JDK 26 diperlukan untuk menjalankan script pembuat installer pada platform tersebut.
- Koneksi jaringan sesuai kebutuhan database atau sumber data yang digunakan.

## AI Assistant dan privasi

AI Assistant bersifat opsional. DbWox menggunakan model BYOK: API key berasal dari pengguna dan request hanya dikirim setelah pengguna mengaktifkan serta menyetujui pengiriman konteks yang relevan.

Jangan pernah membagikan API key, password database, atau data sensitif pada issue maupun diskusi publik.

## Dukungan dan masukan

Silakan gunakan halaman **Issues** untuk melaporkan bug atau mengajukan fitur. Sertakan:

1. Versi DbWox dan sistem operasi.
2. Jenis database serta versinya.
3. Langkah untuk menghasilkan masalah.
4. Pesan error atau screenshot, setelah menghapus informasi sensitif.

DbWox gratis digunakan. Jika aplikasi ini membantu pekerjaan Anda dan Anda ingin mendukung pengembangannya, informasi donasi akan ditambahkan pada halaman ini.

## Lisensi dan distribusi

Repository ini hanya berfungsi sebagai tempat distribusi binary resmi DbWox. Hak cipta dan ketentuan penggunaan akan diumumkan pada rilis berikutnya.
