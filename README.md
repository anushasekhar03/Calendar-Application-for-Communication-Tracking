# Calendar Application for Communication Tracking

## Objective

This application helps organizations maintain and track professional interactions with other companies. It centralizes communication records, enables timely follow-ups, and provides a structured interface for managing past and future engagements.

---

## Features

### Admin Module
- **Company Management**: Add, edit, and delete company details, including names, locations, LinkedIn profiles, emails, and phone numbers.
- **Communication Method Management**: Define and sequence communication methods (e.g., LinkedIn Post, Email, Phone Call).

### User Module
- **Dashboard**: 
  - Grid view for tracking companies, last five communications, and next scheduled communications.
  - Color-coded highlights for overdue (red) and due-today (yellow) tasks.
- **Communication Logging**:
  - Record communication type, date, and notes.
  - Reset task highlights after logging.
- **Notifications**: Display overdue and today's communication tasks with a badge icon for counts.
- **Calendar View**: Visualize past and upcoming communications.

### Reporting and Analytics Module (Optional)
- Communication frequency and effectiveness reports.
- Overdue communication trends.
- Downloadable reports in PDF/CSV formats.
- Real-time activity log.

---

## Tech Stack

### Frontend
- **React.js**
- **Tailwind CSS**
- **FullCalendar** (for calendar UI)

### Deployment
- **Frontend**: Vercel, Netlify, or GitHub Pages

---

## Prerequisites

- Node.js and npm

---

## Installation

### Clone the Repository
```bash
git clone https://github.com/anushasekhar03/Calendar-Application-for-Communication-Tracking.git
cd Calendar-Application-for-Communication-Tracking
```

### Frontend Setup
1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the frontend application:
   ```bash
   npm start
   ```
3. Access the application at `http://localhost:3000`.

---

## Deployment

1. Build the frontend:
   ```bash
   npm run build
   ```
2. Deploy the built files using Vercel, Netlify, or GitHub Pages.

---

## Usage

### Admin Module
- Add company details and communication methods through the admin interface.

### User Module
- Log communications and track tasks through the dashboard and calendar.
- Stay updated with notifications for overdue and due-today tasks.

---


## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For any queries or suggestions, feel free to reach out:
- **Email**: anushasekhar302002@gmail.com
- **GitHub**: [anushasekhar03](https://github.com/anushasekhar03)
