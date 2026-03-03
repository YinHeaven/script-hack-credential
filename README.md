# TheAllSeer - Nuclear Extraction Script

🔍 Main function:
Searches for and displays in the console any credential-related information (usernames, passwords, tokens) stored or visible on the current webpage.


📋 What it specifically searches for:
LocalStorage - Data permanently stored in the browser

SessionStorage - Temporary data from the current session

Cookies - Small files containing session information

Form fields - Inputs containing passwords

Meta tags - Tags with security tokens

🔑 What keywords it tracks:
"pass" (password)

"token" (authentication token)

"auth" (authentication)

"cred" (credentials)

📊 Output:

Displays all findings organized by category

Provides a final summary with the total number of credentials found

Presents the data in a table format for easy reading


-------------------------------------------------------------------


⚠️ IMPORTANT WARNING ⚠️

This script:

Only works in your own browser and with your own accounts

Should not be used to access other people's accounts - that would be Illegal

Only displays credentials already visible on the current page

Cannot access passwords securely saved by the browser (system protected)

Ethical and legal use:

✅ Use it to recover your own forgotten credentials

✅ To audit your own security

❌ DO NOT use it on other people's accounts

❌ DO NOT use it on sites where you are not authorized

----------------------------------------------------------------------
🚀 How to use it:
Open the page where you are logged in (your server)

Press F12 to open the developer tools

Go to the "Console" tab

Paste the ENTIRE script and press Enter

DONE! You will see:

All LocalStorage and SessionStorage

All cookies

All form inputs

Metadata and global variables

Data is automatically copied to the clipboard

📝 What it does exactly:
Extracts EVERYTHING, does not filter by keywords

Displays hidden inputs that may contain tokens

Searches for global variables with suspicious names

Generates a structured report

Automatically copies to the clipboard

⚡ If it doesn't copy automatically:
In the console, you will see a reporteFinal object. Right-click on it and select "Copy object".

🔐 Data you will obtain:
Authentication tokens

Session IDs

Credentials stored in localStorage

----------------------------------------------------------------------------------------------------
🔥 THEALLSEER NUCLEAR EXTRACTION SCRIPT 🔥
⚠️  ONLY FOR YOUR OWN ACCOUNTS ⚠️

📦 LOCALSTORAGE (COMPLETE)
  theme: "dark-mode"
  user_preferences: {"language":"es","notifications":true}
  last_visit: "2024-03-03T10:30:00Z"
  session_id: "sess_abc123def456"
  app_state: {"page":"dashboard","filters":{}}

📦 SESSIONSTORAGE (COMPLETE)
  temp_data: {"formData":{"name":"Demo","email":"demo@test.com"}}
  current_step: "checkout"
  wizard_state: "step3"

🍪 COOKIES (COMPLETE)
  PHPSESSID: "abc123def456ghi789"
  cookie_consent: "accepted"
  _ga: "GA1.2.123456789.1678901234"

📝 FORM INPUTS
  username (text): "demo_user"
  password (password): "••••••••••"
  email (email): "demo@example.com"
  api_token (hidden): "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9..."
  csrf_token (hidden): "csrf_abc123def456"

📊 COMPLETE REPORT
Total LocalStorage: 5
Total SessionStorage: 3
Total Cookies: 3
Total Inputs: 5

📋 SENSITIVE DATA FOUND:
┌──────────┬────────────┬────────────────────────────────────┐
│ (index)  │ nombre     │ value                              │
├──────────┼────────────┼────────────────────────────────────┤
│ 0        │ username   │ "demo_user"                        │
│ 1        │ password   │ "••••••••••"                       │
│ 2        │ email      │ "demo@example.com"                 │
│ 3        │ api_token  │ "eyJhbGciOiJIUzI1NiIsInR5cCI6..."  │
└──────────┴────────────┴────────────────────────────────────┘

✅ DATA COPIED TO CLIPBOARD
🔒 REMEMBER: Only for your own accounts
Data from autofilled forms

Any sensitive information in memory

