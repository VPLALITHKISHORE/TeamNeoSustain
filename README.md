# TeamNeoSustain
All India Developers Challenge 2025
<h1 align="center">
  HydroSense – Smart Water Monitoring & Anomaly Detection System
</h1>

<p align="center">
  <b>AIDC 2025 Final Hackathon Submission</b><br>
  <i>End-to-end AI-powered solution for real-time groundwater monitoring, prediction, public alerting, and complaint redressal</i>
</p>

<hr>

<h2>🚩 Problem Statement</h2>

India faces recurring water crises due to undetected groundwater depletion, delayed civic response, and lack of public awareness. Despite the presence of Digital Water Level Recorders (DWLR), intelligent data-driven intervention is missing.

<h2>✅ Our Solution: HydroSense</h2>

HydroSense is a comprehensive, real-time water monitoring system that combines AI models, alert mechanisms, citizen participation, and data visualization to create a **smart groundwater governance platform**.

It enables:
- Real-time anomaly detection from DWLR streams
- Groundwater level prediction using machine learning
- Automated SMS and voice call alerts to stakeholders
- Complaint redressal system with geo-tagging and image capture
- Live climate and water news feeds using web scraping

<hr>

<h2>🧠 System Architecture</h2>

<div align="center">
  <img src="images/dwlr_anomaly.png" width="90%">
</div>

<table>
  <tr><td><b>Edge Layer</b></td><td>DWLRs & Telemeter Systems (ThingSpeak Cloud)</td></tr>
  <tr><td><b>Backend Layer</b></td><td>AI/ML Models (Isolation Forest, Random Forest), Flask APIs</td></tr>
  <tr><td><b>Frontend Layer</b></td><td>Dashboards, Complaint Portal using ReactJS + HTML + CSS</td></tr>
</table>

<hr>

<h2>⚙️ AI Models Used</h2>

| Use Case              | Model            | Description |
|----------------------|------------------|-------------|
| Anomaly Detection    | Isolation Forest | Detects non-linear water level abnormalities |
| Groundwater Forecast | Random Forest    | Monthly trend forecasting using historical and synthetic data |

<hr>

<h2>🌐 Deployment Links</h2>

| Platform              | Role                       | URL |
|-----------------------|----------------------------|-----|
| Web App (Public)      | For Citizens               | [hydrosense-public.vercel.app](https://hydrosense-public.vercel.app) |
| Web App (Admin)       | For Corporation & Managers | [hydrosense-admin.vercel.app](https://hydrosense-admin.vercel.app) |
| Mobile App (Public)   | Coming Soon                | Play Store (TBA) |
| Mobile App (Admin)    | Coming Soon                | Play Store (TBA) |

<hr>

<h2>📦 Project Modules</h2>

<h3>1. DWLR Anomaly Detection</h3>
<p>Real-time streaming from sensors to cloud. Anomaly detection using Isolation Forest with location tagging and API-based data delivery.</p>

<h3>2. Alert System (Twilio)</h3>
<p>Sends real-time SMS and voice calls to:</p>
<ul>
  <li>Corporation – Alert for water leakage</li>
  <li>Service Manager – DWLR unit malfunction</li>
  <li>Public – Low water level warning</li>
</ul>

<h3>3. Water & Climate News Scraper</h3>
<p>Python-based web scraper using Selenium + BeautifulSoup to collect latest news on:</p>
<ul>
  <li>Climate</li>
  <li>Water</li>
  <li>Floods / Droughts</li>
</ul>

<h3>4. Groundwater Level Forecast</h3>
<p>Uses Random Forest model to predict water levels month-wise with feature extraction and visualization.</p>

<h3>5. Public Complaint Platform</h3>
<p>Geo-tagged issue submission with photo evidence. Admin dashboard to manage, resolve, and track complaints.</p>

<hr>

<h2>📸 Screenshots</h2>

<div align="center">
  <img src="images/alert_flow.png" width="90%" alt="Alert System Flow"><br><br>
  <img src="images/complaint_form.png" width="90%" alt="Complaint Platform"><br><br>
  <img src="images/forecast_model.png" width="90%" alt="Forecast Dashboard"><br><br>
  <img src="images/news_dashboard.png" width="90%" alt="News Dashboard"><br><br>
  <img src="images/public_dashboard.png" width="90%" alt="HydroSense Dashboard">
</div>

<hr>

<h2>🛠️ Tech Stack</h2>

| Component        | Technologies Used |
|------------------|-------------------|
| Backend API      | Python, Flask, Pandas |
| AI/ML Models     | Scikit-learn (Isolation Forest, Random Forest) |
| Web Frontend     | ReactJS, HTML5, CSS3 |
| News Scraper     | Selenium, BeautifulSoup |
| Mobile App       | Flutter (Coming Soon) |
| Cloud Hosting    | ThingSpeak, Render, Vercel |
| Notification API | Twilio |
| Data Sources     | Government DWLR, Synthetic Data |

<hr>

<h2>🧑‍💻 Team – RMK_Innovators</h2>

| Name           | Role                            |
|----------------|----------------------------------|
| Aravindh M M   | Full Stack Developer, AI Models  |
| [Member 2]     | Dashboard UI/UX & Integration    |
| [Member 3]     | Alert System, Twilio Integration |
| [Member 4]     | Data Engineering & Visualization |

<hr>

<h2>📌 Conclusion</h2>

HydroSense is a powerful, scalable platform designed to bridge the gap between groundwater data and real-world action. It not only monitors and predicts, but also communicates and empowers.

<i>Smart water governance begins with HydroSense.</i>

<hr>

<h2>📄 License</h2>

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
