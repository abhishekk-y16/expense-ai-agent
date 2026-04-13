# Expense-AI-Agent 🤖💸  

An AI-powered automation built Using [n8n](https://n8n.io/) that captures Expense details From  a **Telegram bot** and Logs them into an **Excel sheet** — Smartly Extracting  Insights Using the **Gemini API**.     

![Workflow Screenshot](Screenshot.jpg) 

## 🚀 What It Does    

Whenever a User Sends an Expense Message via Telegram (e.g., `₹200 Lunch at Subway` or `Cab - ₹450`), this AI agent:  

1. Uses **Gemini API** to Extract and Interpret:  
   - **Amount**
   - **Item** 
   - **Category** (e.g., Food, Travel, Entertainment)  
   - **Description** 
   - **Date** (or Assigns the Current Timestamp if Missing)  

2.  Writes the Parsed Data into an Excel File with the following structure:    
   `Date | Item | Amount | Category | Description`

✅ Supports Messages with Currency Symbols  
✅ Intelligently categorizes expenses using Gemini  
✅ Uses Current Timestamp When Date is Missing   

---

## 🛠️ Setup Instructions👇 

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/expense-ai-agent.git
2. Open [n8n](https://n8n.io/) and import the provided .json workflow.
3. Configure the Node with the required credentials.
4. Deploy the workflow and test it by sending an expense message to your Telegram bot. Your Excel sheet should update instantly!  

## 🙌 Contribute
Feel free to fork this project, Improve the Logic,or add New features like multi-user support, analytics dashboard, or budget alerts. PRs are welcome!  

