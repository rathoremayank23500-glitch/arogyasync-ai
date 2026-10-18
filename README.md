# ArogyaSync AI 🏥⚡

> **Offline-First Operational Intelligence Mesh for Primary & Community Health Centres (PHCs/CHCs)**  
> *Built for Google for Developers & Hack2Skill PromptWars x VELONX (Build with AI)*  
> **Track:** Smart Health — AI-Driven Health Center & Supply Chain Management

---

## 📌 Problem Statement
Rural healthcare facilities across India (PHCs and CHCs) struggle with recurring operational blindspots:
* **Medicine Stock-Outs:** Essential life-saving drugs (anti-snake venom, antibiotics, IV fluids) exhaust unexpectedly due to slow, handwritten paper ledger tracking and zero inter-facility buffer sharing.
* **Unmanaged Patient Footfall:** Morning OPD surges trigger chaotic 2-hour wait times with unstratified patient acuity.
* **Zero Bed Visibility:** Critical emergency referrals arrive blind at overloaded CHCs while nearby beds sit unlisted.
* **Unannounced Doctor Absence:** Medico-legal court duties and VIP protocol leave rural clinics abruptly unstaffed.

---

## 💡 Solution: ArogyaSync AI
ArogyaSync AI transforms primary health centers from reactive paper-bound clinics into an autonomous operational mesh:

### 1. Multimodal Register OCR & Predictive Supply Chain (Gemini 1.5 Flash)
* Clinic staff snap a photo of the daily paper stock register using their phone.
* Gemini 1.5 Flash extracts handwritten drug names, batch numbers, and stock counts into structured JSON.
* Time-series models forecast stock depletion runways against local seasonal disease spikes (such as dengue or malaria) and auto-trigger micro-transfers from nearby surplus CHCs (15–20 km away).

### 2. Vernacular Voice & Text Triage (Hindi / Hinglish / English)
* ASHA workers or patients speak symptoms into a mobile kiosk or WhatsApp bot in their native language.
* Clinical red-flag parsing stratifies acuity into **P1 Emergency**, **P2 Acute**, and **P3 Routine**, issuing smart color-coded tokens to eliminate morning bottlenecks.

### 3. Real-Time Bed Telemetry & Verified Referral Mesh
* One-tap ward status tracking (Available, Occupied, Oxygen Support) with predictive discharge modeling.
* Confirms and locks vacant ICU/oxygen beds at the destination CHC before ambulance dispatch, preventing fatal transfer delays.

### 4. Dynamic Doctor Attendance & Tele-Consultation Fallback
* Geo-fenced biometric check-ins verify on-site physician presence.
* If a doctor is summoned off-site for emergency or legal duties, the system automatically bridges queued routine patients to a district tele-health pool via an encrypted WebRTC tele-consultation stream.

---

## 🛠️ Google AI & Cloud Tech Stack
* **Intelligence Layer:** Google Gemini 1.5 Flash (Multimodal OCR & Vernacular NLP), Vertex AI (Time-Series Run-Rate Forecasting).
* **Edge & Offline Client:** Progressive Web App (PWA) with local SQLite/Room storage for intermittent rural connectivity.
* **Backend Microservices:** Python FastAPI with Pydantic validation models.
* **National Standards:** Ayushman Bharat Digital Mission (ABDM) FHIR standards and e-Aushadhi integration readiness.

---

## 🤖 Core Prompts Used (PromptWars)

### Prompt 1: Handwritten Pharmacy Register Digitization



