# 🧠 Social Media Sentiment & Issue Analysis  
**Simulated Enterprise Case**

---

## 📌 Project Overview

| Attribute | Description |
|---------|-------------|
| **Role** | Data Analyst |
| **Domain** | Brand Intelligence / Social Media Analytics |
| **Tools** | Python, SQL, Power BI, BERT, LDA |
| **Status** | 🟡 Phase 2 – In Progress |

---

## 📌 Executive Summary

Proyek ini mensimulasikan **alur kerja Social Listening profesional** untuk brand berskala nasional di sektor **Telekomunikasi**.  
Fokus utama proyek adalah mengubah **data tidak terstruktur** dari **Twitter/X, News Online, dan Forum** menjadi **Actionable Reputation Metrics** yang dapat digunakan oleh tim PR, Marketing, dan Management.

Sistem ini dirancang untuk mendeteksi **Emerging Issues secara dini** menggunakan pendekatan **Natural Language Processing (NLP) modern**, sehingga organisasi dapat melakukan **mitigasi krisis sebelum sebuah isu berkembang menjadi viral dan berdampak destruktif terhadap reputasi brand**.

---

## 🛠️ Tech Stack & Methodology

### 1️⃣ Data Processing & NLP (The “Brain”)

- **Language:** Python (Pandas, NumPy)
- **Sentiment Analysis:** Hybrid NLP Approach  
  - *Transformer-ready:* Persiapan integrasi **BERT (Bidirectional Encoder Representations from Transformers)** untuk sentimen berbasis konteks  
  - *Rule-based fallback:* Pemrosesan cepat untuk kata kunci spesifik industri
- **Topic Modelling:**  
  - Implementasi **Latent Dirichlet Allocation (LDA)** untuk ekstraksi topik dan klaster isu tanpa pelabelan manual

---

### 2️⃣ Database Architecture (MySQL)

- **Schema Optimization** khusus untuk data media sosial
- **utf8mb4 encoding** untuk mendukung emoji dan bahasa informal netizen
- **DATETIME indexing** untuk optimasi analisis time-series (Peak Hour Detection)
- **BIGINT** untuk mendukung skalabilitas metrik *Potential Reach* dan *Engagement*

---

### 3️⃣ Visualization & Intelligence (Deliverables)

- **Power BI / Tableau**
- Dashboard eksploratif untuk kebutuhan **C-Level & Stakeholder**
- Fokus metrik utama:
  - Sentiment Share
  - Share of Voice (SoV)
  - Issue Heatmap
  - Interaction & Engagement Rate

---

## 🔍 Analytical Workflow (Simulated)

### A. Sentiment & Issue Clustering

Percakapan publik diklasifikasikan ke dalam tiga dimensi utama:

- **Sentiment:** Positive, Neutral, Negative  
- **Topic:** Harga, Layanan, Produk, Kampanye  
- **Brand Mention:**  
  - Deteksi otomatis brand klien  
  - Perbandingan dengan kompetitor (Benchmarking)

---

### B. Early Warning System (EWS)

Sistem mendeteksi anomali dan memberikan **Issue Flag** pada postingan dengan karakteristik:

- **Sentiment:** Negative  
- **Impact:** Reach / Engagement tinggi  
- **Context:** Isu sensitif (contoh: kebocoran data, gangguan layanan masal)

Tujuan utama EWS adalah **memberikan sinyal dini kepada tim PR dan Management** sebelum isu berkembang lebih luas.

---

## 📈 Project Status – Phase 2

### ✅ Completed

- **Data Fabrication:**  
  - Pembuatan **10,000+ data sintesis** yang merepresentasikan perilaku netizen Indonesia (termasuk slang & bahasa informal)
- **Database Schema:**  
  - Finalisasi struktur tabel `social_monitoring` di MySQL
- **Diagnostic SQL Queries:**  
  - Deteksi lonjakan isu harian dan per jam
  - Monitoring tren sentimen negatif

---

### 🟡 Next Milestones

- Finalisasi **Executive Summary Dashboard** di Power BI
- Fine-tuning parameter **LDA** untuk klaster isu yang lebih granular
- Penyusunan **Client-Ready Report** (Weekly & Monthly Reporting Format)

---

## 💡 Strategic Business Value

Insight yang dihasilkan dari sistem ini dapat digunakan untuk:

- **Reputation Evaluation:**  
  Mengukur efektivitas respons PR terhadap isu negatif
- **Campaign Monitoring:**  
  Menilai penerimaan pesan kampanye oleh audiens target
- **Competitor Benchmarking:**  
  Membandingkan kesehatan reputasi brand klien dengan kompetitor utama di industri

---

## ⚠️ Disclaimer

Project ini merupakan **simulasi independen** yang dikembangkan untuk menunjukkan **kompetensi teknis, pemahaman domain, dan workflow industri Media Monitoring**.  
Tidak menggunakan data klien nyata atau data proprietary perusahaan mana pun.
