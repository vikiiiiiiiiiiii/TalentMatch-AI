# 🏆 TalentMatch AI: Intelligent Candidate Discovery Engine

Developed for the **Data & AI Challenge Track**.  
An advanced, production-grade automated recruitment pipeline that replaces traditional, fragile keyword-matching systems with **Deep Semantic Text Vector Embeddings** and **Multi-Signal Behavioral Telemetry**.

---

## 🚀 Our Core USP: Dual-Gate Hybrid Scoring

Legacy Applicant Tracking Systems (ATS) fail by blindly matching exact character string keywords, which makes them vulnerable to **keyword stuffing** from unqualified profiles while completely missing high-quality candidates who use synonymous phrasing. 

**TalentMatch AI** defeats this bottleneck by engineering a two-tier mathematical evaluation matrix:
1. **Tier 1: Deep Semantic Intent Mapping (70% Weight):** Uses state-of-the-art sentence transformers (`all-MiniLM-L6-v2`) to capture context, nuances, and functional skill meanings across 100,000 raw profile text lines.
2. **Tier 2: Live Behavioral Telemetry Boosting (30% Weight):** Fuses engagement metadata fields (`redrob_signals`) into the final score to prioritize candidates who are actively on the platform, highly responsive, and immediately available in the job market.

---

## 🛠️ The System Architecture Pipeline

To safely process **100,000 candidate records** in under 60 seconds without triggering memory overflow or system timeouts in cloud environments, our engine implements a high-performance **Two-Stage Retrieval Framework**:

1. **Stage 1 (Fast Linear Downscaling):** Flattens nested unstructured arrays (skills, profile definitions, metadata blocks) safely and runs an optimized boolean indicator scan to reduce the data footprint from 100,000 down to a concentrated pool of 2,000 high-potential profiles.
2. **Stage 2 (Dense Semantic Evaluation Matrix):** Vectorizes the remaining pool, calculates cosine similarities against structural job requirements, normalizes active behavioral engagement vectors, and aggregates a definitive, non-increasing sorting rank.
3. **Stage 3 (Dynamic Logic Synthesis):** Generates automated, context-specific textual explanations detailing exactly why each candidate fits the role requirements for human recruiter review.

---

## 📦 File Structures & Deliverables

* `TalentMatch_AI.ipynb`: The complete, fully commented, out-of-the-box executable notebook script.
* `team_talentmatch_ai_submission.csv`: The definitive output file containing **exactly 100 rows** structured precisely in the required schema (`candidate_id,rank,score,reasoning`).
* `TalentMatch_AI_Presentation_Deck.pdf`: Explanatory approach slide deck.

---

## ⚡ How to Run locally / in Colab

1. Open a new notebook instance in [Google Colab](https://colab.research.google.com/).
2. Drag and drop your raw hackathon zip data file (`India_runs_data_and_ai_challenge DATA.zip`) straight into the left Files pane.
3. Upload and execute the `TalentMatch_AI.ipynb` file sequentially. 
4. The script will automatically unpack the nested cloud layers, process the dataset entries, handle unstructured dictionaries gracefully, and compile the final submission file in under 1 minute.
