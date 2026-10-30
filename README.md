# 🎯 Karan B.C.
### Backend Engineer | Focus: High-Throughput Database Layouts & Distributed Systems

I am a software engineer with 3+ years of commercial backend experience specializing in data isolation, query optimization, and transaction safety. My goal is to transition into academic research targeting an M.Sc. in Computer Science with a Graduate Research Assistant (RA) pathway.

---

## 🔬 Core Technical Environment

* **Languages:** PHP, Python, Java, SQL (MySQL, PostgreSQL)
* **Frameworks & Tools:** Laravel MVC, Redis Cluster, Nginx, Git
* **Systems Interest:** Multi-tenancy isolation, asynchronous event queues, performance benchmarking

---

## 🌟 Pinned Projects & Engineering Frameworks

### 🏢 Distributed Multi-Tenant Database Framework
An evaluation setup built to test query performance when using separate database tables per client.
* **The Problem:** Preventing data leaks across client contexts without slowing down the core application routing system.
* **The Result:** Built a dynamic routing engine using Laravel; updated MySQL index layouts and table partitioning to lower read/write latency during heavy, concurrent automated load tests.

### ⚡ High-Precision Billing Queue
An asynchronous processing engine designed to protect ledger histories during high-volume traffic spikes.
* **The Problem:** Preventing database write race conditions and memory locks when thousands of users mutate balance totals simultaneously.
* **The Result:** Implemented a background task queue using Redis to process updates sequentially, and added cryptographically signed webhooks to verify processing boundaries safely.

### 📦 Text Search Engine & Tokenizer
A modular Python text retrieval pipeline built to analyze computational resource boundaries during similarity lookups.
* **The Problem:** Tracking memory usage spikes when matching vocabulary tokens inside structured arrays.
* **The Result:** Built an NLP pipeline with NLTK text processing and Scikit-Learn word arrays. Computed pairwise Cosine Similarity values to sort matching results and logged execution profiles to spot memory bottlenecks.

---

## 📬 Contact & Profiles

* 📧 **Email:** bckaran17@gmail.com
* 💼 **LinkedIn:** https://www.linkedin.com/in/karan-b-c-2162a81b8/
