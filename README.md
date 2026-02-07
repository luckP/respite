# Respite (Prototype)

**Status:** 🚧 Prototype / MVP Phase  
**Concept:** Asynchronous Triage Gateway for Pediatricians

## ⚡ The Problem
Doctors, especially pediatricians, are facing burnout due to the "WhatsAppification" of healthcare. Patients treat personal messaging apps as 24/7 synchronous consultation rooms, leading to:
- Erosion of professional boundaries.
- Unpaid and unstructured labor.
- Legal risks from informal medical advice.

## 🛡️ The Solution: Respite
**Respite** acts as a "digital airgap"—a middleware layer between the patient's anxiety and the doctor's private life.

Instead of messaging the doctor directly, patients use a unique Respite link to:
1.  **Classify Intent:** Distinguish between routine inquiries, scheduling, and urgency.
2.  **Acknowledge Limits:** Explicitly consent to non-emergency service terms.
3.  **Structure Data:** Provide concise, structured information (symptoms, duration, etc.).

The system then **routes** the sanitized request to the doctor's dashboard or queues it for business hours, effectively turning a chaotic chat stream into a manageable ticket queue.

## 🛠️ Architecture (MVP)
- **Pattern:** Facade / API Gateway for Human Communication.
- **Frontend:** [Insert Framework, e.g., Next.js/React]
- **Backend:** [Insert Backend, e.g., Node.js/Serverless Functions]
- **Data:** [Insert DB, e.g., PostgreSQL/Supabase]

## 🚀 Getting Started
1.  Clone the repo.
2.  Install dependencies: `npm install`
3.  Run the development server: `npm run dev`

## ⚠️ Disclaimer
This is a **technical prototype** designed to validate the triage workflow. It is not a certified medical device or a replacement for emergency services (SAMU/911).
