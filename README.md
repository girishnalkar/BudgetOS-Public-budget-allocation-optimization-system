# 🏦 BudgetOS

**BudgetOS** is an AI-powered district budget intelligence and optimization platform. It helps authorities make data-driven decisions on public spending, track fund leakages, and simulate budget allocations across multiple sectors—ensuring every rupee goes where it's most needed.

---

## ✨ Key Features

- **📊 Dynamic Dataset Upload:** Easily load district health, education, infrastructure, and agriculture data via `.csv`, `.xlsx`, or `.json`.
- **🤖 AI-Powered Analysis:** Leverages **Google Gemini AI** to provide smart, contextual insights and recommend budget reallocations based on District KPIs (HDI, Infant Mortality, Literacy, etc.).
- **💧 Fund Leakage Detection:** Tracks the budget pipeline from District -> Block -> Gram Panchayat -> Beneficiary, identifying bottlenecks, delays, and diversions.
- **📈 Scenario Simulation:** Adjust budgets interactively to see the projected impact on sector health and overall district outcomes.
- **🧑‍💻 Official Data Entry Portal:** A dedicated login portal for field officers and government officials to input live tracking data.

---

## 🛠️ Tech Stack

- **Frontend:** React 19, Vite, Tailwind CSS
- **Charts & Visualization:** Recharts
- **Icons:** Lucide React
- **Data Parsing:** PapaParse (CSV), XLSX (Excel)
- **AI Integration:** Google Gemini API

---

## 🚀 Getting Started

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) (v18+ recommended) installed on your machine.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/girishnalkar/BudgetOS-Public-budget-allocation-optimization-system.git
   cd BudgetOS-main
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up Environment Variables:**
   - Copy `.env.example` to a new file named `.env`:
     ```bash
     cp .env.example .env
     ```
   - Open `.env` and add your **Google Gemini API Key**:
     ```env
     VITE_GEMINI_API_KEY=your_gemini_api_key_here
     ```

### Running the Application

Start the development server:
```bash
npm run dev
```

Open your browser and navigate to `http://localhost:5173/` (or the URL provided in your terminal).

---

## 💡 Usage

1. **Upload Data:** Upon launching, drag and drop your district dataset (`.csv`, `.xlsx`, or `.json`) into the dropzone. Alternatively, click **Use Sample Data** to load pre-configured Maharashtra districts.
2. **Dashboard:** View overall budget distribution, district indicators, and AI-recommended budget shifts.
3. **Pipeline Tracker:** Analyze the flow of funds and identify where money is leaking or getting delayed.
4. **AI Agents:** Consult specialized AI agents (Leakage Agent, Diagnosis Agent, Scenario Agent) for tailored advice.
5. **Scenario Planner:** Experiment with different allocation sliders to see real-time impact simulations.




