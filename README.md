# Automate-Security-Alerts-Using-Google-Apps-Script-And-Gmail-API

🛡️ Automate Security Alerts Using Google Apps Script & Gmail API

This project will help you detect phishing emails and send alerts when suspicious activity is found in Gmail. We’ll use Google Apps Script (a built-in scripting tool in Google Workspace) to scan emails for phishing keywords and send alerts when needed.


---

🔹 Step 1: Open Google Apps Script

1️⃣ Go to Google Drive → Click “New” → “Google Apps Script”.
2️⃣ Delete any existing code and start fresh.


---

🔹 Step 2: Set Up Gmail API Access

✅ Google Apps Script has built-in GmailApp services, so no extra setup is required!

✅ This script will:
🔹 Scan emails for suspicious words.
🔹 Move suspected emails to the Spam folder.
🔹 Send an alert email if phishing is detected.


---

🔹 Step 3: Write the Security Alert Script

Paste the code inside your Google Apps Script editor.


---

🔹 Step 4: Save & Test the Script

1️⃣ Click “Save” (💾 icon).
2️⃣ Click Run ▶️ to execute the script.
3️⃣ Authorize access when prompted (Allow Gmail permissions).

✅ The script will scan emails from the past 24 hours, flag suspicious ones, move them to Spam, and send an alert to your email.


---

🔹 Step 5: Automate the Script (Run Daily Automatically)

1️⃣ Go to Triggers (⏰ icon in Apps Script Editor).
2️⃣ Click + Add Trigger → Set:

Function to run: checkForPhishingEmails

Time-driven trigger: Every 6 hours (or daily).
3️⃣ Click Save → Done!


✅ Now, your script will run automatically and check for phishing emails every day!

---
