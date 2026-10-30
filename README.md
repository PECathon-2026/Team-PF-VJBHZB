# 🌐 Small Web Reader

> A minimalist, privacy-first RSS and independent web reader built for the open web. Designed for speed, zero-tracking discovery, and offline readability.

---

## ✨ Core Features

* **📰 RSS Autodiscovery & Parsing:** Instantly parse and subscribe to any independent blog, newsletter, or RSS feed with clean URL normalization.
* **📖 Full-Article Extraction:** Integrated Mozilla Readability parsing to extract and clean full article content directly on the client side.
* **🧭 Anonymous Co-Subscription Discovery:** Decentralized recommendations computed anonymously using the **Jaccard Similarity index** ($J(A, B) = \frac{|A \cap B|}{|A \cup B|}$) across reader subscription sets without user tracking.
* **💾 Local-First Storage:** High-performance client-side data persistence using IndexedDB (via `idb`) for offline bookmarking and reading states.
* **🛡️ Feed Integrity Audit:** Built-in auditing tool to catch malformed XML, duplicate feeds, and dead or unreachable endpoints.

---

## 🛠️ Tech Stack

* **Framework:** Next.js 14 (App Router, Client-side rendering)
* **Styling:** Tailwind CSS & Lucide Icons
* **Language:** TypeScript
* **Storage:** IndexedDB (`idb`)
* **Parsing Utilities:** `@mozilla/readability` & `DOMPurify`

---

## 🚀 Getting Started Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/PECathon-2026/Team-PF-VJHBZB.git](https://github.com/PECathon-2026/Team-PF-VJHBZB.git)
   cd small-web-reader
