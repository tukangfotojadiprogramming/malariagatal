# Analisis Infeksi Malaria Berdasarkan Perbedaan Tekstur Citra Sel Darah Menggunakan Segmentasi Thresholding

## Anggota Kelompok
| Nama                             |      NIM      |
|----------------------------------|---------------|
| Lalu Adittya Pratama Jelindra    |  F1D02310014  |
| Zamzami Satria Tegar             |  F1D02310029  |
| Aditia Rahmat Maulana            |  F1D02310030  |
| Rifky Akbar Utomo Putra          |  F1D02310149  |

# Latar Belakang
### Malaria merupakan penyakit menular yang masih menjadi ancaman serius, terutama di wilayah tropis. Proses deteksinya umumnya dilakukan secara manual melalui pemeriksaan mikroskopis, yang rentan terhadap kesalahan dan memerlukan waktu serta tenaga ahli. Padahal, citra sel darah penderita malaria memiliki tekstur yang berbeda dari sel darah normal, dan perbedaan ini bisa dimanfaatkan untuk analisis otomatis. Dengan menggunakan segmentasi thresholding, bagian penting dari citra bisa dipisahkan secara efisien, sehingga analisis tekstur menjadi lebih fokus dan akurat. Oleh karena itu, pemanfaatan pengolahan citra digital dalam mendeteksi infeksi malaria menjadi langkah penting menuju sistem diagnosis yang lebih cepat dan terjangkau.

### Program ini dirancang untuk membantu proses deteksi awal infeksi malaria melalui analisis citra mikroskopis sel darah. Tahap pertama dilakukan segmentasi menggunakan metode thresholding untuk memisahkan objek utama (sel darah) dari latar belakang citra. Setelah itu, program menganalisis tekstur dari citra yang telah disegmentasi guna membedakan antara sel darah normal dan sel yang berpotensi terinfeksi parasit malaria. Dengan pendekatan ini, program diharapkan mampu memberikan dukungan awal dalam sistem diagnosis malaria secara otomatis dan efisien.

# Preprocessing 
### Metode yang digunakan dalam penyusunan project ini adalah Resize, Grayscale, Normalisasi, Thresholding, Median, Erosi, dan Segmentasi/Masking.

# Dataset
### Parasitized:
![C33P1thinF_IMG_20150619_114756a_cell_179](https://github.com/user-attachments/assets/24359699-3888-49b2-9693-3f18b26aaec5)
### Uninfected
![C1_thinF_IMG_20150604_104722_cell_60](https://github.com/user-attachments/assets/bb90e887-3590-4eaf-9837-ed3806495733)

## Hasil Perhitungan Akurasi
### Percobaan Before:
![Screenshot 2025-06-02 225249](https://github.com/user-attachments/assets/8feb47b3-b44a-48d7-aa26-ee82609ba9c2)

### Percobaan 1:
![Screenshot 2025-06-02 215152](https://github.com/user-attachments/assets/97518834-c586-4d4b-8aac-71544c44e6e4)

### Percobaan 2:
![Screenshot 2025-06-02 223522](https://github.com/user-attachments/assets/e245aab9-ee58-4c2a-a6ae-4189702ba6c0)

### Percobaan 3:
![Screenshot 2025-06-02 230120](https://github.com/user-attachments/assets/5a59162b-b344-478b-9ca5-17db3712bb5e)


