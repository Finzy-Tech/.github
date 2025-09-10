# Finzy 💹  

## Hi there 👋, Welcome to Finzy  

Finzy is a personal investment assistant designed to make investing in **mutual funds simple, transparent, and user-friendly**.  

Whether you’re just starting your investment journey or already managing multiple SIPs, Finzy helps you **analyze, track, and optimize your portfolio** — all in one place.  

---

## 🚀 What is Finzy trying to do?  

Investing can feel overwhelming — KYC, risk profiling, choosing funds, and tracking returns are often confusing for new investors.  
Finzy’s goal is to:  

- Simplify onboarding with easy signup/login and risk profiling.  
- Provide **real-time market data** via AMFI APIs.  
- Offer a clean **portfolio dashboard** to track holdings, SIPs, and returns.  
- Deliver **insights and blogs** to keep users informed.  
- Grow into a **complete wealth management platform** over time.  

---

## ✨ Core Features (MVP)  

### 👤 User Onboarding  
- Signup/Login (KYC option later)  
- Basic risk profiling (understand investor appetite)  

### 📈 Investment Options  
- Mutual Funds (via AMFI NAV API)  
- SIP Calculator (simulate returns)  

### 📊 Portfolio Management  
- Portfolio overview (holdings, NAVs, returns)  
- SIP tracking (status, next due date)  
- Performance monitoring  

### 📰 Market Data & Insights  
- Real-time NAVs (from AMFI)  
- News, insights, and blogs  

### 🔔 Notifications  
- SIP reminders  
- Market updates  

---

## 🏗️ Architecture  

- **Frontend**  
  - Built with modern web stack (Next.js / React + TypeScript)  
  - Two key routes:  
    - `/dashboard` → landing dashboard (risk profile, insights, market data)  
    - `/portfolio` → portfolio management (holdings, SIPs, performance)  

- **Backend**  
  - Modular services:  
    - `auth-service` → login, onboarding, KYC  
    - `market-service` → AMFI NAVs, news  
    - `portfolio-service` → holdings, SIPs, returns  

- **Database**  
  - `users` → auth, risk profile, KYC status  
  - `funds` → mutual fund data + NAV history  
  - `sip_plans` → user SIP details  
  - `transactions` → future extension for real execution  

---

## 📅 Roadmap  

- ✅ User authentication & onboarding  
- ✅ Basic risk profiling  
- ✅ AMFI integration for NAVs  
- ✅ SIP calculator  
- 🚧 Portfolio dashboard (in progress)  
- 🚧 Notifications & alerts  
- 🔜 KYC & compliance integration  
- 🔜 Real SIP execution (payment gateway)  

---

## 🤝 Contributing  

We welcome contributions! If you’d like to help improve Finzy:  
1. Fork this repo  
2. Create your feature branch (`git checkout -b feature/awesome-feature`)  
3. Commit your changes (`git commit -m 'Add awesome feature'`)  
4. Push to the branch (`git push origin feature/awesome-feature`)  
5. Open a Pull Request  

---

## 📜 License  

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.  

---

## 🙌 Acknowledgements  

- [AMFI NAV API](https://www.amfiindia.com) for mutual fund NAV data  
- Open-source community for inspiration & tools  
