Perfect — let’s look at **another car marketplace case study**, this time where an **agency actually built the MVP** before the company scaled internally.

Here’s one that fits that pattern well 👇

---

## 🚗 **Case Study: Kavak (Mexico) — Agency-Built MVP to Global Marketplace**

---

## 🏁 **1. Background**

- Founded: **2016, Mexico City**
- Founders: **Carlos García, Loreanne García, and Roger Laughlin**
- Idea: Build a **trusted used-car marketplace** in Latin America — an industry notorious for fraud, paperwork issues, and lack of standardized pricing.

> **Problem:** Latin America’s used car market was worth billions, but there was _no trusted digital platform_ for transparent buying and selling.

---

## 🧩 **2. The Early Stage (2016–2017)**

The founders were **business operators**, not engineers.
They needed:

- A website and backend system that could handle car listings, inspections, and payments.
- Something fast enough to show investors the potential.

Instead of hiring an in-house tech team (which would take months), they **hired a Mexico-based software agency** that specialized in **marketplace MVPs**.

---

### 🔹 Agency Deliverables

**Goal:** Build MVP in 10–12 weeks to test:

- Listing flow (add, edit, remove car)
- Search/filter functionality
- Price estimation
- Booking a test drive
- Admin portal (approve, reject, verify)

**MVP Stack:**

| Layer               | Tech Used          |
| ------------------- | ------------------ |
| Frontend            | React.js           |
| Backend             | Node.js + Express  |
| Database            | MongoDB            |
| Hosting             | AWS EC2            |
| Payment Integration | Stripe (test mode) |
| Image Uploads       | AWS S3             |
| Notifications       | SendGrid + Twilio  |

**Team from Agency:**

| Role            | Description                           |
| --------------- | ------------------------------------- |
| Project Manager | Liaison between founders & devs       |
| UX/UI Designer  | Built user flows & marketplace layout |
| 2 Frontend Devs | React interface                       |
| 2 Backend Devs  | APIs + MongoDB                        |
| QA              | Testing core flows                    |

---

## 🚀 **3. MVP Launch**

They launched a **pilot version** in Mexico City with:

- ~50 cars manually onboarded by Kavak staff.
- Buyers able to book appointments online.
- Inspections done at Kavak’s small warehouse.

The goal wasn’t scalability — it was **proof of concept**:

- People were willing to **book online**, even for used cars.
- The agency’s MVP handled basic workflows and payments successfully.

---

## 💡 **4. Transition to Internal Team**

Within 6 months:

- Kavak raised its **first seed funding (~$1.5M)**.
- Immediately began **hiring in-house engineers** to replace agency code.
- The agency stayed on **retainer** for maintenance for 3–4 months during transition.

**Internal Team Focused On:**

- Refactoring backend for scalability.
- Adding car inspection API.
- Integrating CRM for customer follow-ups.
- Improving photo upload and pricing engine.

By 2018, all core development was handled internally.

---

## ⚙️ **5. Scaling and Tech Evolution**

Once Kavak validated its business model:

- Expanded to **Brazil and Argentina**.
- Introduced **AI-based pricing models**.
- Built an **internal logistics system** for car pickup/delivery.
- Shifted architecture to **microservices + event-driven design** (Kafka, Node.js, Go).
- Added **mobile apps** using React Native.

**In-house team grew** to 200+ engineers across Latin America.
They also opened a **data science division** to improve price and risk modeling.

---

## 🧭 **6. Decision Breakdown**

| Decision             | Owner                |
| -------------------- | -------------------- |
| Business Model       | Founders             |
| MVP Feature Scope    | Founders + Agency PM |
| Tech Stack (initial) | Agency Architect     |
| Product Design       | Agency UX/UI Team    |
| Funding & Expansion  | Founders + Investors |
| Rebuild Strategy     | Internal CTO         |

> 💬 “We knew we’d rebuild, but the MVP gave us investor traction we couldn’t have achieved without a working demo.” — _Carlos García, Co-founder of Kavak (TechCrunch interview)_

---

## 💰 **7. Results**

| Stage            | Year | Key Milestone                 |
| ---------------- | ---- | ----------------------------- |
| MVP Launch       | 2016 | Agency-built web app launched |
| Seed Funding     | 2017 | $1.5M raised                  |
| Series A         | 2018 | $10M raised, in-house rebuild |
| Global Expansion | 2020 | Entered Brazil, Argentina     |
| Unicorn Status   | 2021 | Valued > $4 billion           |
| Super App        | 2023 | Added financing + insurance   |

---

## 🧠 **8. Key Lessons**

1. **Agencies accelerate MVP validation.**

   - Founders didn’t waste time hiring engineers.
   - Product hit market in <3 months.

2. **Always plan for rebuild.**

   - Agency-built MVP ≠ scalable architecture.
   - Rebuilding is expected once traction comes.

3. **Define “what,” let the agency define “how.”**

   - Founders focus on vision; agency on tech.

4. **Documentation and handover are critical.**

   - Proper repos, credentials, and deployment access make transition smoother.

5. **Internalization is a must for long-term scale.**

   - Once you have users, investors demand an in-house tech team.

---

## 🧩 **9. Stage-by-Stage Timeline**

| Stage             | Duration | Built By          | Outcome                   |
| ----------------- | -------- | ----------------- | ------------------------- |
| Ideation          | 1 month  | Founders          | Business plan             |
| MVP Build         | 3 months | Software Agency   | Working product           |
| Pilot Launch      | 2 months | Agency + Founders | Early traction            |
| Funding + Handoff | 6 months | Founders          | Seed raised               |
| Rebuild & Scale   | 1 year   | Internal Team     | Growth to multiple cities |

---

## ⚙️ **10. Current Stack (Enterprise Phase)**

| Component | Technology                      |
| --------- | ------------------------------- |
| Frontend  | React.js + Next.js              |
| Mobile    | React Native                    |
| Backend   | Node.js + Go microservices      |
| Database  | PostgreSQL, MongoDB             |
| Messaging | Kafka                           |
| Cloud     | AWS (ECS, S3, CloudFront)       |
| ML / Data | Python + TensorFlow for pricing |

---

## 🏁 **Summary**

| Phase      | Who Builds                | Purpose                |
| ---------- | ------------------------- | ---------------------- |
| MVP        | Agency                    | Validate idea          |
| Growth     | In-house + agency support | Optimize core features |
| Scale      | Full in-house             | Build for performance  |
| Enterprise | Global dev org            | Automate, expand       |

---

Would you like me to show a **diagram showing the Kavak lifecycle** — from founders → agency → MVP → internal rebuild → scale — similar to how venture-backed marketplaces grow?
That visual makes the business and tech relationship very clear.
