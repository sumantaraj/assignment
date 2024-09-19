# Interactive Kanban Board Application

## Overview

This project is an interactive Kanban board application built using **ReactJS** that interfaces with the following API:  
[API Endpoint](https://api.quicksell.co/v1/internal/frontend-assignment)

The goal is to display a dynamic and responsive Kanban board where users can group and sort tickets based on their preferences. The application does not utilize any external CSS libraries (like Bootstrap or Tailwind) or frameworks (such as Next.js), instead relying on pure React and CSS, with the option to use Styled JSX.

## Features

### Grouping Options
The application offers three distinct ways to group the tickets:
1. **By Status**: Group tickets by their current status (e.g., Open, In Progress, Done).
2. **By User**: Group tickets by the assigned user.
3. **By Priority**: Group tickets by their priority level:
    - Urgent (Priority level 4)
    - High (Priority level 3)
    - Medium (Priority level 2)
    - Low (Priority level 1)
    - No priority (Priority level 0)

### Sorting Options
The Kanban board allows users to sort tickets in two different ways:
1. **By Priority**: Sort tickets in descending order of priority.
2. **By Title**: Sort tickets in ascending alphabetical order based on their title.

### Persistence of User View
The application remembers the user's selected grouping and sorting options even after a page refresh, ensuring a seamless experience.

### API Data
The Kanban board is populated with data from the provided API, which includes ticket details like title, status, user, and priority level. The API returns the following priority levels:
- 4: Urgent
- 3: High
- 2: Medium
- 1: Low
- 0: No priority

### Responsiveness
The UI is designed to be fully responsive and visually appealing across different devices, ensuring optimal usability on both desktop and mobile screens.

## Technologies Used

- **ReactJS**: Core library for building the user interface.
- **Styled JSX**: For adding scoped CSS styles to components.
- **Pure CSS**: All styling is done using plain CSS, no third-party CSS frameworks or libraries are used.

## How to Run the Application

1. Clone the repository:
`

2. Install dependencies:
   \```bash
   npm install
   \```

3. Start the application:
   \```bash
   npm start
   \```

4. Open the application in your browser at `http://localhost:3000`.




