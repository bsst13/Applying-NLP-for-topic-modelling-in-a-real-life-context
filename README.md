# NLP Insights: Decoding Customer Dissatisfaction at Scale

## 🏋️ The Business Challenge
In a high-volume business like a fitness chain, manual review reading is impossible. This project automates the detection of "Why customers leave" by analyzing thousands of reviews to find the signal in the noise.

## 🧠 The Technical Approach: A Dual-Model Pipeline
I utilized two different modeling approaches to ensure no detail was missed:
1. **BERTopic:** For deep contextual understanding of customer emotions.
2. **LDA (Gensim):** To extract specific, granular keywords (like 'ventilation' or 'music volume') that BERTopic might overlook.

## 📍 Identifying the "Crisis Locations"
By cross-referencing **Sentiment Intensity** with **Topic Frequency**, I mapped out the Top 30 locations requiring immediate intervention. 

## 💡 Top 3 Recommendations
* **Facility Maintenance:** Analysis showed high anger regarding "Ventilation" and "Broken Equipment" in key zones.
* **Staffing Pilot:** Identified "Management presence" as a recurring theme in mid-tier locations.
* **In-Gym Experience:** Recommendations for Wi-Fi and Music adjustments based on specific location clusters.
