# 📈 Riskfolio
### Mobile Portfolio & Risk Tracker

> Know what you own. Know what you can handle.

Riskfolio is a Flutter mobile app that brings all your investments — **BIST stocks, Gold, Forex and SPY** — into one clean dashboard, and helps you discover your **investor profile on a scale of 1 to 7**.

---

## ✨ Features

- **All assets in one place** — track BIST, Gold, Forex and SPY together
- **Live market prices** — pulled from a financial API
- **Risk assessment test** — a short quiz that places you on a 1–7 risk scale
- **Asset allocation chart** — see your portfolio distribution at a glance
- **Profit & loss tracking** — clear green/red indicators

---

## 🎨 Design

| Element | Choice | Why |
|---|---|---|
| Background | Dark Navy `#0F172A` | Easy on the eyes, dark mode first |
| Accent | Gold `#F59E0B` | Strong contrast, a nod to wealth and value |
| Profit | Green `#10B981` | Industry standard for gains |
| Loss | Red `#EF4444` | Industry standard for losses |
| Font | Inter | Highly readable numbers on small screens |

Card-based layout, one-handed bottom navigation (Home · Add Asset · Profile) and large tap targets.

---

## 🏗️ Architecture

**MVVM (Model–View–ViewModel)** with Provider

- **Model** — `Asset`, `UserProfile`
- **View** — Flutter screens such as `DashboardScreen`, `RiskResultScreen`
- **ViewModel** — `AssetProvider`: fetches prices, calculates the risk score, updates the UI

**Protocols:** REST over HTTPS · JSON parsing · OAuth 2.0 · Local storage (`shared_preferences`)

---

## 📂 Deliverables

| | |
|---|---|
| 📄 Design Justification | `Design Justification_ Portfolio & Risk Tracker App.pdf` |
| 🔀 User Flow | `Mobil Programming Flow.pdf` |
| 🧱 Architecture & Protocols | `Architecture and Protocols.pdf` |
| 🎨 Wireframes · Mockups · Prototype | [Figma](https://www.figma.com/design/X0nQiwhuBcKXb1ha8SyQ9T/Portfolio-and-Risk-Management-App?node-id=0-1&t=FJPlks42g8Hpw5jh-1) |

---

## 👥 Team

| Name | Student No |
|---|---|
| Bilal Aytepe | 23058002 |
| Tayfur Durlanık | 22058020 |

*Gemini, Claude and Figma AI were used as assistants.*

---

<sub>MTM4186 Mobile Programming · Yıldız Technical University</sub>
