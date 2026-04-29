<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Atif%20Zeya&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Backend%20Developer%20%7C%20Java%20%7C%20Spring%20Boot&descAlignY=58&descSize=18&descColor=a0aec0" />
</p>

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=4EA8DE&center=true&vCenter=true&width=700&lines=Java+Backend+Developer;Spring+Boot+%7C+REST+APIs+%7C+PostgreSQL;Building+Real-World+Full-Stack+Apps;Open+to+Fresher+%2F+Junior+Backend+Roles" />

<br/>

[![Profile Views](https://komarev.com/ghpvc/?username=AtifZeya84&label=Profile+Views&color=4ea8de&style=flat-square)](https://github.com/AtifZeya84)
&nbsp;
[![GitHub followers](https://img.shields.io/github/followers/AtifZeya84?label=Followers&style=flat-square&color=4ea8de)](https://github.com/AtifZeya84)

</div>

---

## 👨‍💻 About Me

Hey, I'm **Atif** — a backend developer from Bengaluru, currently studying at **Maulana Azad College of Engineering & Technology, Patna**. I spend most of my time building REST APIs and full-stack apps with Java and Spring Boot. I like writing clean, structured code and turning real-world problems into working software.

- 🏗️ Built a full-stack **Loan Origination System** with 3-role JWT auth workflow
- 💸 Built a full-stack **Expense Tracker** with category analytics and a dashboard
- 🔐 Comfortable with **Spring Security**, JWT
- 🚀 Actively looking for **fresher / junior backend developer** roles

---

## 🛠️ Tech Stack

### Languages & Core
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Frameworks & Libraries
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

### Database
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white)

### Tools & DevOps
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🏦 Loan Origination System
**Enterprise-grade loan management platform**

A full-stack loan processing platform built with dual-approval workflow and JWT-based role security. Handles the complete lifecycle from customer submission to final approval.

**Highlights**
- 👥 3-role system — Customer → Maker → Checker
- 🔐 JWT auth with role-based access control
- 📄 Document upload & eligibility checker
- 🔑 Forgot/reset password with security questions
- 📖 Swagger docs at `/swagger-ui.html`
- 🔔 Real-time status notifications

**Application Flow**
```
Customer Submits ──► WITH_MAKER
                         │
              ┌──────────┴──────────┐
           Approve               Reject
              │                     │
         WITH_CHECKER           REJECTED
              │
     ┌────────┴────────┐
  Approve            Reject
     │                  │
 APPROVED           REJECTED
```

**Tech Stack**

| Layer | Technology |
|-------|-----------|
| Frontend | React 18, Bootstrap 5, Axios |
| Backend | Java 17, Spring Boot 3.2 |
| Auth | JWT (jjwt), Spring Security |
| Database | PostgreSQL, Spring Data JPA |
| API Docs | SpringDoc OpenAPI / Swagger |

[![View Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AtifZeya84/loan-approval-system)

</td>
<td width="50%" valign="top">

### 💸 SpendLog — Expense Tracker
**Full-stack personal finance dashboard**

A feature-rich expense management app with a live dashboard, interactive charts, category budgeting, and CSV export. Built with Spring Boot backend and a fully custom frontend.

**Highlights**
- 📊 Dashboard with spending trend & donut charts
- 🗂 Category filtering — Food, Transport, Shopping & more
- 💰 Per-category monthly budget with progress tracking
- ↩️ Undo delete with 5-second recovery window
- ⬇️ CSV export for all expenses
- 🔍 Real-time search & multi-sort options
- 🌙 Dark / Light mode toggle
- 🔌 RESTful API with 7 endpoints

**API Endpoints**

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/expenses` | All expenses |
| GET | `/api/expenses/{id}` | Single expense |
| GET | `/api/expenses/category/{cat}` | Filter by category |
| GET | `/api/expenses/total` | Total amount |
| POST | `/api/expenses` | Create expense |
| PUT | `/api/expenses/{id}` | Update expense |
| DELETE | `/api/expenses/{id}` | Delete expense |

**Tech Stack**

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, Bootstrap 5, Vanilla JS |
| Backend | Java 17, Spring Boot 3.2 |
| Database | PostgreSQL, Spring Data JPA |
| Charts | Chart.js |

[![View Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AtifZeya84/Expense-Tracker-App)

</td>
</tr>
</table>

---

## 🏅 Certifications

<table>
<tr>
<td align="center" width="50%">

<img src="https://hrcdn.net/fcore/assets/brand/logo-new-white-green-a5cb16e0ae.svg" width="140" style="background:#1ba94c;padding:10px;border-radius:8px"/>

### Java (Basic)
**HackerRank Certified**

Covers core Java concepts including data types, control flow, OOP, exception handling, and collections.

[![View Certificate](https://img.shields.io/badge/View_Certificate-1BA94C?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/certificates/2e17c992b364)

</td>
<td align="center" width="50%">

<img src="https://hrcdn.net/fcore/assets/brand/logo-new-white-green-a5cb16e0ae.svg" width="140" style="background:#1ba94c;padding:10px;border-radius:8px"/>

### SQL (Basic)
**HackerRank Certified**

Covers SQL fundamentals — SELECT queries, filtering, joins, aggregations, and subqueries.

[![View Certificate](https://img.shields.io/badge/View_Certificate-1BA94C?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/certificates/59fb299a90a8)

</td>
</tr>
</table>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=AtifZeya84&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" width="48%"/>
&nbsp;
<img src="https://github-readme-streak-stats.herokuapp.com/?user=AtifZeya84&theme=tokyonight&hide_border=true" width="48%"/>

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AtifZeya84&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" width="40%"/>

</div>

---

## 🌐 Connect With Me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-AtifZeya84-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AtifZeya84)
[![Gmail](https://img.shields.io/badge/Gmail-Drop_a_Mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gk0215312@gmail.com)
[![HackerRank](https://img.shields.io/badge/HackerRank-Profile-1BA94C?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/AtifZeya84)

</div>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer"/>
</p>

<div align="center">
  <i>"Code is not just syntax — it's problem solving."</i>
</div>
