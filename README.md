# Analisis Peran Teman, Absensi, dan Kedisiplinan Belajar dalam Meningkatkan Performa Siswa

# 💫 About Me:

<h3>Hi 👋, I'm Sekar Novica Azkarani</h3>

<p>
Saya baru saja menyelesaikan sebuah <b>Capstone Project</b> sebagai bagian dari tugas <b>Data Classification and Summarization Using IBM Granite</b>, dengan menggunakan dataset dari Kaggle:  
<a href="https://www.kaggle.com/datasets/hannhu4002/analysis-of-student-academic-performance-factors" target="_blank">Analysis of Student Academic Performance Factors</a>
</p>

<p>
I'm currently working on <b>Capstone Project IBM Data Classification and Summarization Using IBM Granite</b> berjudul:  
<h3>"Analisis Peran Teman, Absensi, dan Kedisiplinan Belajar dalam Meningkatkan Performa Siswa"</h3>
</p>

<p>🔗 Google Colab: 
<a href="https://colab.research.google.com/drive/1PPrYadbYjXgzVG6ZXVIv2Nhrl4pWQR9U?usp=sharing" target="_blank">Klik di sini</a>  
</p>

<p>📊 Dashboard: 
<a href="https://github.com/sekarzakarani/Capstone_Project-IBM_Data-Classification-and-Summarization-Using-IBM-Granite_Sekar-Novica-Azkarani/blob/f5ef9719fc3c4bb5d48b701ade6f0f36fb90e598/Capstone_Project_SekarNovicaAzkarani.zip" target="_blank">Klik di sini</a>  
</p>

 

<h2>Latar Belakang</h2>
<p>Pendidikan adalah proses kompleks yang dipengaruhi oleh berbagai faktor. Tiga faktor utama yang teridentifikasi memiliki dampak signifikan pada performa akademik siswa adalah pengaruh teman sebaya (Peer_Influence), kehadiran (Attendance), dan waktu belajar per minggu (Hours_Studied_Week). Memahami hubungan kausal antara faktor-faktor ini dan nilai ujian (Exam_Score) sangat krusial bagi pihak sekolah dan orang tua. Analisis ini bertujuan untuk memberikan wawasan berbasis data agar strategi peningkatan performa siswa dapat dirancang secara lebih efektif dan tepat sasaran.</p>

<h2>Tujuan</h2>
<ul>
  <li>Menganalisis faktor-faktor yang paling dominan dalam memengaruhi performa akademik siswa.</li>
  <li>Mengelompokkan siswa berdasarkan kategori nilai (Low, Medium, High) untuk memahami distribusi capaian akademik.</li>
  <li>Menyusun insight yang dapat mendukung pengambilan keputusan berbasis data bagi sekolah, guru, maupun orang tua.</li>
  <li>Menghasilkan rekomendasi strategi yang konkret dan actionable untuk meningkatkan prestasi akademik siswa.</li>
</ul>

<h2>Permasalahan</h2>
<ul>
  <li>Dari ketiga faktor yang dianalisis (Peer_Influence, Attendance, dan Hours_Studied_week), manakah yang paling dominan dalam memengaruhi nilai ujian siswa?</li>
  <li>Bagaimana distribusi siswa di setiap kategori nilai ujian (Low, Medium, High)?</li>
  <li>Apa saja rekomendasi yang relevan dan dapat diterapkan untuk meningkatkan capaian akademik siswa berdasarkan temuan analisis?</li>
</ul>

<h2>Pendekatan</h2>
<p>Pendekatan yang digunakan dalam proyek ini meliputi beberapa tahapan utama:</p>
<ol>
  <li>
    <b>Eksplorasi Data (Data Exploration)</b>  
    <ul>
      <li>Menganalisis struktur, karakteristik, dan kualitas dataset.</li>
      <li>Melakukan analisis statistik deskriptif (rata-rata, median, standar deviasi).</li>
      <li>Membuat visualisasi seperti histogram dan box plot untuk melihat distribusi data.</li>
      <li>Mengidentifikasi anomali, missing values, atau kesalahan entri data.</li>
    </ul>
  </li>
  <li>
    <b>Pra-pemrosesan Data (Preprocessing)</b>  
    <ul>
      <li><i>Cleaning</i>: Menghapus/mengisi nilai yang hilang serta mengatasi anomali.</li>
      <li><i>Encoding</i>: Mengubah variabel kategorikal (misalnya Peer_Influence) menjadi numerik.</li>
      <li><i>Scaling</i>: Menyamakan skala variabel numerik agar lebih optimal untuk model.</li>
    </ul>
  </li>
  <li>
    <b>Pemodelan Klasifikasi (Classification)</b>  
    <ul>
      <li>Membangun model prediktif untuk mengklasifikasikan siswa ke kategori nilai (Low, Medium, High).</li>
      <li>Menggunakan algoritma <i>Random Forest</i> (untuk hubungan kompleks) atau <i>Logistic Regression</i> (untuk interpretasi probabilitas).</li>
    </ul>
  </li>
  <li>
    <b>Analisis Signifikansi Fitur (Feature Importance)</b>  
    <ul>
      <li>Menentukan faktor paling berpengaruh terhadap nilai ujian.</li>
      <li>Menggunakan koefisien regresi (Logistic Regression) atau feature importance (Random Forest).</li>
    </ul>
  </li>
  <li>
    <b>Perumusan Insight (AI Summarization - IBM Granite)</b>  
    <ul>
      <li>Merangkum hasil analisis menjadi narasi singkat dan mudah dipahami.</li>
      <li>Menggunakan model AI untuk menyusun insight yang dapat ditindaklanjuti.</li>
    </ul>
  </li>
  <li>
    <b>Visualisasi & Dashboard (Streamlit + ngrok)</b>  
    <ul>
      <li>Membangun dashboard interaktif menggunakan Streamlit.</li>
      <li>Menyediakan visualisasi distribusi nilai, korelasi, dan hasil prediksi model.</li>
      <li>Menggunakan ngrok agar dashboard dapat diakses publik.</li>
    </ul>
  </li>
