# ☎️ Call Centre Performance Dashboard (Power BI)

## 📁 Project Overview
The **Call Centre Performance Dashboard** is an interactive **Power BI report** designed to monitor and evaluate customer service efficiency through key performance indicators such as total calls, call durations, response times, and sentiment analysis.  
It provides a comprehensive view of call centre operations to help management make data-driven decisions and improve customer satisfaction.

---

## 🎯 Objective
The goal of this dashboard is to:
- Analyze overall **call volume**, **duration**, and **response performance**.  
- Track **SLA compliance** across different channels (Call, Email, Chatbot, Web).  
- Understand **customer sentiment** and common **reasons for contact**.  
- Provide insights into **agent productivity** and **regional call distribution**.

---

## 🗂️ Dataset Details
**File Used:** `call_centre_data.xlsx` (example dataset)  

**Key Columns:**
- **Id** – Unique call identifier  
- **Customer Name** – Name of the customer who made the call  
- **Channel** – Communication channel (Call-Centre, Email, Chatbot, Web)  
- **State / City** – Location of the customer or call centre  
- **Reason** – Purpose of the call (Billing Question, Payments, Service Outage, etc.)  
- **Response Time** – SLA compliance (Within SLA, Above SLA, Below SLA)  
- **Total Call Duration (mins)** – Duration of each call  
- **Sentiment** – Customer sentiment (Positive, Neutral, Negative, etc.)  
- **Date** – Date of call  

---

## 📊 Dashboard Features

### 🔹 Key Metrics (KPIs)
- **Total Calls:** 33K  
- **Total Call Duration (mins):** 824K  
- **Total Call Duration (hours):** 13.74K  
- **Average Call Duration (mins):** 25.02  
- **Response Time %:** 75.26%

### 🔹 Visual Insights
#### 📅 Home Page Overview
- **Total Calls by Day** – Trend of daily call volumes  
- **Total Calls by State** – Geographic distribution of calls across the US  
- **Total Calls by Reason** – Major customer issues (Billing, Payments, Outage)  
- **Total Calls by Channel** – Communication mode analysis (Call-Centre, Email, Chatbot, Web)  
- **Total Calls by Sentiment** – Customer satisfaction trends  
- **Total Calls by Call-Centre City** – Top performing or busy centres  

#### 🧾 Grid View
- Detailed record table showing all customer interactions with attributes like:
  - Customer name, channel, state, reason, response time, and total duration  
- Useful for **drill-down analysis** and data validation  

### 🔹 Filters / Slicers
Interactive filters for:
- Date  
- Channel  
- Call Centre City  

These enable users to dynamically explore call data and view trends from multiple perspectives.

---

## 💡 Key Insights
- **Billing Questions** are the most common reason for customer calls.  
- **Los Angeles** and **Baltimore** are the busiest call centres with 13.7K and 11K calls respectively.  
- Around **75% of calls** were responded to **within SLA**, indicating good efficiency but room for improvement.  
- **Negative sentiment** is the most frequent, showing opportunities to enhance customer experience.  
- Average call duration remains consistent at **~25 minutes**, suggesting stable call handling times.

---

## 🛠️ Tools & Technologies
- **Power BI Desktop** – For data modeling and visualization  
- **Microsoft Excel** – Data preparation and cleaning  
- **DAX (Data Analysis Expressions)** – KPI calculations and dynamic measures  
- **Power Query** – Data transformation and preprocessing  

---

## 🚀 How to Use
1. Download the repository.  
2. Open the `.pbix` file in **Power BI Desktop**.  
3. Load or connect the dataset (`call_centre_data.xlsx`).  
4. Refresh data connections to update visuals.  
5. Interact with filters and explore insights in **Home** and **Grid** pages.

---

## 📚 Learning Outcomes
From this project, I learned:
- **Building multi-page dashboards** with interactive navigation  
- **Designing KPI cards and drill-down visualizations**  
- **Creating geographic visualizations** using map visuals  
- **Applying Power BI themes and layout consistency** for a professional design  

---

## 🧠 Future Enhancements
- Connect live data from **CRM or telephony systems (e.g., Twilio, Zendesk)**  
- Add **agent performance tracking and leaderboards**  
- Incorporate **AI sentiment scoring** for deeper insights  
- Create **automated reports** for weekly performance summaries  

---

## 📷 Dashboard Previews

### 🏠 Home View
<img width="1410" height="791" alt="image" src="https://github.com/user-attachments/assets/a775e3e4-0fb6-49ae-8a3c-9f9cb873b2fb" />


### 🧾 Grid View
<img width="1411" height="793" alt="image" src="https://github.com/user-attachments/assets/e42153c3-7dda-49f5-974b-37b61a595125" />


---

## 👩‍💻 Author
**Nanditha Gooty**  
