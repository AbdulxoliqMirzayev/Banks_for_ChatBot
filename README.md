# Banks_for_ChatBot

# 🏦 Bank Chatbot - Natural Language Understanding (NLU) Model

**Anorbank mijozlari uchun** o‘zbek tilida tayyorlangan, foydalanuvchi savollarini avtomatik tushunuvchi va javob beruvchi **AI Chatbot loyihasi**.

---

## 📚 Loyihaning Asosiy Maqsadi

- Anorbank mijozlarining **3000+ real komentlarini** tahlil qilish
- Foydalanuvchi izohlarini **tozalash**, **xizmat turi**, **muammo** va **maqsad (intent)** ni aniqlash
- Matnlardan **TF-IDF vektorizatsiya** yordamida **Machine Learning modelini** qurish
- **Logistic Regression** modeli yordamida foydalanuvchi niyatini aniqlash
- Kritik vaziyatlarda (karta bloklangan, hisob bloklangan) foydalanuvchidan **telefon raqami so‘rash** va **mutaxassisga uzatish**

---

## 📦 Loyihada foydalanilgan texnologiyalar

- **Python** (Google Colab uchun)
- **pandas** - ma'lumotlar bilan ishlash uchun
- **nltk** - matn tozalash va preprocessing
- **scikit-learn (sklearn)** - ML modeli va baholash
- **matplotlib, seaborn** - grafiklar va vizualizatsiya
- **joblib** - model va vektorizatorni saqlash

---

## 🛠 Loyihaning asosiy bosqichlari

### 1. Dataset tayyorlash
- 3000+ realistik Anorbank mijozlar izohlari
- Har bir izohda: foydalanuvchi ismi, jinsi, sanasi, izoh matni

### 2. Data Cleaning
- Harflarni kichik qilish
- Maxsus belgilar va noto'g'ri shevalarni olib tashlash
- Stopwords va lemmatization
- Toza `clean_comment` ustuni yaratish

### 3. Intent aniqlash
- Intentlar: `shikoyat`, `rahmat`, `so'rov`, `tavsiya`, `tanqid`, `savol`, `boshqa`
- Qoidaga asoslangan oddiy model (`rule-based`)

### 4. Entity Extraction
- Xizmat turi: `kredit karta`, `hisob`, `depozit`, `mobil ilova`, `internet banking`
- Muammo turi: `blok`, `nosozlik`, `xato`, `sekin`, `server error`

### 5. Machine Learning Modeling
- `TF-IDF Vectorization` bilan matnni raqamli ko‘rinishga o‘tkazish
- `Logistic Regression` modeli qurish
- Modelni `train/test split` bilan o‘rgatish va baholash
- Model Performance: **Accuracy: 1.0** ✅

### 6. Modelni Saqlash
- Model: `anorbank_intent_model.pkl`
- TF-IDF vektorizator: `anorbank_tfidf_vectorizer.pkl`

### 7. Session Management (Advanced)
- Har bir foydalanuvchi uchun session yaratish
- Telefon raqami so‘rash va mutaxassisga eskalatsiya qilish (kritik vaziyatlarda)

---

## 📈 Natijalar

- 3000+ real foydalanuvchi komentlari bilan ishlov berildi
- 100% aniqlik bilan intentlar aniqlandi
- Telefon raqamini so‘rash va eskalatsiya qilish imkoniyati yaratildi
- Chatbot uchun to‘liq backend tayyorlandi

---

## 🚀 Keyingi bosqichlar (Optional)

- Modelni real-time Telegram botga ulash
- FastAPI bilan mini-API server yaratish
- Chatbotga yangi tillar va xizmatlarni qo‘shish
- Deep Learning modellar bilan kuchaytirish (BERT, RoBERTa)

---

## 📑 Loyiha muallifi

**Anorbank NLU Chatbot loyihasi**  
By: Abdulxoliq MIrzayev
© 2025

---

