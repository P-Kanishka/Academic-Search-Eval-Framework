# 📊 Academic Search Engine Evaluation Framework

**📅 Project Type:** Graduate Research (University of South Dakota)
**🧪 Methodology:** Quantitative Analysis, Weighted Scoring, Mean Reciprocal Rank (MRR)
**📚 Domain:** Information Retrieval (IR) & Data Analytics

### 📖 Project Overview
Ranking academic search engines is complex due to varying database sizes, indexing algorithms, and user interface capabilities. This project proposes a **novel quantitative framework** to benchmark search engines like **Google Scholar**, **BASE**, and **The Lens**.

[cite_start]Unlike subjective reviews, this framework utilizes a **"10-Point Scale"** system that assigns weighted scores to key performance indicators (KPIs), providing a data-driven ranking of retrieval effectiveness.

### 📐 The 10-Point Scoring Model
[cite_start]The framework evaluates engines based on a weighted sum of parameters:

$$Score_{total} = \sum (W_i \times P_i)$$

Where $W$ is the weight of the parameter and $P$ is the performance score. Key metrics include:
* **Relevance & Precision:** How accurate are the top-k results?
* [cite_start]**Time-Based Mean Reciprocal Rank (MRR):** Measures the speed and rank accuracy of retrieving specific documents.
* [cite_start]**Database Coverage:** Size of the index (e.g., Google Scholar vs. BASE).
* **User Experience (UX):** Interface latency and advanced filtering capabilities.

### 🔬 Key Findings
* [cite_start]**Google Scholar** consistently ranked highest for **recall**, leveraging its massive crawl database.
* [cite_start]**BASE (Bielefeld Academic Search Engine)** performed well in **open-access filtering** but lagged in raw relevance ranking for obscure queries.
* [cite_start]**The Lens** offered superior visualization tools for citation networks but had a smaller total index size.

### 📄 Research Documentation
The full paper, detailing the mathematical scoring model and comparative analysis, is available here:
[View Full Research Paper](./10_Point_Scale_for_Evaluating_Academic_Search_Engines.pdf)

### 📚 Selected Bibliography
This research built upon foundational Information Retrieval texts:
1.  [cite_start]*Search Engines: Information Retrieval in Practice* - Croft, Metzler, & Strohman[cite: 5].
2.  [cite_start]*Google Scholar to overshadow them all?* - Michael Gusenbauer (Scientometrics)[cite: 6].
3.  *Towards Better Understanding of Academic Search* - Khabsa et al. (Microsoft Research) [cite_start][cite: 4].
