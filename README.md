video Link: https://drive.google.com/file/d/1CbXuMYEuEpZxcHHVsqCKHjfSZjQ1aOAU/view?usp=sharing


# 🚀 URL Shortener — Docker Setup Guide

This guide explains how to set up and run the **URL Shortener** application using **Docker**, **VS Code Dev Containers**, and **Git submodules**.

---

## 📂 Repository

GitHub Link: 
root project link: https://github.com/AbhishekSankhla121/url-shortener
frontend project link: https://github.com/AbhishekSankhla121/urlshortener-frontend**
backend project link: https://github.com/AbhishekSankhla121/urlshortener-backend

others
application setup video link: https://drive.google.com/file/d/1CbXuMYEuEpZxcHHVsqCKHjfSZjQ1aOAU/view?usp=sharing
test-frontend-application link: https://urlshortener-frontend-s5vj.onrender.com
test-backend-application link: https://urlshortener-backend-8oji.onrender.com
Candidate ID: Naukri1125
---

## 🛠️ Requirements

Make sure these tools are installed on your system:

### **Tools**
- Docker
- Visual Studio Code
- Git

### **VS Code Extensions**
- Dev Containers (by Microsoft)

---

## 🧩 Project Structure Overview

This repository uses **Git submodules** for:
- `urlshortener-frontend`
- `urlshortener-backend`

Both projects run inside Docker Dev Containers.

---

## ⚙️ Setup Instructions

Follow these steps to set up the application:

1️⃣ **Open your terminal in the home directory**

2️⃣ **Clone the main repository**     :   git clone https://github.com/AbhishekSankhla121/url-shortener

3️⃣ **Enter the project folder**      :   cd url-shortener

4️⃣ **Install Git submodules**        :   git submodule update --init --recursive

5️⃣ **Open the project in VS Code**   :   code .
6️⃣ **Install Dev Containers extension** : Extensions → Search “Dev Containers” → Install
7️⃣ **Rebuild Dev Containers Open Command Palette:**: Ctrl + Shift + P → ">Dev Containers: Rebuild Without Cache"
Choose environment:

->**Frontend**

->**Backend**

8️⃣ Done! 🎉

Your application is now fully set up inside Docker Dev Containers.

