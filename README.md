# Project Name: Mission Management System

## Description
This project is a Mission Management System developed using Angular, .NET C#, and PostgreSQL. The system provides a web API for login registration and the creation of admin and user profiles. It offers functionalities for both admins and users, with different capabilities based on their roles.

### Admin Features:
- Add, delete, and update users
- Add, delete, and update missions
- Add, delete, and update mission skills
- Add, delete, and update mission themes
- Add, delete, and update mission applications

### User Features:
- Apply for missions
- Update user profiles

## Technologies Used
- **Frontend:** Angular
- **Backend:** .NET C#
- **Database:** PostgreSQL

## Progress Bar
Below is a visual representation of the technology usage in the project.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Progress Bar</title>
  <style>
    .progress-bar {
      width: 100%;
      background-color: #f3f3f3;
      border: 1px solid #ddd;
      border-radius: 5px;
      overflow: hidden;
      margin: 10px 0;
    }
    .progress {
      height: 30px;
      border-radius: 5px;
      line-height: 30px;
      color: white;
      text-align: center;
      transition: width 0.3s;
    }
    .angular {
      background-color: #dd0031;
      width: 40%; /* Example percentage */
    }
    .dotnet {
      background-color: #512bd4;
      width: 35%; /* Example percentage */
    }
    .postgresql {
      background-color: #336791;
      width: 25%; /* Example percentage */
    }
  </style>
</head>
<body>
  <h2>Technologies Usage Progress</h2>
  <div class="progress-bar">
    <div class="progress angular">Angular (40%)</div>
  </div>
  <div class="progress-bar">
    <div class="progress dotnet">.NET C# (35%)</div>
  </div>
  <div class="progress-bar">
    <div class="progress postgresql">PostgreSQL (25%)</div>
  </div>
</body>
</html>
