# 📘 Vocational Training Center - Dehiwala

### 🔹 Project Name: `Vocational-Training-Center-Dehiwala`

---

## 📝 Description

**"Vocational Training Center - Dehiwala"** is a Windows desktop application developed specifically for the government institution Vocational Training Center - Dehiwala. This software is designed to provide **student learning access management** and o**nline lesson control** within the institution.

The system allows the **Admin** to create student accounts via **Google Forms**, storing usernames and passwords in an **online database**. Students can log in from anywhere, and their credentials are verified online before granting access.  

Admins have full control over:
- Which **lessons** each student can access  
- How many **practicals** and **assignments** per lesson are available to each student  

The system includes **7 main lessons**, each containing **10 practicals** and **10 assignments** (totaling **70 practical PDFs** and **70 assignment PDFs**). Access restrictions ensure that students can only view the materials assigned to them.  

Additionally, students can:
- **Send completed practicals or assignments** to their teacher via the built-in email function  
- Select one or multiple files and send them directly, with the system including the student’s name and lesson details in the email  

A key feature is the **Mega Cloud-based PDF update system**. When the student clicks the **Update** button, the software downloads the latest PDFs from Mega Cloud, encrypts them, and saves them locally.  
This allows teachers to update content instantly without requiring a software reinstall or developer involvement.  

Overall, this system streamlines **course material delivery**, **access control**, and **assignment submission**, making learning more organized and efficient.  

---

## 🛠️ Built With

- **Programming Language**: C#  
- **Platform**: Windows Desktop Application  
- **Framework**: .NET Framework  
- **Database**: Cloud-hosted online database  
- **Cloud Storage**: Mega Cloud (for PDF storage and updates)  
- **Email Integration**: SMTP for sending student submissions  
- **UI Design**: Guna UI2 for modern interface  

---

## 💾 Installation Guide

1. **Download** the `Vocational-Training-Center-Dehiwala` installer folder.  
2. Open the `Debug` (or installer) folder.  
3. Double-click the `.msi` installer file.  
4. Click **Next** on the welcome screen.  
5. Select the installation location.  
6. Click **Next** to proceed.  
7. Confirm and click **Install**.  
8. Wait until the setup completes.
9. You can now open the system using the desktop shortcut that was created during installation.

![Desktop Shortcut](https://drive.google.com/uc?export=view&id=1cHFkJ6lQvIBZ9m7ILFe3Tn0pEsIMJieX)

---

## 🔐 Admin Account Creation

Admins can create student accounts via **Google Forms**:  
- Fields:  `Username`, `Password`  
- The submitted credentials are stored securely in the system’s **online database**.

![Google Sheet](https://drive.google.com/uc?export=view&id=1wblEszN2yvYjuZKpbiuH6K496wTag4d6)

---

## 🔓 Student Login

- Students enter their **username** and **password** to log in.  
- Credentials are **verified online** before granting access.  
- Successful login allows access only to **lessons, practicals, and assignments** assigned by the admin.

![Login Page](https://drive.google.com/uc?export=view&id=1h6YGehnVg4bTifDTAdZhoi3JB4xL84lo)
---

## 📚 Course Structure

The system contains **7 Lessons**:

1. Introduction to Computer  
2. Operating System  
3. Word Processing  
4. Presentation Applications  
5. Introduction to Spreadsheet & MS Excel  
6. Introduction to Databases & MS Access  
7. Internet and e-Mail


![Home Page](https://drive.google.com/uc?export=view&id=11ReF-P0K_B7egmv8R0cdBf1bvZ-ABTTG)

---

## 📂 Content Details

- Each **Lesson** contains:  
  - **10 Practicals** (PDF)  
  - **10 Assignments** (PDF)  

**Total PDFs**:  
- Practicals → **70 PDFs**  
- Assignments → **70 PDFs**  

![PDF](https://drive.google.com/uc?export=view&id=1Q2zfGu7rBOElnlNQmPoIBbf-OCxd7a2H)

---

## 🎯 Access Control

Admin can **assign access limits** for each student:
- **Lesson Access:** Determines which lessons the student can open
- **Practical Access per Lesson:** Determines how many practicals within a lesson the student can view  
- **Assignment Access per Lesson:** Determines how many assignments within a lesson the student can view

**Example:**  
If a student is assigned **3 lessons**, **8 practicals**, and **5 assignments**:
- Lesson 1: Practicals 1–10 accessible, Assignments 1–10 accessible
- Lesson 2: Practicals 1–10 accessible, Assignments 1–10 accessible
- Lesson 3: Practicals 1–8 accessible, Assignments 1–5 accessible
- Lesson 3: Practicals 9 & 10 No access, Assignments 6–10 No access
- Lesson 4–7: No access to practicals or assignments  
---

## 📤 Sending Work via Email

Students can send completed files to their teacher:

1. Login with username & password.  
2. Open the relevant lesson (e.g., Word Processing).  
3. Click **Send Mail**.  
4. Select one or multiple files to send.  
5. Click **Send**.  

The teacher receives:  
- Student’s **Name**  
- **Lesson Name**  
- All **attached files**  

![Send Mail](https://drive.google.com/uc?export=view&id=11mn5pybMEFpCFVrRF5M9qcQ3u_BCb1ig)

---

## 🔄 PDF Update System (Mega Cloud Integration)

- **Update Button** on Home Page:  
  - Downloads the latest PDFs from **Mega Cloud**.  
  - Files are **encrypted** before saving locally.  

✅ **Benefits**:  
- Teachers can update PDFs anytime without developer intervention.  
- Students receive the latest materials **without reinstalling the software**.  
