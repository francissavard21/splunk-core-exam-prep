# Splunk Core Certified User – Study Notes

These are my personal notes in preparation for the **Splunk Core Certified User exam. Splunk is a platform used for real-time threat detection, log analysis, and performance monitoring across IT environments.

---

## 🔍 What Is Splunk?

- Centralized platform to **collect, process, and analyze data** from systems, networks, and applications
- Primarily used to **detect threats**, **monitor events**, and **investigate incidents**
- Supports **real-time threat detection** for things like malware and unauthorized access
- Can **identify bottlenecks** in high-traffic systems to help improve performance
- Known to be **resource-intensive**, especially in large deployments
- Integrates with **AWS**, **Azure**, and **Google Cloud**

---

## 🧠 Key Concepts

- **SPL** (Search Processing Language):  
  Splunk’s language used to perform searches and manipulate results

- **Search Operators**:
  - `*` – Wildcard; matches any word containing the base
  - `" "` – Quotation marks used for **exact phrase** matches

---

## 📦 Data Flow & Components

- **Data Path**:  
  `Host → Indexer → Index (Buckets) → Search`

- **Indexer**:  
  Stores incoming data into **indexes**, broken down into **buckets**

- **Indexer Clustering**:  
  Multiple indexers can report to an **Indexer Manager** (cluster master)

- **Search Head**:  
  Sends search queries to one or more indexers and compiles results

---

## ✅ What I’m Focusing On

- Understanding how data flows through Splunk architecture
- Writing effective SPL queries using wildcards and phrase matching
- Learning how Splunk supports real-time detection and cloud integrations
- Preparing for exam topics like field extraction, knowledge objects, and dashboards

---

## 📌 Notes

- Certification comes with a **digital badge** upon completion
- Know the difference between **search heads**, **indexers**, and **forwarders**
- Get comfortable identifying and writing basic SPL queries

---

## 📚 Resources
- [Splunk Docs](https://docs.splunk.com/)
- [Splunk Fundamentals Training (Free)](https://www.splunk.com/en_us/training/free-courses/splunk-fundamentals-1.html)
- [TryHackMe - Splunk Room](https://tryhackme.com/room/splunk)
