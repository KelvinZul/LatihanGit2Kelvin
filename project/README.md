# Struktur Proyek Pengingat Eksperimen

Repositori ini menyiapkan kerangka kerja untuk menjalankan alur pengingat eksperimen melalui Google Colab dan Google Drive.

## Struktur Folder

```
project/
├── config.json         # Placeholder konfigurasi webhook dan pesan pengingat
├── datasets/           # Tempat menyimpan dataset terkait eksperimen
└── notebooks/
    └── reminder_ai.ipynb  # Notebook Colab untuk memasang Drive dan membaca konfigurasi
```

## Cara Menggunakan Notebook

1. Buka `project/notebooks/reminder_ai.ipynb` di Google Colab.
2. Jalankan sel pertama untuk memasang Google Drive dengan `drive.mount('/content/drive')`.
3. Pastikan folder `project/` berada di `MyDrive/` sehingga file `config.json` dapat dibaca oleh notebook.
4. Jalankan sel kedua untuk memuat `config.json` dan menampilkan isi placeholder `n8n_webhook_url` serta `reminder_message`.

Dengan mengikuti langkah di atas, notebook dapat dioperasikan langsung di lingkungan Google Colab.
