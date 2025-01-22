# TimeTalk - Historical Dialect Translator

TimeTalk is a web application that translates modern English text into various historical dialects using AI. Users can choose from different time periods including Caveman, Greek, Medieval, Shakespearean, Pirate, Colonial, and Future speak.

## Features

- Translation to 7 different historical dialects
- Interactive UI with period-themed backgrounds
- Auto-changing slideshow on homepage
- Real-time text translation using OpenAI's GPT-3.5
- Responsive design for all devices

## Technologies Used

### Frontend
- HTML5
- CSS3 (with custom animations)
- Vanilla JavaScript
- Custom image slideshow implementation

### Backend
- Node.js
- Express.js (v4.21.1)
- Packages:
  - axios (v1.7.7) - For making HTTP requests to OpenAI API
  - cors (v2.8.5) - For handling Cross-Origin Resource Sharing
  - dotenv (v16.4.5) - For environment variable management

### APIs
- OpenAI GPT-3.5 Turbo - For text translation/generation

### Deployment
- Frontend: Vercel
- Backend: Render
- Version Control: Git & GitHub

## Project Structure
project-root/
├── frontend/
│   ├── src/
│   │   ├── Dialects/
│   │   │   ├── Caveman/
│   │   │   ├── Colonial/
│   │   │   ├── Future/
│   │   │   ├── Greek/
│   │   │   ├── Medieval/
│   │   │   ├── Pirate/
│   │   │   └── Shakespearian/
│   │   ├── js/
│   │   ├── photos/
│   │   ├── Home.css
│   │   └── index.html
│   ├── package.json
│   └── .gitignore
│
└── backend/
├── server.js
├── .env
├── package.json
└── .gitignore
