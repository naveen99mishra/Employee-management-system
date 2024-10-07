# Employee Management System

## #SiteFeatures

### Admin Panel:
- Separate login systems for Admins and Employees.
- Admin can:
  - Add new employees.
  - Assign individual projects.
  - Check employee salaries and project status.
  - Grade projects and update the leaderboard.
- Leaderboard updates based on project marks.
- Employees receive bonuses over their base salary based on their project marks.

### User Panel:
- Employees can:
  - View the leaderboard, project deadlines, and salary details.
  - View and update their profile information.
  - Submit projects.
  - Apply for leave.

## #TechnologiesUsed
- HTML
- CSS
- JavaScript
- MySQL

### Additional Resources:
- ER Diagram and Relational Schema are provided as PDFs.

## #InstallationGuide

1. Clone the repository to your localhost folder.
    ```bash
    git clone <repository_url>
    ```
2. Launch XAMPP (or any similar service) and start Apache and MySQL.
3. Go to phpMyAdmin, create a database named **370project**, and import the `370project.sql` file.
4. Launch the site in your browser.

## #LoginInformation

### Admin Panel:
- **Username:** admin  
- **Password:** admin

### User Panel:
- **Username:** User's email address  
- **Password:** 1234 (default, can be changed by the user)

## #ProjectStructure

```bash
project_root/
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── sql/
│   └── 370project.sql
├── index.html
├── admin_panel.html
└── user_panel.html
