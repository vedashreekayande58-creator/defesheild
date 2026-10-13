# # 🏢 Tathastu — Student Accommodation & Mess Finder

[![Node.js](https://img.shields.io/badge/Node.js-v18+-green.svg)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express-v4.19-blue.svg)](https://expressjs.com/)
[![SQLite](https://img.shields.io/badge/SQLite-v3-sky.svg)](https://www.sqlite.org/)
[![License: ISC](https://img.shields.io/badge/License-ISC-yellow.svg)](https://opensource.org/licenses/ISC)

**Tathastu** is a lightweight, full-stack platform designed to simplify the struggle students face when searching for housing and food options near their colleges. It provides centralized information on Paying Guest (PG) accommodations, daily mess facilities, and allows seamless visit scheduling.

---

## 📌 Project Overview

Tathastu solves a major challenge for college students and out-of-station youth by aggregating essential accommodation metrics—such as monthly rent, gender availability, proximity to transit, medical facilities, and daily utilities. The platform features an interactive frontend paired with a fast asynchronous REST API backend.

---

## ✨ Features

- 🏠 **PG Accommodations:** Browse PGs filtered by rent, gender options (Boys / Girls / Co-Ed), nearby colleges, and transit distances.
- 🍲 **Mess & Canteen Directory:** View monthly subscription rates, single-meal pricing, special menu items, and daily meal plans.
- 📅 **Schedule Visits:** Book physical visits to PGs directly through an interactive appointment handler.
- ⭐ **Student Reviews:** Access real feedback from fellow students regarding safety, Wi-Fi, and amenities.

---

## 🛠️ Open-Source Tech Stack

### **Backend**
* **Runtime:** [Node.js](https://nodejs.org/) — An event-driven, non-blocking JavaScript runtime.
* **Framework:** [Express.js](https://expressjs.com/) — Fast, minimalist web framework for handling API routing.
* **Database:** [SQLite3](https://github.com/TryGhost/node-sqlite3) — Lightweight relational database engine configured in-.

### **Frontend**
* **Markup & Styling:** HTML5, CSS3
* **Scripting:** Vanilla JavaScript (ES6+ with native Fetch API)

---

## 📁 Repository Structure

```text
tathastu/
├── server.js        # Express API server & SQLite database seed logic
├── index.html       # Client interface with dynamic API integration
├── package.json     # Project dependencies and script configurations
├── .gitignore       # Exclusion rules for git tracking
└── README.md        # Project documentation
