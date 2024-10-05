# Project Title: **TaskMaster**

## Description
**TaskMaster** is a task management application that helps individuals and teams keep track of their to-do lists, deadlines, and projects in an organized and efficient manner. Designed to streamline productivity, TaskMaster allows users to create, assign, and track tasks while providing real-time collaboration features for team-based workflows.

Key Features:
- Create and manage tasks with priority settings and deadlines.
- Assign tasks to team members and track progress.
- Visualize tasks with calendar and kanban views.
- Receive notifications for task deadlines and updates.
- Collaborative real-time editing for team projects.

## Setup Instructions

### Prerequisites
- **Node.js** (v16 or later)
- **npm** (v7 or later)
- **MongoDB** (v5 or later)
- **Git** (Optional, for cloning the repository)

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/TaskMaster.git
    ```
   
2. **Navigate to the project directory**:
    ```bash
    cd TaskMaster
    ```

3. **Install dependencies**:
    ```bash
    npm install
    ```

4. **Set up the environment variables**:
   Create a `.env` file in the root directory with the following details:
    ```
    MONGO_URI=<your-mongodb-connection-string>
    JWT_SECRET=<your-jwt-secret>
    PORT=5000
    ```

5. **Start the application**:
    ```bash
    npm run dev
    ```

### Running the Application Locally

Once the server is running, the application will be available at `http://localhost:5000`.

To run the app in production mode:
```bash
npm run start
