# LeadPilot AI — Sales Lead Scoring & Qualification

LeadPilot AI is a web application designed to help sales teams prioritize potential customers using machine-learning-based lead scoring. It demonstrates how businesses can organize leads, estimate their priority, and focus their follow-up efforts.

## 🚀 Live Demo

**Live Application:** [Try LeadPilot AI](https://lead-pilot-ai-lead-scoring--pjyaswanth2005.replit.app/)

**GitHub Repository:** [LeadPilot AI on GitHub](https://github.com/Yaswanthpothula/LeadPilot-AI-Sales-Lead-Scoring-App)

## 💼 Business Use Case

Sales teams often receive more leads than they can follow up with immediately. LeadPilot AI demonstrates a way to categorize leads by predicted priority, helping sales representatives organize their workflow.

Potential business applications include:
- Prioritizing leads for sales follow-up.
- Identifying high-, medium-, and low-priority prospects.
- Processing multiple leads from CSV files.
- Reviewing and exporting scored lead lists.

## ✨ Features

- **Lead Scoring:** Generate a model-based score for submitted leads.
- **Priority Classification:** Group leads into high, medium, and low categories.
- **CSV Upload:** Process multiple leads in a batch.
- **CSV Export:** Download scored lead results for further analysis.
- **Interactive Dashboard:** Review lead information and scoring results.
- **Sample Data:** Explore the workflow using example leads.

## 🛠️ Tech Stack

- **Language:** Python
- **Backend:** Flask
- **Machine Learning:** Scikit-learn, Random Forest
- **Data Processing:** Pandas, NumPy
- **Frontend:** HTML, CSS
- **Deployment:** Replit

## ⚙️ Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/Yaswanthpothula/LeadPilot-AI-Sales-Lead-Scoring-App.git
cd LeadPilot-AI-Sales-Lead-Scoring-App
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Start the application

If `app.py` is the Flask entry point:

```bash
python app.py
```

Open the local URL printed by Flask in your browser, usually `http://127.0.0.1:5000`.

## 🧪 Machine Learning Note

The current demonstration uses synthetic sample data to train its model. The generated scores illustrate a lead-prioritization workflow and should not be treated as validated predictions of real customer conversion or sales revenue. Real-world use would require representative business data, model evaluation, and calibration.

## 🔮 Future Improvements

- Train and evaluate the model using real, appropriately authorized sales data.
- Add customer relationship management (CRM) integrations.
- Track follow-up outcomes and lead conversion rates.
- Add authentication and persistent database storage.
- Monitor model performance and prediction quality.

## 👨‍💻 Author

**Yaswanth Pothula**

Software Developer | Python | Flask | Machine Learning | Full Stack Development

---

*This project is an educational and portfolio demonstration of machine learning applied to a practical business workflow.*
