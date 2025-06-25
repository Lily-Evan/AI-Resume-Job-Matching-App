# AI-Resume-Job-Matching-App
SmartCV – AI-Powered Resume Analyzer &amp; Job Matcher
# 💼 SmartCV – AI-Powered Resume Analyzer & Job Matcher

**SmartCV** είναι μια έξυπνη web εφαρμογή που βοηθά τους χρήστες να βελτιώσουν το βιογραφικό τους, να εντοπίσουν κατάλληλες θέσεις εργασίας και να λάβουν προσωποποιημένες συμβουλές με τη βοήθεια τεχνητής νοημοσύνης.

---

## 🎯 Main Features

### 1. 📄 Resume Upload & Analysis
- Υποστήριξη για PDF, DOC, και DOCX με drag-and-drop interface
- Χρήση Google Gemini 1.5 για parsing βιογραφικών
- Εξαγωγή πληροφοριών: δεξιότητες, εμπειρία, σπουδές, επιτεύγματα
- Καθαρό, φιλικό περιβάλλον χρήστη

### 2. 🧠 Smart Job Matching
- Ανάλυση συμβατότητας μεταξύ βιογραφικού και αγγελιών
- Υπολογισμός ποσοστού αντιστοιχίας (0–100%) ανά θέση
- Εμφάνιση αντιστοιχισμένων και ελλιπών δεξιοτήτων
- Εξατομικευμένες AI συστάσεις για κάθε θέση

### 3. 📊 Interactive Dashboard
- Τρεις βασικές ενότητες: Resume Upload, Job Matches, Available Jobs
- Χρωματικός δείκτης αντιστοιχίας (π.χ., κόκκινο – χαμηλή, πράσινο – υψηλή)
- Job cards με περιγραφή και απαιτήσεις θέσης
- Responsive σχεδίαση για mobile & desktop

### 4. 🤖 AI-Powered Insights
- **Matching Skills**: Ταυτοποιημένες δεξιότητες από το βιογραφικό
- **Skills to Develop**: Δεξιότητες που απαιτούνται για καλύτερη αντιστοιχία
- **AI Recommendations**: Προσωποποιημένες προτάσεις
- **Match Scoring**: Σύστημα αξιολόγησης job fit

---

## 🔧 How It Works

1. **Upload**: Ο χρήστης ανεβάζει το αρχείο του (βιογραφικό)
2. **Analyze**: Το μοντέλο Google Gemini 1.5 αναλύει το περιεχόμενο
3. **Match**: Η AI συγκρίνει τα δεδομένα με αγγελίες εργασίας
4. **Result**: Προβάλλονται τα αποτελέσματα με visual insights & συστάσεις

---

## 📊 Sample Data

Η εφαρμογή περιλαμβάνει δείγμα αγγελιών για δοκιμές:

- 👨‍💻 Senior Software Engineer (TechCorp)
- 📈 Data Scientist (DataFlow Inc)
- 📦 Product Manager (StartupXYZ)

---

## 🖥️ Tech Stack

- **Frontend**: React / Next.js (ή άλλο framework που χρησιμοποίησες)
- **Backend**: Node.js / Python + REST API
- **AI Engine**: Google Gemini 1.5 via API
- **Styling**: TailwindCSS / MaterialUI
- **Deployment**: (π.χ., Vercel, Netlify ή local)

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- npm ή yarn
- Google Gemini API Key

### Installation

```bash
git clone https://github.com/your-username/smartcv.git
cd smartcv
npm install
npm run dev
