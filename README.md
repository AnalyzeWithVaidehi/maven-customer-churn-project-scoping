# 📉 Maven Music Project Scoping: Translating Customer Churn into a Supervised Learning Strategy

## 👋 Meet the Analyst

Hi, I'm **Vaidehi**! I am a **Data Analyst** specializing in bridging the gap between raw data chaos and clean, reliable business strategies. With a background in computer science and digital marketing analytics, I don't just look at data as numbers in a grid—I look at it as a map of customer behavior and operational health.

* **🛠 My Tech Stack:** Excel, Power BI/Tableau, SQL (Window Functions, CTEs, Complex Joins) and Python (Pandas, Numpy, Matplotlib, Seaborn).
* **🎯 My Philosophy:** A model or dashboard is only as good as the scoping behind it. Before writing a single line of SQL or Python, I focus heavily on product thinking, stakeholder alignment, and defining clear metric boundaries to ensure data projects solve real business problems.
* **📬 Connect with Me:** [linkedin](https://www.linkedin.com/in/vaidehibharambeaulagar) | vaidehibh@gmail.com

---

## 📌 Project Overview: Why this project?

**Maven Music** is a streaming service that has been experiencing a worrying trend: they are losing more customers than usual, causing their **monthly revenue growth to slow down significantly**. If an analyst immediately jumps into writing code or building models without understanding this friction, they risk wasting weeks solving the wrong problem. 

* **My Mission:** Step in as the junior data analyst to systematically scope this data science project. I translated a broad business anxiety (*"we are losing revenue"*) into a precise, structured supervised learning architecture with a clearly defined timeline and measurable objectives.

---

## 🔍 The Scoping Framework: Core Decisions & Mapping

Project scoping requires moving systematically from stakeholder conversations to data constraints. I tracked every strategic decision, feasibility check, and structural layout to build an actionable blueprint. Here are the core alignment pillars I established:

### 1. Stakeholder Empathy & Metric Alignment
Through discovery conversations with the business end-users, I uncovered the true definition of success. The retention team doesn't just want a fancy machine learning model; they want to protect the company's bottom line. We established our **"Guiding Star" objective: reduce total customer cancellations by 2% over the next fiscal year.**

### 2. Problem Root-Cause Ideation
Before looking at rows and columns, I mapped out potential business friction points causing customer opt-outs to guide future feature engineering:
* **Price Elasticity:** Subscription price updates and recent plan changes.
* **Product Friction:** Technical platform performance issues or user interface bugs.
* **Content Limits:** Stagnant library growth or a small indie artist catalog.
* **Acquisition Quality:** Aggressive marketing campaigns targeting short-term, discount-reliant users.

### 3. Supervised Learning Schema Setup
Because we are leveraging historical data to isolate past behaviors that predict a known, clear outcome (whether a user stayed or left), I explicitly structured this as a **Supervised Learning problem**. 

> 🔹 **X Variables = Inputs = Features:** The customer behavioral patterns we feed the model.
> 🔸 **Y Variable = Output = Target Label:** The explicit business outcome we want to predict (`Cancelled?`).

| Customer | Months Active <br>*(X Feature)* | Monthly Payment <br>*(X Feature)* | Listened to Indie Artists? <br>*(X Feature)* | Cancelled? <br>*(Y Target Label)* |
| :--- | :---: | :---: | :---: | :---: |
| **Aria** | 25 | $9.99 | Yes | **No** |
| **Chord** | 2 | $0 | No | **No** |
| **Melody** | 14 | $14.99 | No | **Yes** |

### 4. Data Feasibility & Source Auditing
To ensure a rapid deployment, I conducted a data accessibility check. Instead of chasing external metrics that are difficult or expensive to pull, I prioritized immediate internal value:

| Features | Potential Sources | Ease of Access | MVP Status |
| :--- | :--- | :--- | :--- |
| • Monthly rate <br>• Auto-renew flag | Customer subscription & billing history | 🟢 **Easy** *(Internal Warehouse)* | **IN SCOPE** |
| • Age <br>• Urban vs. Rural location | Customer account registration details | 🟢 **Easy** *(Internal Warehouse)* | **IN SCOPE** |
| • Competitor Promotional History | External market subscription trackers | 🔴 **Hard** *(External Data)* | **OUT OF SCOPE** |

---

## 💡 Key Takeaways: My Core Scoping Philosophy

Project scoping is where an analyst proves they can think like a business strategist, not just a programmer. Through this framework, I prioritize four main pillars:

* **Empathy Over Algorithms:** A successful project doesn't start with raw data; it starts with the end user. By focusing entirely on stakeholder pain points and aligning on a 2% reduction objective before looking at the database, I ensure the analytical workflow delivers direct business value.
* **Brainstorm Big, Execute Focused:** Effective brainstorming requires zero limitations initially. I explicitly map out a wide range of ideas—knowing that many solutions don't even require data science—and then intentionally narrow them down to keep engineering resources focused.
* **Architectural Clarity:** Understanding data structure is vital before writing code. For this supervised learning strategy, identifying the target label (`Cancelled?`) up front is essential for formatting rows into historical ground truths, a step that would be entirely absent in an unsupervised clustering approach.
* **The MVP Approach:** Data complexity can easily derail deadlines. By starting with a lean, 3-month lookback period on active subscribers as a Minimum Viable Product (MVP), I establish a rapid feedback loop with stakeholders before choosing to onboard larger, more complex data streams.

---

## 🚀 Future-Proofing: Managing Scope Creep & Scaling

Going too deep into a data science project without early feedback often leads down an unproductive path or results in over-complicating the technical solution. If I were executing this pipeline on the job, I would manage delivery risks using these guardrails:

* **Minimum Viable Product (MVP) Boundaries:** I restricted the initial scope to evaluate a clean, 3-month lookback period focusing exclusively on customers who are actively subscribed. This gives the marketing team an immediate, highly relevant window of behavior to test.
* **Iterative Scaling Strategy:** If the model's predictive strength on this initial 3-month subset doesn't meet stakeholder expectations, I would scale up the framework systematically—expanding to longer historical cohorts or onboarding secondary demographic datasets—rather than over-engineering features on day one.

---

## 📂 What’s Inside This Repository?

* 📁 data/maven.db
*  |---------/maven_music_cutomers.csv
*  |---------/maven_music_listening_history.xlsx: Raw data files
* 📄 `README.md`: The strategic operational blueprint summarizing the business goals and data boundaries.
* 📄`My Thought Process.pdf`: File that contains what was I thinking during the scoping of the project.
---

## 💡 What's next? 
Now that the project boundaries, data schemas, and the 2% cancellation reduction goal are locked in, my next sprint is gathering the raw Maven Music customer records in Python, performing rigorous data cleaning, and launching the **Exploratory Data Analysis (EDA)**!
