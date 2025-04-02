```markdown
Campuslight Core Founding Team Challenge
```
# Online-Learning-Platform-Dashboard

## Problem Overview:
Build an interactive dashboard for an Online Learning Platform where students can track their courses, assignments, and progress. The platform should allow users to see a list of available courses, view their enrolled courses, and keep track of ongoing assignments.

You will need to use HTML, CSS, JavaScript, and ReactJS to create an interactive and functional UI. The dashboard should simulate a real-world online learning platform like Coursera, Udemy, or LinkedIn Learning.

## Features & Requirements:

### Landing Page:
- Create a landing page that welcomes users and provides an overview of the platform.
- The landing page should include options for signing up or logging in.

### User Authentication (Simulated):
- Simulate a login/signup process where users can input their credentials (e.g., email and password).
- Once logged in, redirect the user to the dashboard.

### Dashboard:
The main dashboard page should display the following:
- A list of available courses (e.g., Programming, Web Development, Data Science).
- A section for enrolled courses that the user is currently taking.
- A section showing ongoing assignments with deadlines.
- The current progress bar for each course (e.g., 70% completed).

### Course List:
Each course should display the following information:
- Course name
- Instructor name
- Short description
- "Enroll" button to add the course to the user's enrolled list.
- Once a course is clicked, show detailed course information.

### Assignments:
Display a list of ongoing assignments for each enrolled course.
Each assignment should include:
- Assignment title
- Due date
- Completion status (e.g., "Not started", "In Progress", "Completed").

### Progress Bar:
For each course, show a progress bar that indicates how much of the course the user has completed.
- Update the progress based on the assignments completed or lessons watched.

### CSS Styling & Responsiveness:
- The platform should be styled using CSS (use Flexbox or Grid for layout).
- The design should be responsive and work well on different screen sizes (desktop, tablet, mobile).

### ReactJS Functionalities:
- Use ReactJS to build components for courses, assignments, user authentication, and progress tracking.
- Use React Router for navigation between pages (e.g., landing page, login, dashboard).
- Store the data in React state for courses, assignments, and user progress.
- Optionally, you can use localStorage to persist user data such as courses and assignments.

### Challenge:
- Build the app using ReactJS for dynamic interaction.
- Create static data for courses, assignments, and users (this can be done as mock data or as an API simulation).
- Implement state management using React's `useState` and `useEffect`.
- Create a simple authentication flow (use mock authentication, no real backend required).
- Ensure the platform is responsive and looks clean on all devices.
```
## Project Structure:


Online-Education-Dashboard/
  ├── public/
  │   ├── index.html
  ├── src/
  │   ├── components/
  │   │   ├── CourseCard.js
  │   │   ├── CourseList.js
  │   │   ├── AssignmentList.js
  │   ├── App.js
  │   ├── index.js
  │   ├── App.css
  ├── package.json

```
## Implementation Steps:
```
### Setting Up the Project:
1. Initialize a React app using Create React App:
   ```bash
   npx create-react-app online-education-dashboard
   ```
2. Add any necessary libraries like React Router and styled-components if required.

### Landing Page:
- Create a simple page that welcomes users and gives them options to sign up or log in.

### Authentication:
- Create mock authentication using local state (e.g., simulate login with hardcoded credentials).

### Dashboard:
- Create a dashboard with sections for available courses, enrolled courses, and assignments.

### Courses and Assignments:
- Create course cards and an assignment list. You can mock the data for now in a JSON format or store it in an array.

### Progress Bar:
- Use a progress bar to show how much of the course is completed. Use state to track the progress.

### Styling and Responsiveness:
- Use CSS for styling and ensure the layout is responsive with media queries.

### Additional Features (Optional):
- **Filter Courses**: Add a filter to search and filter available courses based on categories.
- **API Integration**: If you want to make it more realistic, you can use a mock API or integrate an actual API for courses and assignments.
- **Dark Mode**: Add a dark mode toggle for the dashboard.

## All the best champions!
```

This **README.md** file retains all the content and structure of the problem description you provided, formatted for clarity and easy understanding. You can copy and paste it directly into your project repository.
