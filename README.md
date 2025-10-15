#🩺 Healthcare Symptom Checker#
🎯 Objective
This project is an educational healthcare assistant that takes user-entered symptoms as input and returns probable conditions and recommended next steps.
⚠️ Disclaimer: This tool is for educational purposes only and not a substitute for professional medical advice, diagnosis, or treatment.

🧠 Features
Accepts symptom input (e.g., "fever, cough, fatigue")
Returns:
Possible medical conditions (with confidence %)
Triage and next-step recommendations
Red-flag alerts (if any)
Provides structured and explainable results
Optional input fields: age, sex, comorbidities
Built with Groq LLM API + Gradio UI

⚙️ Tech Stack
Component	Technology
Backend	Python, Requests, Groq API
Frontend	Gradio (interactive web interface)
LLM Model	llama-3.3-70b-versatile
Environment	Jupyter Notebook / Colab
📦 Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/<your-username>/healthcare-symptom-checker.git
cd healthcare-symptom-checker
2️⃣ Install Dependencies
pip install -r requirements.txt
(or manually install if you don’t have requirements.txt)
pip install requests gradio
3️⃣ Run the Application
python symptom_checker.py
4️⃣ Enter your Groq API Key
You will be prompted to enter your Groq API key.
Obtain it from https://console.groq.com
5️⃣ Access the Web App
Once started, a Gradio interface link (like https://xxxx.gradio.live) will open automatically in your browser.

Input:
Symptoms: sore throat, mild fever, fatigue
Age: 23
Sex: Female
Comorbidities: None

Output Example:
🩺 Healthcare Symptom Checker Results
Disclaimer: This response is for educational purposes only and should not be considered a diagnosis or medical advice. 
If symptoms worsen or red flag symptoms appear, seek urgent medical care.
🔎 Possible Conditions
- Viral pharyngitis (60%) — The combination of sore throat, mild fever, and fatigue could be indicative of a viral infection, such as a common cold or mononucleosis.  
- Strep throat (20%) — The presence of a sore throat and mild fever could also suggest a bacterial infection like strep throat, although this is less likely without additional symptoms such as swollen lymph nodes or a rash.  
- Influenza (10%) — Fatigue and mild fever could be symptoms of the flu, especially during peak season, but the absence of other flu-like symptoms such as cough or body aches makes this less likely.  
- Tonsillitis (10%) — The sore throat could be due to tonsillitis, which can be caused by either a viral or bacterial infection, but without more specific symptoms such as swollen tonsils, this is less likely.
🧭 Triage Advice
Self-care and monitoring
🚨 Red Flags
Difficulty swallowing, Severe headache, High fever (over 103°F), Shortness of breath, Severe fatigue lasting more than a week

📄 Deliverables
✅ GitHub Repository (this project)
✅ README with setup & usage
✅ Demo video (upload link here when ready)

🧩 Evaluation Focus
Criterion	Description
Correctness	Functional symptom-to-condition output
LLM Reasoning	Logical, probabilistic suggestions
Safety	Includes disclaimer & red-flag handling
Code Design	Modular, readable, and API-driven

💡 Future Enhancements
Add a database to store user queries/history
Improve UI styling with more interactivity
Integrate visualization of symptom-condition relationships
Support multilingual input

👩‍💻 Author
Divya Thorlikonda

⚠️ Disclaimer
This project is strictly educational and does not provide medical diagnoses or treatments.
Always consult a certified healthcare professional for medical concerns.