</ol>

<h2>Insight</h2>
<p>
Analisis data menunjukkan bahwa <b>Peer_Influence</b> dan <b>Hours_Studied_week</b> memiliki nilai kepentingan yang relatif tinggi dalam memengaruhi nilai ujian, dengan nilai kepentingan masing-masing 0.13 dan 0.094.</p>

<h2>Findings</h2>
<ul>
  <li>Distribusi nilai ujian terlihat tidak seimbang, dengan banyak siswa memiliki nilai rendah (61–66) dan hanya sedikit yang memperoleh nilai lebih tinggi (67, 68, 71).</li>
  <li>Model klasifikasi menghasilkan <i>f1-score</i> tertinggi (0.40) pada kelas 64, menunjukkan prediksi lebih baik pada kelompok nilai sekitar 64 dibandingkan kelas lainnya.</li>
  <li>Faktor <i>Peer_Influence</i> dan <i>Hours_Studied_week</i> terbukti lebih signifikan dibandingkan faktor lainnya.</li>
  <li> Selain itu, faktor <i>Attendance, Previous_Scores, Sleep_Hours, Tutoring_Sessions,</i> dan <i>Physical_Activity</i> juga memberikan kontribusi, namun tingkat pengaruhnya lebih rendah. </li>
</ul>

<h2>Conclusion</h2>
<p>
Dari hasil analisis, dapat disimpulkan bahwa <b>Peer_Influence</b> dan <b>jam belajar per minggu</b> merupakan faktor dominan yang memengaruhi nilai ujian siswa.  
Namun, rendahnya skor f1 untuk hampir semua kelas menandakan bahwa model klasifikasi masih perlu perbaikan agar dapat memberikan prediksi yang lebih akurat.
</p>

<h2>Recommendation</h2>
<ol>
  <li>Membangun program untuk mendorong hubungan positif antar siswa (<i>Peer_Influence</i>) agar dapat saling memotivasi dalam belajar.</li>
  <li>Memberikan panduan manajemen waktu belajar sehingga siswa memiliki <b>jam belajar mingguan</b> yang cukup dan terstruktur.</li>
  <li>Meningkatkan partisipasi siswa dalam kelas (<i>Attendance</i>) melalui metode pembelajaran yang lebih interaktif dan menarik.</li>
  <li>Menyediakan dukungan tambahan berupa <i>Tutoring Sessions</i> atau bimbingan belajar bagi siswa dengan nilai rendah.</li>
  <li>Mendorong keseimbangan gaya hidup siswa, termasuk tidur cukup dan aktivitas fisik yang sehat, agar performa akademik tetap optimal.</li>
</ol>

<h2>AI Support Explanation</h2>
Dalam proyek ini, kecerdasan buatan (AI) digunakan untuk mendukung proses analisis data melalui fitur AI Summarization. Peran AI dalam analisis ini meliputi:
1. <b>Automatic Summarization</b>, AI secara otomatis merangkum hasil analisis teknis (feature importance, klasifikasi nilai ujian, distribusi kategori) menjadi penjelasan naratif yang mudah dipahami.
2. <b>Insight Generation</b>, AI membantu mengidentifikasi faktor utama yang memengaruhi nilai ujian siswa yaitu <i>Peer_Influence</i> (pengaruh teman sebaya) dan <i>Hours_Studied_week</i> (jam belajar per minggu). Kedua faktor ini dinilai memiliki kontribusi terbesar dibandingkan faktor lain seperti Attendance, Previous_Scores, Sleep_Hours, Tutoring_Sessions, dan Physical_Activity.
3. <b>Structured Reporting</b>, Output AI diformat menjadi empat bagian utama:
   <li><b>Insight</b>, Menunjukkan temuan penting bahwa <i>Peer_Influence</i> dan <i>Hours_Studied_week</i> berperan signifikan terhadap capaian nilai ujian.</li>
   <li><b>Findings</b>, Menjelaskan distribusi nilai ujian siswa yang tidak seimbang, dengan dominasi nilai rendah (61–66) dan hanya sedikit siswa dengan nilai lebih tinggi.</li>
   <li><b>Conclusion</b>, Menyimpulkan bahwa hubungan sosial positif dan manajemen waktu belajar efektif dapat menjadi kunci peningkatan prestasi akademik.</li>
   <li><b>Recommendation</b>, Memberikan rekomendasi konkret seperti mendorong interaksi positif antar siswa, memastikan siswa memiliki waktu belajar yang terstruktur, serta meningkatkan partisipasi aktif melalui kehadiran dan sesi bimbingan tambahan.</li>
4. <b>Decision Support</b>  
Dengan menggunakan AI, hasil analisis tidak hanya berupa angka atau metrik teknis, tetapi diterjemahkan menjadi narasi yang aplikatif. Rekomendasi yang dihasilkan dapat menjadi dasar kebijakan sekolah, strategi pembelajaran guru, maupun pedoman orang tua dalam mendukung siswa mencapai hasil akademik yang lebih baik.

  
## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/www.linkedin.com/in/sekar-novica-azkarani-99754137b) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:sekarnovicaazkarani@gmail.com) 

# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=sekarzakarani&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=sekarzakarani&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=sekarzakarani&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=sekarzakarani&theme=radical&no-frame=false&no-bg=true&margin-w=4)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

---
[![](https://visitcount.itsvg.in/api?id=sekarzakarani&icon=9&color=1)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
