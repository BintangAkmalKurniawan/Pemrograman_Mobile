🚀 Langkah Pembuatan Project

    Buat Project Baru
    Di Android Studio, pilih New Project > Empty Activity. Beri nama project kamu (misalnya "KamalApp").

    Struktur File Utama

        MainActivity.kt: File Kotlin utama yang menangani interaksi pengguna.

        activity_main.xml: File layout yang mengatur tampilan UI.

🧩 Penjelasan Komponen
1. activity_main.xml (Desain UI)

File ini mendefinisikan tampilan antarmuka pengguna, terdiri dari:

    EditText → Input untuk nomor HP dengan icon telepon.

    Button → Beberapa tombol untuk:

        Memilih tanggal (btnDate)

        Memilih waktu (btnTime)

        Menampilkan alert dialog (btnAlert)

        Menampilkan toast (btnToast)

Semua komponen ini ditempatkan dalam LinearLayout dengan orientasi vertikal dan padding agar tampil rapi.

2. MainActivity.kt (Logika Aplikasi)

File ini berisi logika yang mengatur interaksi pengguna:

    phoneInput → Mengambil nilai input dari EditText.

    btnDate → Menampilkan DatePickerDialog saat ditekan.

    btnTime → Menampilkan TimePickerDialog untuk memilih jam dan menit.

    btnAlert → Menampilkan AlertDialog dengan pilihan "OK" dan "Cancel".

    btnToast → Menampilkan pesan toast sebagai notifikasi ringan.


Project ini untuk memenuhi tugas Pemrograman Mobile
