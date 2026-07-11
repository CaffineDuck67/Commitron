# Commitron
# 🐉 Commitron

> **Your GitHub activity, brought to life.**

Commitron is an interactive, virtual coding pet that hatches, grows, and evolves based on your real GitHub activity. Simply enter a public GitHub username, and Commitron analyzes repository metrics, commits, streaks, and programming languages to create a unique digital companion reflecting your coding journey.

Built using **HTML5, CSS3, and Vanilla JavaScript**, Commitron demonstrates how data visualization, API integration, custom SVG animations, and gamification can transform standard developer statistics into an engaging visual experience.

---

## ✨ Features

### 🐣 Virtual Coding Pet
* **Dynamic Evolution:** Pet evolves automatically based on accumulated Experience Points (XP).
* **Interactive SVG Animations:** Features breathing, blinking, tail wagging, aura effects, and evolution transitions.
* **Mood System:** Pet mood dynamically reflects recent activity levels.

### 📈 GitHub Analytics & Dashboard
* **Metrics Tracked:** Total public commits, repository count, star count, longest streaks, and top programming languages.
* **Visual Breakdown:** Integrated contribution heatmap, language distribution chart, and evolution timeline.

### 🎮 Gamification & Experience
* **XP Progression:** Clear visual progress bars tracking progress to the next evolution stage.
* **Shareable Profiles:** Generate summary snapshots of your pet and developer status.
* **Recent History:** Quickly view and switch between recently analyzed developer profiles.

### ⚡ Performance & Design
* **Zero Backend Required:** 100% client-side application running directly in the browser.
* **API Rate Limit Handling:** Built-in client-side caching and API rate-limit awareness.
* **Fully Responsive:** Smoothly scales across mobile, tablet, and desktop viewports.

---

## 📷 Screenshots

> *Replace placeholder images with real screenshots post-deployment.*

| Home Screen | Virtual Pet View | Developer Dashboard |
| :---: | :---: | :---: |
| `screenshots/home.png` | `screenshots/pet.png` | `screenshots/dashboard.png` |

---

## 🚀 Live Demo

🔗 **[Launch Commitron](#)** *(Coming Soon)*

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
* **Graphics:** Inline SVG
* **Data Source:** GitHub REST API
* **Typography:** Google Fonts

---

## 📂 Project Structure

```text
Commitron/
├── index.html          # Main application page
├── README.md           # Project documentation
├── assets/             
│   ├── images/         # Visual assets & graphic elements
│   └── icons/          # Application icons
└── screenshots/        # README preview assets
🧠 How It Works  [ User Input ]  ──>  [ GitHub REST API ]  ──>  [ Data Analysis ]
                                                        │
  [ Dynamic Dashboard ]  <──  [ Pet Evolves ]  <──  [ XP Calculation ]
Input: User submits a valid GitHub username.Fetch: Commitron requests public events and repository data via GitHub's REST API.Analyze: Calculates public push events, total repositories, and total stars received.Calculate: Applies the custom XP formula to compute current experience points.Render: The SVG pet updates its evolutionary state while the dashboard populates real-time stats.⭐ XP FormulaXP is calculated using the following weighted metric formula:$$\text{XP} = (\text{Recent Commits} \times 10) + (\text{Repositories} \times 5) + (\text{Stars} \times 3)$$🐉 Evolution StagesStageNameXP RequiredDescription🥚Null Egg0 XPWaiting to be hatched🌱Byte Sprout100 XPFirst sign of digital life🐶Loop Pup300 XPEnergetic and active learner🦊Stack Fox700 XPNimble and experienced problem solver🐉Commit Wyrm1500 XPLegendary status achieved🔮 More legendary evolutions are currently in development!📊 Data Source & API LimitationsCommitron uses the public GitHub REST API.Scope: Analyzes public push events, public repositories, primary languages, and star counts.Note: GitHub's Events API returns up to 90 days of recent public activity. Private repository activity and historical events older than 90 days are not accessible without authenticated OAuth scopes.🎯 Roadmap[ ] v1.1 — Profile EnhancementsDeveloper profile cards with custom GitHub avatarsAdvanced contribution heatmaps[ ] v1.2 — Quests & AccessoriesDaily coding quests and achievement badgesUnlockable pet accessories[ ] v1.3 — Social & AuthGitHub OAuth integration (access extended historical data)Global developer leaderboards and head-to-head comparisons[ ] v2.0 — Extended EcosystemMultiple species options, inventory system, and cloud saves💻 Running LocallyNo build tools or server setup required!Clone the repository:Bashgit clone [https://github.com/CaffineDuck67/commitron.git](https://github.com/CaffineDuck67/commitron.git)
Navigate into the project directory:Bashcd commitron
Launch the application:Simply open index.html in your web browser of choice.🌍 Browser SupportChromeEdgeFirefoxBraveSafariYesYesYesYesYes🤝 ContributingContributions make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.Fork the ProjectCreate your Feature Branch (git checkout -b feature/AmazingFeature)Commit your Changes (git commit -m 'Add some AmazingFeature')Push to the Branch (git push origin feature/AmazingFeature)Open a Pull Request📄 LicenseDistributed under the MIT License. See LICENSE for more information.👨‍💻 AuthorRajesh BasnetStudent • Data Science & AI Enthusiast • Python DeveloperGitHub: @CaffineDuck67
