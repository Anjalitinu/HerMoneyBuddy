HerMoney Buddy 💖
AI Financial Advisor Chatbot for Women
HerMoney Buddy is a beginner-friendly financial chatbot empowering women with personalized investment and loan recommendations. Built for a 9-hour girls-only hackathon, it compares SIPs, FDs, PPF, loans, and more using live APIs with cute UI/UX!

✨ Tech Stack
text
Frontend: Streamlit (Python)
Backend: Python 3.12
Data: MFAPI.in, MetalPriceAPI (live rates)
Libraries: pandas, numpy, requests
Deployment: Streamlit Cloud + GitHub
🚀 Features
 Smart Investment Comparison - Compares SIP, FD, PPF, Gold, Stocks, NPS based on risk/goal

 Loan EMI Calculator - Home, Personal, Gold, Vehicle, Education loans with real rates

 Live Market Data - Real mutual fund NAVs + gold prices via free APIs

 Personalized Scoring - AI-like recommendations (amount, risk tolerance, liquidity)

 Encouraging UX - Beginner-friendly with pink gradients, hearts, balloons 🎉

 Mobile Responsive - Works on phone for hackathon demos

🛠️ Installation
bash
# Clone repo
git clone https://github.com/YOURUSERNAME/hermoney-buddy.git
cd hermoney-buddy

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
# venv\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt
▶️ Run Locally
bash
streamlit run app.py
Opens: http://localhost:8501

📱 Screenshots
Add these: Take screenshots of your running app → drag into screenshots/ folder



🔗 API Documentation
API	Endpoint	Data
Mutual Funds	https://api.mfapi.in/mf/1	NAV, returns
Gold Prices	https://api.metalpriceapi.com/v1/latest	Live XAU-INR
FD Rates	Hardcoded (SBI: 6.5%)	Quarterly update
👩‍💻 Team
Name	      Role
Anjali Tinu	UI/UX + Deployment, Styling + Content
Alaina Raju	APIs + Logic, Bug fixing + Demo

📄 License
text
MIT License - Free to use, modify, deploy anywhere!
Copyright (c) 2026 HerMoney Buddy Team


Live URL: https://hermoney-buddy.streamlit.app

