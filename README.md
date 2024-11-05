# PFE-Platform

A full stack web application built with **Laravel 11** and **React** to automate and manage Master’s final-year projects (PFE). This platform facilitates communication and organization among students, teachers, and companies, streamlining the complex workflow of project proposals, supervision assignments, and defense scheduling.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Management**: Allows administrators to import, add, edit, and delete users (students, teachers, and companies) via CSV files.
- **Automated Email System**: Configurable email reminders for every project stage, ensuring users complete required steps on time.
- **PFE Proposals**:
  - Teachers, students, and companies can submit PFE proposals with detailed descriptions.
  - Users can view, edit, or delete their proposals before submission deadlines.
- **Project Supervision Assignment**:
  - Teachers select projects to supervise based on availability and preferences.
  - Students and companies receive notifications about supervision assignments.
- **Project Validation**:
  - Master’s coordinators review and validate project proposals.
  - Notifications inform users of project acceptance or requested modifications.
- **Student Project Selection**: Students can select a project from a tailored list of PFE options within their specialization.
- **Automated Project Allocation**: Projects are assigned based on student preferences and academic performance.
- **Defense Management**:
  - Automatic jury assignment based on teacher preferences, grades, and seniority.
  - Scheduling for defense dates, times, and venues, with notifications sent to all participants.

## Technologies Used

- **Backend**: Laravel 11
- **Frontend**: React
- **Database**: MySQL (or any database supported by Laravel)
- **Email System**: Laravel’s built-in email services for automated notifications

## Installation

### Prerequisites
Ensure you have the following installed:
- PHP >= 8.1
- Composer
- Node.js and npm
- MySQL or another database

### Backend Setup (Laravel 11)

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/PFE-Platform.git
   cd PFE-Platform/server
   ```

2. Install PHP dependencies:
   ```bash
   composer install
   ```

4. Migrate the database:
   ```bash
   php artisan migrate
   ```

5. Serve the application:
   ```bash
   php artisan serve
   ```

### Frontend Setup (React)

1. Navigate to the frontend directory:
   ```bash
   cd ../client
   ```

2. Install Node dependencies:
   ```bash
   npm install
   ```

3. Start the React development server:
   ```bash
   npm start
   ```

## Usage

1. **Administrator**:
   - Set up automated emails and manage user data.
   - Import CSV files for batch user data.

2. **Teachers**:
   - Submit and manage PFE proposals.
   - Choose projects for supervision and indicate jury preferences.

3. **Students**:
   - Propose PFE projects and select from available options.
   - Receive project assignments based on academic performance and preferences.

4. **Companies**:
   - Submit internship proposals for student PFEs.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure your code adheres to existing code standards.
