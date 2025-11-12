# 🎓 Big Data Capstone Project  
## Player Behaviour Analysis and In-Game Personalisation Using Big Data  
**Author:** D. Harish Naik  
**Roll No:** 24MBMB33  
**Program:** MBA – Business Analytics, HCU  

---

## 🧠 Project Overview
This project demonstrates how **Big Data technologies** and **AI-driven analytics** can be applied in the gaming industry to enhance **player engagement, retention, and monetization**.  
The goal is to analyze player behaviour data — such as **Game Genre**, **Engagement Level**, and **Purchase History** — to generate **personalized in-game experiences** through data-driven insights.

---

## 🎯 Objectives
- To process and analyze large-scale player data using **Big Data frameworks**.  
- To design an **ETL pipeline** that efficiently extracts, transforms, and loads behavioural data.  
- To apply **AI and ML models** for dynamic personalization and player retention.  
- To implement **MLflow tracking** for experiment management and reproducibility.  
- To derive **actionable insights** for personalization, difficulty adjustment, and player churn reduction.

---

## ⚙️ Technical Architecture

### 🧱 ETL Pipeline
The data pipeline is structured into three key stages using **PySpark**:
1. **Extract:** Import raw player data (PlayerID, Game Genre, Engagement Level, and Purchases).  
2. **Transform:**  
   - Clean and preprocess datasets using PySpark DataFrames.  
   - Handle null values and normalize categorical fields.  
   - Merge datasets to create a unified analytics view.  
3. **Load:** Store transformed data in a structured format suitable for downstream analytics.

This process ensures scalability and reliability for high-volume gaming data.

---

## 🧩 Machine Learning & Experiment Tracking
After the ETL process, **MLflow** is used to:
- Track model versions, parameters, and metrics.  
- Compare model performance for personalization and churn prediction tasks.  
- Maintain experiment reproducibility and lifecycle management.  

This integration of **PySpark** and **MLflow** enables distributed computation and seamless model evaluation in real-world Big Data environments.

---

## 🧰 Tools & Technologies Used
| Category | Tools / Libraries |
|-----------|------------------|
| Programming Language | Python |
| Big Data Framework | PySpark |
| ML Experiment Tracking | MLflow |
| Data Environment | Jupyter Notebook |
| Data Storage | CSV / DataFrame Structures |
| Visualization | Matplotlib, PySpark Display Functions |

---

## 📊 Dataset Description
| Feature | Description |
|----------|-------------|
| PlayerID | Unique identifier for each player |
| GameGenre | Type of game (e.g., Sports, RPG, Simulation, Strategy) |
| EngagementLevel | Low, Medium, or High engagement |
| PlayerLevel | Skill or experience level of player |
| PurchaseHistory | Number of in-game purchases |
| SessionsPerWeek | Weekly gaming activity |
| DifficultyLevel | Current game difficulty mode |

---

## 💡 Use Cases & Insights

### 🕹️ Use Case 1: Player Weapon Recommendation Insights
- High-engagement players (Sports, Strategy) → Advanced weapons (*Top-Tier Gear Set*, *Advanced Mine Layer*).  
- Medium-engagement players → Balanced weapons (*Assault Rifle*, *Strategic Drone Strike*).  
- Low-engagement players (RPG, Simulation) → Basic tools (*Healing Potion Bundle*, *Starter Kit*).  
**Insight:** Weapon complexity increases with engagement and genre intensity.

---

### 🎁 Use Case 2: AI-Based Player Reward Personalization
- High-engagement → Premium rewards (*Elite Spender Pack*, *Advanced Rifle Blueprint*).  
- Medium-engagement → Retention-based rewards (*Daily Login Crate*).  
- Low-engagement → Motivation rewards (*Tutorial Completion Quest*).  
**Insight:** AI maintains engagement by tailoring rewards to player type.

---

### ⚖️ Use Case 3: Dynamic Difficulty Adjustment
- Low-level players on Hard Mode → **Decrease difficulty** to Medium.  
- High-level players on Easy Mode → **Increase difficulty** to Medium.  
**Insight:** AI automatically balances challenge and satisfaction.

---

### 🛒 Use Case 4: AI-Triggered Contextual Offers
- Non-spending players receive limited-time offers (*50% Off Gear*).  
- Active spenders do not get discounts.  
**Insight:** AI triggers offers only when conversion probability is high — maximizing revenue.

---

### 🔁 Use Case 5: AI-Driven Player Retention Strategy
- Low-risk players → Standard check-ins.  
- Medium-risk → Engagement messages.  
- High-risk → Proactive reactivation rewards (*Free Perks*).  
**Insight:** Retention interventions are personalized based on churn probability.

---

## 📈 Analytical Results
- **Improved player retention rates** through personalized incentives.  
- **Balanced difficulty levels** enhanced player satisfaction.  
- **Optimized reward distribution** minimized churn risk and increased loyalty.  
- **Targeted offer timing** increased conversion efficiency and profitability.  

---

## 🧩 Challenges Encountered
- Managing **data imbalance** between low and high-engagement players.  
- Ensuring **ETL pipeline performance** under large data loads.  
- Hyperparameter tuning for ML models.  
- Maintaining consistent **tracking and version control** across experiments.

---

## 🎓 Key Learnings
- Efficient use of **PySpark** for distributed data transformation.  
- Experiment management through **MLflow** improves traceability.  
- The value of **data-driven personalization** in improving user experience.  
- Importance of integrating **ETL, AI, and business insights** for scalable analytics.

---

## 📚 Future Scope
- Integration with **real-time streaming** systems for live personalization.  
- Use of **deep learning models** for advanced behavioural prediction.  
- Deployment on **cloud-based Big Data platforms** for scalability.  
- Expansion to **multi-game environments** with cross-platform analytics.

---

## 🏁 Conclusion
This project successfully demonstrates how **Big Data analytics and AI personalization** can transform the gaming industry.  
By integrating **PySpark ETL pipelines**, **MLflow experiment tracking**, and **AI-based personalization models**, it delivers a scalable framework that enhances **player satisfaction, engagement, and revenue**.

---

## 🙏 Acknowledgements
I would like to express my gratitude to my faculty and mentors from the **MBA Business Analytics Program at HCU** for their continuous support and guidance throughout this project.

---

## 📂 Repository Structure
