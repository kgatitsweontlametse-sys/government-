# government-# 🏛️ Mini E-Government Portal

A simple full-stack web application that allows citizens to submit service requests (e.g., ID renewal, housing queries) and view their status. Built to demonstrate SDLC principles, backend development, and responsive frontend design.

## 🔧 Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP, MySQL
- **Architecture:** Modular folder structure
- **Testing:** Manual black-box testing + planned unit tests

## 📦 Features
- Submit service requests via web form
- Store requests in MySQL database
- View request status (admin dashboard planned)
- AJAX-based form submission
- SDLC documentation and BPMN diagram included

## 📁 Folder Structure

## 🚀 How to Run
1. Clone the repo
2. Import `requests.sql` into MySQL
3. Update `db.php` with your DB credentials
4. Open `index.html` in browser and test form submission

## 📈 SDLC & Documentation
- Followed Waterfall model: Requirements → Design → Implementation → Testing → Deployment
- BPMN diagram included to show request flow
- Future plans: Admin dashboard, authentication, unit testing

## 🧪 Testing Strategy
- Manual black-box testing for form submission
- Planned PHPUnit tests for backend logic
- UI tested across Chrome and Firefox

## 📄 License
MIT License
# 📈 Software Development Lifecycle – Mini E-Government Portal

## 1. Requirements Gathering
- Citizens need a way to submit service requests online
- Admins need to view and manage requests
- System must be simple, secure, and scalable

## 2. Design
- Frontend: HTML/CSS form with JavaScript for interactivity
- Backend: PHP scripts for data handling and MySQL for storage
- BPMN diagram created to visualize request flow

## 3. Implementation
- Developed modular PHP scripts for form handling
- AJAX used for smooth user experience
- Database schema created for request tracking

## 4. Testing
- Manual black-box testing for form submission and data storage
- UI tested on multiple browsers
- Future unit tests planned using PHPUnit

## 5. Deployment
- Local deployment for testing
- GitHub repo created with documentation
- Future deployment planned on Netlify or Heroku

## 6. Maintenance & Future Enhancements
- Add admin dashboard to manage requests
- Implement login system for authentication
- Add email notifications for request updates
