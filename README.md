🛡️ Phishing Detection Email Dashboard (Simulator)

Using Frontend & Java Backend

📌 Project Description

The Phishing Detection Email Dashboard (Simulator) is a web-based application designed to identify and analyze phishing emails and malicious URLs. The system simulates how real-world email security platforms detect threats by scanning inputs such as email content or URLs and classifying them as safe or phishing.

This project is developed using a frontend interface (HTML, CSS, JavaScript) for user interaction and a backend built with Java (Spring Boot) to handle processing, logic, and threat detection.

🎯 Objective

The main objective of this project is to:

Detect phishing emails or URLs using predefined rules or logic
Provide a user-friendly dashboard for analysis
Simulate real-time email security systems
Help users understand phishing threats and prevention techniques
⚙️ System Overview

The system consists of two main components:

1. Frontend (User Interface)
Built using HTML, CSS, and JavaScript
Provides forms to input email content or URLs
Displays results such as:
Safe ✅
Suspicious ⚠️
Phishing ❌
Includes dashboard features like:
Total scans
Detected phishing attempts
Recent activity
2. Backend (Java - Spring Boot)
Handles request processing and business logic
Analyzes input using phishing detection rules such as:
Suspicious keywords (e.g., “urgent”, “verify now”)
Presence of fake or shortened URLs
Domain mismatch
Sends results back to frontend
Stores scan history (optional database integration like MySQL)
🔍 Key Features
📧 Email/URL scanning system
📊 Dashboard with statistics and reports
🔐 Login system for user authentication
🧠 Rule-based phishing detection
📝 Scan history tracking
🔄 Real-time result display
🎨 Simple and responsive UI
🛠️ Technologies Used
Frontend: HTML, CSS, JavaScript
Backend: Java, Spring Boot
Tools: VS Code, Maven
🚀 Working Process
User logs into the dashboard
Enters an email content or URL
Frontend sends request to backend
Backend analyzes input using phishing detection logic
System classifies input as safe or phishing
Result is displayed on dashboard


run: mvn clean spring-boot:run
