# Immunization-tracker
"Your personal immunization assistant - never miss a vaccine, stay healthy!"




#🧒 Immunisation Recorder & Reminder System

##📌 Problem Statement

In India, many parents miss their child’s vaccination schedule because:

They forget the dates

Lack of awareness

Limited accessibility in rural areas


👉 This leads to children being vulnerable to vaccine-preventable diseases.


---

##🎯 Our Solution

We built an Immunisation Recorder & Reminder System that:

1. Allows parents to register their child with DOB.


2. Automatically calculates the vaccination schedule.


3. Sends reminders/notifications before due dates.


4. Maintains a vaccination history record.




---

##👥 Team Roles

1. Research & Data Expert – Collect vaccination schedule and prepare JSON/DB.

2. Backend Developer – Create API and implement age-to-vaccine logic.

3. Frontend Developer – Build mobile/web app with user-friendly interface.

4. Notification Engineer – Integrate SMS/WhatsApp/App notifications.

5. Testing & Presentation Lead – Test the project and prepare hackathon demo.


---

🛠 Tech Stack

Frontend: React / React Native

Backend: Node.js / Python (Flask / FastAPI)

Database: MongoDB / Firebase / MySQL

Notifications: Firebase Cloud Messaging / Twilio / WhatsApp API

Version Control: Git & GitHub



---

##📂 Repository Structure

immunisation-recorder/
│
├── backend/             # Backend code
├── frontend/            # Frontend code
├── data/                # Vaccination schedule (JSON/CSV)
│   └── vaccination_schedule.json
├── docs/                # Presentations, diagrams
└── README.md            # Project documentation


---

##📊 Vaccination Data Source

Government of India – National Immunization Schedule (NIS)

World Health Organization (WHO)

Indian Academy of Pediatrics (IAP)


##JSON Example:

[
  {
    "age": "At Birth",
    "vaccines": ["BCG", "OPV-0", "Hepatitis-B (Birth dose)"],
    "next_due": "6 Weeks"
  },
  {
    "age": "6 Weeks",
    "vaccines": ["OPV-1", "DPT-1 (Pentavalent)", "IPV-1", "Rotavirus-1", "PCV-1"],
    "next_due": "10 Weeks"
  }
]


---

##🚀 How It Works

1. Parent registers child → enters DOB.

2. Backend calculates child’s age → checks JSON/DB for due vaccines.

3. App displays → “Next Vaccine Due: DPT-1 on 10 Oct 2025”.

4. Notification system sends reminder to parents.

---

##📸 Demo Flow (Hackathon Presentation)

Screen 1: Child registration

Screen 2: Dashboard → “Next Vaccine: DPT-1”

Screen 3: Notification alert on parent’s phone

Screen 4: Vaccination history record



---

##✅ Future Scope

Multi-language support (English + Hindi + Regional)

QR-code based hospital vaccination record

Integration with government health portals

AI prediction for missed doses & bulk reminders



---

##👨‍💻 Contributors

[Your Name] – Research & Data Expert

[Member 2] – Backend Developer

[Member 3] – Frontend Developer

[Member 4] – Notification Engineer

[Member 5] – Testing & Presentation Lead

