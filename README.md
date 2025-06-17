# IST101G1-S2-Midterm-BrahndonAGP
# H2O Challenge - MidTerm Exam  
**Course:** DevOps Infrastructure Level 1  
**Institution:** Canadian College of Technology and Business (CCTB)  
**Instructor:** Washington Valencia  
**Student:** Brahndon Alexis Guajardo Perez (CT1007951)  

---

## Project Description

This is a web application that helps users track their daily water intake, aiming to reach 2 liters per day.  
The app is divided into two panels:

- **Left Panel**: Shows a visual representation of remaining water with a large cup.
- **Right Panel**: Lets users click on small 250ml cups to track their progress.

---

## Technologies Used

- HTML5 + CSS3  
- JavaScript (Vanilla)  
- Git + GitHub  
- AWS EC2, Launch Template, Auto Scaling Group, Load Balancer  
- Linux (Amazon Linux 2023)  
- Apache Web Server  
- Stress testing with `stress`

---

## Features Implemented

- Displays EC2 Public IP dynamically using `https://api.ipify.org`
- Shows student name and current date automatically
- Responsive UI with real-time progress tracking
- Auto Scaling configuration based on CPU usage (>35%)
- Load Balancer setup to serve traffic across instances

---

## Required Screenshots

- `Screenshot1A_App_Instance1.png` – App with IP, name, and date
- `Screenshot1B/1C` – App on different instances (new IPs)
- `Screenshot2_CPU_Before.png` – CPU before stress test
- `Screenshot3_CPU_After.png` – CPU after stress test
- `Screenshot4_EC2_Before.png` – One EC2 instance
- `Screenshot5_EC2_After.png` – Multiple EC2 instances
- `Screenshot6_Final_App.png` – App working via Load Balancer

---

## GitHub Repository

[View this project on GitHub](https://github.com/BrahnGP/MidTerm_BrahndonAGP)

