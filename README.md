# Rekrutmen-Data-Analyst-Seara-Bank-2026
# Overview

---

!images (3).jpg.jpg)

## Outline Overview Project :
- Business Understanding
- Result Summary of The Project
- Key Takeaways
- Process
- More Insights / Recommendation Business
- The Project

## Business Understanding

---

- Problem:
    
    Dalam proses rekrutmen Data Analyst di SearaBank, perusahaan menghadapi tantangan dalam memahami kesiapan kandidat terhadap kebutuhan teknis yang spesifik, terutama pada kompetensi Excel, SQL, Python, dan BI tools.
    
    Selain itu, belum terdapat pemetaan yang jelas mengenai:
    
    - Kesesuaian skill kandidat dengan kebutuhan tiap posisi (Junior vs Senior)
    - Distribusi kemampuan teknis antar Fresh Graduate dan Experienced
    - Efektivitas channel rekrutmen dan sebaran talent pool
    
    Hal ini menyebabkan proses screening belum sepenuhnya berbasis data dan masih membutuhkan optimasi untuk meningkatkan efisiensi rekrutmen.
    
- Objective:
    - Menganalisis distribusi kompetensi teknis kandidat (SQL, Python, Excel, BI tools)
    - Memetakan kesiapan kandidat terhadap kebutuhan posisi Junior dan Senior Data Analyst
    - Mengidentifikasi segmentasi kandidat berdasarkan level pengalaman
    - Menganalisis sumber kandidat dan persebaran geografis
    - Memberikan rekomendasi strategi rekrutmen berbasis data
- Business Question:
    - Bagaimana distribusi kompetensi teknis kandidat terhadap kebutuhan tools perusahaan?
    - Di platform BI mana kandidat potensial paling banyak ditemukan?
    - Apakah Fresh Graduate mampu bersaing dengan Experienced dalam kompetensi SQL dan Python?
    - Bagaimana distribusi kandidat berdasarkan domisili dan sumber informasi lowongan?
    - Segmen kandidat mana yang paling siap untuk kebutuhan Junior dan Senior role?

## Result Summary of The Project

---

- Total kandidat: **681 orang**
- Fresh Graduate: **56,7% (386 kandidat)**
- Experienced: **43,3%**

### Temuan Utama:

- SQL (561), Python (546), dan Excel (527) menjadi skill paling dominan
- BI tools seperti Tableau dan Looker Studio masih lebih rendah dibanding tools hulu
- Kombinasi **Excel + Tableau** paling banyak dimiliki kandidat Junior (224 kandidat)
- Terdapat ±300 Fresh Graduate yang memenuhi kualifikasi awal posisi Senior (SQL & Python)
- 80,6% kandidat berasal dari LinkedIn
- Kandidat terkonsentrasi di Jawa Barat, DKI Jakarta, Jawa Timur, dan Jawa Tengah

## Key Takeaways

---

### Apa yang dipelajari?

- Talent pool Fresh Graduate sangat besar dan kompetitif
- Skill SQL dan Python tidak hanya dimiliki oleh experienced candidate
- BI tools menjadi skill gap utama untuk kebutuhan tertentu
- LinkedIn merupakan channel rekrutmen paling efektif
- Persebaran kandidat masih terpusat di wilayah urban

### Tantangan:

- Perbedaan skill antar tools hulu (SQL, Python) vs hilir (BI tools)
- Kebutuhan Junior dan Senior memiliki karakteristik kompetensi yang berbeda
- Tidak semua kandidat BI-ready meskipun memiliki Excel dasar
- Segmentasi kandidat perlu lebih presisi untuk efisiensi hiring

### Yang bisa ditingkatkan:

- Penambahan scoring system untuk kandidat (skill-based ranking)
- Automasi screening berbasis rule engine (SQL/Python threshold)
- Penguatan talent pipeline untuk BI tools (Power BI & Looker Studio)
- Optimasi sourcing di luar LinkedIn untuk diversifikasi talent pool

## Process

---

- Pengumpulan data rekrutmen internal SearaBank (681 kandidat)
- Data understanding (profil kandidat, skill, motivasi, sumber, domisili)
- Data cleaning:
    - Standarisasi teks (PROPER, REGEXREPLACE)
    - Penghapusan duplikasi data
    - Handling missing value
- Data transformation:
    - Kategorisasi domisili (IF + VLOOKUP)
    - Encoding skill menjadi binary (IF + REGEXMATCH)
    - Pivot table untuk summary data
- Exploratory Data Analysis (EDA):
    - Analisis distribusi kandidat
    - Analisis kompetensi teknis
    - Analisis kombinasi skill
    - Analisis motivasi & sumber rekrutmen
- Visualisasi dashboard menggunakan Google Looker Studio

## More Insights / Recommendation Business

---

- Prioritaskan kandidat Junior untuk kombinasi **Excel + Tableau** karena supply paling besar
- Untuk posisi Junior Squad Pockets, perlu strategi khusus karena kandidat Power BI dan Looker Studio lebih terbatas
- Gunakan SQL & Python sebagai filtering awal untuk posisi Senior Credit Risk Analyst
- Fresh Graduate dengan performa tinggi dapat dimasukkan ke **talent pipeline Senior development**
- LinkedIn tetap menjadi channel utama, namun perlu diversifikasi sourcing untuk memperluas talent pool
