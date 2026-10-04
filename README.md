 # 🌿 FloraLore — Ethnobotanical AI Assistant
*Where computer vision meets botanical mythology.*

FloraLore is an AI-powered conversational web application that bridges traditional botanical knowledge, folklore, and computer vision. By analyzing photos or descriptions of plants, leaves, and trees, FloraLore generates an Ethnobotanical Dossier detailing scientific taxonomy, cultural and religious symbolism, mythological folklore, and historical medicinal remedies. Users can also dispatch the complete generated dossier directly to their email inbox with a single click.

🌟 Key Features
**Visual Plant Identification:** Upload images (.jpg, .jpeg, .png) of leaves, flowers, or trees for taxonomy analysis.

**Ethnobotanical Dossiers:** Deep dives into historical lore, folklore narratives, indigenous applications, and botanical trivia.

**Interactive Conversational AI:** Built using Google's Gemini 3.5 Flash vision model.

**Automated Email Dispatch:** Direct-to-inbox dispatch powered by Python's native smtplib and Gmail SMTP with TLS/SSL encryption.

**Persistent Session State:** Onboarding screen captures user identity and preserves context across rerun cycles.

🛠️ Tech Stack
 **Frontend / Framework:** Streamlit

**AI and Vision Model:** Google Gemini 3.5 Flash 

**Email Service:** Python smtplib + MIME via Gmail SMTP 

**Environment and Configuration:** Streamlit Secrets Management (secrets.toml)

🚀 Quickstart

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/alex-coder-bot/FloraLore.git](https://github.com/alex-coder-bot/FloraLore.git)
   cd FloraLore
   
2. **Install dependencies:**
Bash
pip install -r requirements.txt

3.**Configure credentials:**
Create .streamlit/secrets.toml:

Ini, TOML
GEMINI_API_KEY = "your-gemini-api-key"
GMAIL_ADDRESS = "your-email@gmail.com"
GMAIL_APP_PASSWORD = "your-16-character-app-password"

4.**Run the app:**
Bash
python -m streamlit run app.py

---

### To push this to GitHub:

1. In VS Code, create a file named `README.md` and paste the above snippet.
2. In PowerShell, push it up:
   ```powershell
   git add README.md
   git commit -m "Add minimal README"
   git push -u origin main
