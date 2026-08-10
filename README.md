# Phishguard
PhishGuard (Mobile Phishing Awareness &amp; Training Kit
Here is the general description and core overview of the project based on the documentation:
## **Project Description: PhishGuard (Mobile Phishing Awareness & Training Kit)**
**PhishGuard** is an interactive, lightweight, mobile-first Web Application designed to educate and train non-technical users, learners, and employees on how to detect and defend against mobile phishing threats (such as **Smishing**, **Typosquatting**, and **Credential Harvesting**).
Instead of relying on traditional, passive reading materials, PhishGuard provides hands-on learning through simulated real-world phishing scenarios and built-in diagnostic tools.
### **Core Capabilities & Key Features**
 1. **Interactive Quiz Lab:**
   * Presents learners with real-world mobile phishing message simulations (SMS/Email).
   * Gives instant contextual feedback explaining why a link or message is safe or malicious.
 2. **Heuristic Link & Threat Inspector:**
   * Features a client-side algorithmic engine using **Levenshtein Distance matching** to automatically catch brand typosquatting (e.g., detecting paypa1.com mimicking paypal.com).
   * Evaluates protocol security (HTTP vs. HTTPS), suspicious TLDs (.xyz, .info), complex subdomain structures, and urgency triggers in the message text to calculate a dynamic risk score (0–100%).
 3. **Scenario Builder:**
   * An administrative tool allowing instructors, managers, or creators to add custom phishing scenarios directly into the app.
 4. **Progress, Audit Logging & Compliance:**
   * Records user activity, scores, and scanned link history locally on the device using browser localStorage.
   * Allows exporting audit logs in **CSV format** for compliance tracking.
   * Automatically generates a **Printable Compliance Certificate (PDF)** pre-filled with the learner's details (*Abdullahi Sani Salisu*), organization (*Waleedunslaw Cybersecurity Organization*), completion date, and overall performance score.
5 Progressive Web App (PWA) & Offline Readiness:**
   * Equipped with a Web App Manifest and Service Worker (sw.js) utilizing a **Cache-First Strategy**, enabling full offline functionality on mobile devices without requiring dedicated server infrastructure or an active internet connection.
