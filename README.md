# Jenkins with java-application
- CI/CD pipeline Practice ♾️
- Maven 🪶
- Nexus 🗃️
- sonarqube 🔎
- Tomcat 🌐
# 🧩 Project Infrastructure Setup — Role & Tool Configuration
## 🏗️ Overview
This document defines the user roles, toolchain configuration, and deployment workflow for a Java-based project deployed via Tomcat, with artifacts stored in Nexus, and quality analyzed by SonarQube.

### Roles & Permissions
| Role | username | Access Level |
| ------------- | ------ | -------|
| 🧑‍💻 Developer  |  Sam |  Build-only permissions  |
| 👨‍🏫 Team Lead| Rocky |Configuration-only permissions|
| ⚙️ DevOps Engineer | Bob|Admin privileges|

example scenario ⬆️
## 👤 User Creation Steps (Jenkins)
1. Login as Admin (DevOps Engineer)
2.  Create user Go to : ``` Manage Jenkins → Users → Create User ``` (add user-detail like the table )
3.  download plugin  - ```Role-based Authorization Strategy``` and in ```Manage Jenkins → security → Authorization( Role-based Authorization Strategy)``` - save Changes
  
4.  Create Roles Go to : ``` Manage Jenkins → Security → Manage and Assign Roles ```
    - developer → Build permission only
    - team_lead → Configure permission only
    - devops_engineer → Full permissions
6. Save & Apply changes ✅


---
# 🧠 Jenkins Master–Slave Setup
-  🔗setupLink   [Master–Slave 📡](https://github.com/solaijr11/Jenkins-Master-slave) 
