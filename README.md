# Foto Kita Blur

Foto Kita Blur adalah aplikasi sederhana berbasis Python yang dapat memberikan efek blur pada wajah secara real-time menggunakan webcam. Aplikasi ini memanfaatkan OpenCV untuk pengolahan citra dan MediaPipe untuk mendeteksi gesture tangan.

## Fitur

- Blur wajah secara real-time
- Deteksi gesture tangan (Peace Sign ✌️)
- Mengaktifkan atau menonaktifkan blur menggunakan gesture
- Menggunakan webcam secara langsung

## Teknologi

- Python
- OpenCV
- MediaPipe
- NumPy

## Instalasi

Clone repository ini.

```bash
git clone https://github.com/putrifathonah/foto-kita-blur-.git
cd foto-kita-blur-
```

Install semua dependency.

```bash
pip install -r requirements.txt
```

Jalankan program.

```bash
python blur.py
```

## Cara Menggunakan

1. Jalankan aplikasi.
2. Izinkan webcam menyala.
3. Arahkan wajah ke kamera.
4. Gunakan gesture Peace Sign (✌️) untuk mengontrol blur.
5. Tekan `Q` untuk menutup aplikasi.

## Struktur Project

```
foto-kita-blur/
├── blur.py
├── requirements.txt
└── README.md
```

## Catatan

Jika muncul error seperti berikut:

```text
AttributeError: module 'mediapipe' has no attribute 'solutions'
```

Pastikan menggunakan virtual environment dan MediaPipe sudah terpasang dengan benar.

## Author

Putri Fathonah

GitHub: https://github.com/putrifathonah
