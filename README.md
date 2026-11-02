# Better Grade Calculator

A web application that allows students to easily track their grades, and calculate their semester GPA in one tab.

## The Problem

Brightspace makes it difficult to get a clear overview of grades across multiple courses. Students often have to switch between different tabs and manually calculate their grades and GPA. This app aims to make grade tracking simpler and more organized.

## How It Works

Better Grade Calculator provides a dashboard where students can view and manage their coursework and grades.

- Display all courses and grades on one dashboard.
- Add, edit, and delete courses and assignments.
- Track upcoming and completed assignments.
- Calculate weighted course grades in real time.
- Calculate semester GPA using Purdue's grading scale and course credits.
- Save user data locally between sessions.

### System Diagram

![System Diagram](docs/system-diagram.png)

## Tech Stack

- **Languages:** TypeScript, HTML, CSS
- **Frontend:** React
- **Styling:** Tailwind CSS
- **Development Tools:** VS Code, Git, GitHub
- **Storage:** Browser localStorage (JSON)
- **External APIs:** None for the MVP

## Setup

The project is currently in the planning phase. Once development is complete, users will be able to run the application locally.

1. Clone the GitHub repository.
2. Navigate to the project directory.
3. Install the required dependencies.
4. Start the local server.

```bash
git clone https://github.com/YOUR_USERNAME/better-grade-calc.git
cd better-grade-calc
npm install
npm run dev
```

## Usage

Once the application is running:

1. Open the localhost address provided by the development server.
2. Add courses and their credit hours.
3. Enter completed and upcoming assignments.
4. Enter grades and assignment weights.
5. View calculated course grades and semester GPA on the dashboard.

## Roadmap

Future features planned for V2.0 and beyond:

- [ ] Integrate with the Brightspace API for automatic grade syncing.
- [ ] Add a what-if grade calculator.
- [ ] Display grade history and progress charts.
- [ ] Implement assignment deadline notifications.
- [ ] Support multiple semesters.

## Project Documentation

- [Eisenhower Matrix](docs/eisenhower-matrix.txt)
- [System Diagram](docs/system-diagram.png)

## Author

[Krish Pipaliya](https://github.com/starplexo)