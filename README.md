# Study Buddy 📚

**Study Buddy** is a comprehensive study management web application designed to help students organize their academic lives effectively. With features like timetables, calendars, task management, and note-taking, it serves as an all-in-one assistant for students aiming to stay on top of their goals.

---

## 🚀 Features

1. **Timetable**  
   Easily organize and visualize your weekly study and class schedules.

2. **Calendar**  
   Keep track of upcoming exams, assignment deadlines, and other important events.

3. **Tasks Manager**  
   Add, edit, prioritize, and complete tasks with an intuitive task manager. Features include:
   - Set due dates and priorities.
   - Track completion status.

4. **Notes Manager**  
   Take, save, and search through your notes with a rich-text editor powered by [Quill.js](https://quilljs.com/). Features include:
   - Organize notes with titles.
   - Search functionality for quick access.
   - Edit and delete notes.

---

## 🛠️ Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Local Storage**: Used to persist data (tasks and notes).
- **Quill.js**: For the rich text editor in the Notes Manager.
- **Responsive Design**: Optimized for all screen sizes.

---

## 💻 Setup Instructions

### Prerequisites
- A modern web browser (Google Chrome, Firefox, etc.)
- A text editor (e.g., Visual Studio Code) if you plan to modify the code.

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/study-buddy.git
Navigate to the project directory:
bash
Copy code
cd study-buddy
Open the home.html file in your browser to start using the application:
bash
Copy code
open home.html
📂 File Structure
graphql
Copy code
study-buddy/
├── home.html          # Main landing page
├── notes.html         # Notes management page
├── tasks.html         # Task management page
├── timetable.html     # Timetable feature (to be implemented)
├── calendar.html      # Calendar feature (to be implemented)
├── styles/            # CSS for styling (inline CSS is currently used)
└── scripts/           # JavaScript functionality (embedded in HTML)
🎨 Design Highlights
Color Scheme:

Sidebar: #A8E1C5 (Light green) with black text.
Background: #F4F4F9 (Light grey).
Cards and modals: White with subtle shadows.
Intuitive Layout:

Sidebar navigation for quick access to features.
Responsive design adapting to all screen sizes.
🛡️ Future Enhancements
Timetable and Calendar Enhancements
Fully integrate timetable and calendar functionality for a complete academic planner.

Database Integration
Transition from local storage to a database like Firebase for real-time sync across devices.

User Authentication
Allow users to sign up and log in for personalized experiences.

Export & Import
Add options to export notes and tasks for backup or sharing.

🌟 Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch:
bash
Copy code
git checkout -b feature-name
Make your changes and commit:
bash
Copy code
git commit -m "Add feature"
Push to your branch:
bash
Copy code
git push origin feature-name
Create a pull request.
