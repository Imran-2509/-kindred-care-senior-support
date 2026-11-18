Kindred Care 🤍
A compassionate, accessible frontend web platform designed to support elderly citizens living alone through verified student volunteer companions, weekly wellbeing check-ins, everyday assistance coordination, and a 24/7 nighttime safety helpline desk.

🌟 Overview
Kindred Care is an interactive, standalone frontend application built to address senior social isolation, digital healthcare navigation hurdles, and nighttime medical emergency anxiety. The platform runs entirely in the browser using localStorage for data persistence, requiring no backend servers or external API dependencies.

✨ Key Features
Senior Profiles & Care Circle Management: Register senior citizens with details on spoken languages, medical conditions, hobby interests, and night-time emergency contacts with full CRUD support (register, edit, remove).

Weighted Companion Matching Algorithm: Automatically ranks student volunteers by matching shared languages (up to 60 points) and hobby interests (up to 40 points) to compute a compatibility score (%) with 1-click pairing.

Weekly Companion Check-In Log: Record emotional well-being (e.g., Bright and engaged, Anxious or worried), physical health status, call duration, and digital healthcare/telehealth assistance notes.

Assistance Request Board: Track everyday practical tasks—such as medication delivery, grocery runs, utility bill payments, and digital smartphone tutoring—through an interactive status queue (Open → In progress → Completed).

24/7 Safety & Nighttime Helpline Desk: Features an instant emergency contact directory, a nighttime readiness checklist, and an interactive reassurance modal complete with a guided breathing orb and a Paramedic Quick Medical Profile Card.

Elderly Accessibility & Responsive UI: Includes an instant font-size adjuster (A / A+ / A++), mobile navigation drawer, and a clean forest-green aesthetic.

Data Backup & Reset: Export all local data to a JSON backup file or restore sample demonstration data at any time.

🛠️ Technologies Used
HTML5 / Semantic Markup

CSS3 / Custom Variables & Responsive Grid Layouts

Vanilla JavaScript (ES6+ / DOM APIs)

Browser LocalStorage API (for frontend data persistence)

Google Fonts (DM Sans & Manrope)

🚀 Getting Started & Deployment
Because Kindred Care is a purely frontend solution, you do not need to install Node.js, databases, or backend runners.

Local Development
Clone the repository:
git clone https://github.com/your-username/kindred-care-senior-support.git

Open the project folder.

Open index.html directly in any web browser (Chrome, Firefox, Safari, Edge).

Deploying to GitHub Pages
Push your code to a public GitHub repository.

Go to your repository settings on GitHub.

Navigate to Pages under the "Code and automation" section.

Under Build and deployment, select Deploy from a branch and set the branch to main (or master) and / (root), then click Save.

Your live deployed link will be available at
[https://imran-2509.github.io/kindred-care-senior-support/](https://imran-2509.github.io/kindred-care-senior-support/).

💡 Project Usage
Register a Senior: Head to the Senior profiles tab to add an elderly citizen's preferences, languages, and emergency contact details.

Find a Companion: Go to Companion matching, select the registered senior, and review the computed match percentages to pair them with a student volunteer.

Log Check-Ins: Use Weekly check-ins after a companion call to note their mood, health status, and telehealth readiness.

Coordinate Assistance: Post errands or digital tutoring tasks on the Help requests board and update their progress status.

Nighttime Reassurance: Click the 24/7 Helpline button in the top bar to access breathing exercises and paramedic medical cards.

🛡️ Disclaimer
Kindred Care is designed as an academic and community demonstration project. It is not a staffed emergency dispatch service, professional medical helpline, or substitute for official emergency medical services (such as 112, 108, or 911).
