# 📝 Tugas/Refleksi: Evaluasi Strategi TI
## Studi Kasus: Universitas Pembangunan

**Mata Kuliah:** Perencanaan Strategis TI - Pertemuan 13

**Dosen Pengampu:** Dr. Basuki Rahmat, S.Si. MT

---

## I. Pendahuluan

Universitas Pembangunan (UP) sebagai institusi pendidikan tinggi sangat bergantung pada Teknologi Informasi (TI) untuk menjalankan Tridharma Perguruan Tinggi (pendidikan, penelitian, dan pengabdian masyarakat). Ketergantungan ini tercermin pada penggunaan sistem vital seperti Sistem Informasi Akademik (SIAMIK), Learning Management System (LMS) berbasis Moodle, dan sistem *e-office* untuk administrasi internal. Analisis ini bertujuan mengevaluasi kondisi isu etika, kebijakan, keamanan, dan tata kelola TI dalam konteks strategi TI di lingkungan UP.

---

## II. Evaluasi Isu Etika dalam TI 

Isu etika berfokus pada tanggung jawab moral dan sosial dalam penerapan TI di lingkungan akademis.

| Fokus Etika | Kondisi di Universitas Pembangunan (UP) | Tantangan dan Potensi Risiko |
| :--- | :--- | :--- |
| **Privasi Data** | UP memiliki kebijakan yang mewajibkan anonimitas data mahasiswa/dosen saat digunakan untuk riset internal. Akses ke data pribadi di SIAMIK dibatasi ketat hanya untuk unit yang berkepentingan. | Risiko kebocoran data (misalnya: Facebook-Cambridge Analytica) akibat *phishing* atau kesalahan konfigurasi sistem. |
| **Hak Kekayaan Intelektual** | UP memprioritaskan penggunaan *software* berlisensi resmi atau *open-source* untuk mengurangi *software piracy*. Terdapat sanksi akademik bagi kasus plagiarisme digital. | Memastikan semua unit kerja konsisten dalam penggunaan *software* berlisensi. |
| **Transparansi Algoritma** | UP menggunakan sistem seleksi beasiswa yang transparan dengan kriteria yang dipublikasikan. Proses keputusan tetap melibatkan verifikasi manual oleh komite. | Menghindari *AI bias* (bias pada kecerdasan buatan) jika sistem otomatisasi keputusan ditingkatkan. |

---

## III. Evaluasi Kebijakan TI 

Kebijakan TI adalah aturan formal yang mengatur penggunaan TI, bertujuan melindungi aset dan mendukung strategi organisasi.

| Jenis Kebijakan | Implementasi di Universitas Pembangunan (UP) | Efektivitas/Kesenjangan |
| :--- | :--- | :--- |
| **Kebijakan Keamanan Informasi** | UP memiliki *Standard Operating Procedure* (SOP) pengelolaan kata sandi dan penanganan insiden siber yang dimutakhirkan setiap tahun. | Perlu sosialisasi yang lebih intensif agar SOP tidak hanya menjadi dokumen, tetapi dipraktikkan. |
| **Kebijakan BYOD** | UP mengizinkan BYOD tetapi membatasi akses perangkat pribadi ke jaringan internal hanya pada jaringan tamu (*Guest Wi-Fi*) yang terpisah dari jaringan server utama. | Risiko masuknya *malware* atau ancaman keamanan lainnya dari perangkat pribadi. |
| **Kebijakan Penggunaan Email/Internet**| UP menetapkan bahwa email resmi hanya digunakan untuk urusan dinas dan akademik, melarang penggunaan untuk aktivitas ilegal atau penyebaran misinformasi. | Memastikan penggunaan fasilitas TI sejalan dengan norma dan etika akademik. |

---

## IV.Evaluasi Keamanan dalam Strategi TI 

Keamanan TI melibatkan perlindungan aset melalui pilar CIA Triad (Confidentiality, Integrity, Availability).

| Aspek Keamanan | Penerapan di Universitas Pembangunan (UP) | Keterkaitan dengan Strategi UP |
| :--- | :--- | :--- |
| **CIA Triad** | UP menerapkan enkripsi untuk data mahasiswa di SIAMIK (*Confidentiality*) dan prosedur *backup* harian ke server terpisah (*Integrity*). Kapasitas server ditingkatkan menjelang KRS untuk memastikan layanan tidak terganggu (*Availability*). | Jika SIAMIK *down*, seluruh proses akademik terhenti, mengancam kredibilitas UP dan *availability* layanan. |
| **Manajemen Ancaman** | UP menggunakan *firewall* modern, *Intrusion Detection System* (IDS), dan antivirus terpusat. Tim TI secara rutin memantau ancaman *malware* dan *phishing*. | Mencegah kerugian finansial dan reputasi akibat serangan siber. |
| **Awareness & Training** | Pelatihan keamanan siber diwajibkan bagi staf baru dan diadakan *refresher course* tahunan bagi dosen dan staf. | Keamanan siber paling lemah ada pada pengguna (*insider threats*). |

---

## V. Evaluasi Tata Kelola TI (*IT Governance*) 

Tata Kelola TI adalah kerangka untuk memastikan TI memberikan nilai tambah dan selaras dengan misi organisasi.

| Prinsip Tata Kelola | Kondisi di Universitas Pembangunan (UP) | Rekomendasi Framework |
| :--- | :--- | :--- |
| **Alignment TI & Bisnis** | Perencanaan investasi TI (pengadaan server/sistem) didiskusikan oleh Komite TI yang anggotanya mencakup Wakil Rektor Bidang Akademik dan Sumber Daya. | Menggunakan ISO/IEC 38500 untuk tata kelola di level manajemen puncak. |
| **Value Delivery** | Keberhasilan proyek TI diukur berdasarkan peningkatan efisiensi proses administrasi dan peningkatan kepuasan pengguna (survei *feedback* mahasiswa/dosen). | Menggunakan kerangka **COBIT** untuk memastikan kontrol dan audit yang efektif. |
| **Manajemen Layanan** | UP memiliki *Service Desk* terpusat yang menggunakan sistem *ticketing* untuk menangani masalah TI. Terdapat SOP untuk penanganan insiden dan permintaan layanan. | Menggunakan kerangka **ITIL** untuk meningkatkan manajemen layanan TI. |

---

## VI. Kesimpulan dan Rekomendasi

### Kesimpulan
Secara umum, Universitas Pembangunan telah memiliki dasar yang kuat dalam Kebijakan, Keamanan, dan Tata Kelola TI. Terdapat *alignment* antara strategi TI dan tujuan akademik. Namun, tantangan terbesar terletak pada sosialisasi kebijakan dan pengelolaan risiko etika yang terus berkembang (misalnya *deepfake* dan *AI bias*).

### Rekomendasi Aksi Nyata
1.  **[Rekomendasi Etika/Kebijakan]** Universitas harus secara formal mengadopsi **Kode Etik Penggunaan Sistem Informasi** yang mencakup isu *deepfake* dan misinformasi , serta mewajibkan pelatihan HAKI bagi seluruh sivitas akademika.
2.  **[Rekomendasi Tata Kelola/Keamanan]** Membentuk **Komite Tata Kelola TI** di level manajemen yang secara rutin memonitor *value delivery*  dan secara bertahap mengimplementasikan standar keamanan **ISO 27001** untuk Sistem Manajemen Keamanan Informasi (SMKI).
