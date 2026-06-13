# Nexa Mail Client

[![GitHub Repository](https://img.shields.io/badge/Repo-HarmonyNextMail-blue)](https://github.com/xiaobocm/HarmonyNextMail)  
[![Platform](https://img.shields.io/badge/platform-HarmonyOS%20NEXT-brightgreen)](https://developer.harmonyos.com/)  
[![Language](https://img.shields.io/badge/language-ArkTS-9cf)](https://developer.harmonyos.com/cn/docs/documentation/doc-guides/arkts-get-started-0000001820880589)

A better email solution built specifically for **native HarmonyOS NEXT** users.  
Developed with passion by a junior high school student.

> **Repository created on:** June 13, 2026  
> **Target OS:** HarmonyOS NEXT (API 12+)

---

## 📱 Overview

HarmonyNext Mail Client is a lightweight, modern email app that deeply integrates with HarmonyOS NEXT’s distributed capabilities. Unlike traditional email clients, our app focuses on **multi-account management**, **calendar & scheduling**, and **contact management** — with exciting AI features coming soon.

This project is built entirely with **ArkTS** and follows HarmonyOS’s design guidelines to deliver a seamless native experience.

---

## ✨ Current Features

- **Multi-Account Management** – Add and switch between multiple email accounts (IMAP/SMTP, Exchange support planned).
- **Calendar & Schedules** – View, create, and sync calendar events. Integrate with system calendar.
- **Contact Management** – Manage contacts from different accounts, sync with device contacts.

> All features are designed to work offline-first and sync seamlessly when online.

---

## 🚀 Future Plans (Roadmap)

- 🤖 **AI-Powered Assistant** – Smart email categorization, one‑click reply suggestions, and automatic schedule extraction from emails.
- 📎 **Advanced Attachments** – Cloud integration with HarmonyOS Share.
- 🔔 **Unified Notifications** – Customizable rules per account.
- 🌙 **Dark Mode & Themes** – Fully adaptive to system settings.

---

## 🛠️ Tech Stack

| Area          | Technology                          |
|---------------|-------------------------------------|
| Language      | ArkTS (TypeScript superset)         |
| UI Framework  | ArkUI (Declarative)                 |
| Data Storage  | Preferences + RelationalStore (SQLite) |
| Network       | @ohos.net.http + IMAP/SMTP libraries |
| Build System  | DevEco Studio / hvigor              |

---

## 📦 Installation & Usage

Since this project is in early development, pre‑built binaries are not yet available.  
To build and run from source:

1. **Clone the repository**  
   ```bash
   git clone https://github.com/xiaobocm/NexaMail.git
