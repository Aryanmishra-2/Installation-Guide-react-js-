# React.js Installation Guide

---
## Author Information

| Created         | Created on         | Version          | Last updated by   | pre Reviewer       | L0 Reviewer     | L1 Reviewer          |    L2 Reviewer    |
|-----------------|--------------------|------------------|-------------------|--------------------|-----------------|----------------------|-------------------|
| Aryan mishra    |17-07-2025          | V.1        |                         |       Siddharth    |                 |                      |                   |
 
 ---

##  Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation Steps](#️installation-steps)
- [Step 1: Install Node.js and npm](#step-1-install-nodejs-and-npm)
- [Step 2: Verify Node.js and npm Installation](#step-2-verify-nodejs-and-npm-installation)
- [Step 3:  Step 3: Create a React App](#Step-3-Create-a-React-App)
- [Step 4: Create a New React App](#step-4-create-a-new-react-app)
- [Step 6: Start the Development Server](#step-6-start-the-development-server)
- [Troubleshooting](#Troubleshooting)
- [Conclusion](#Conclusion)
- [Contact Information](#Contact-Information)
- [References](#References)

---

## Introduction

React.js is a JavaScript library used to build fast and interactive user interfaces. This guide will help you set up a local React development environment using `create-react-app`.

---

## Prerequisites

Make sure you have the following installed:

- **Operating System**: Windows / macOS / Linux
- **Node.js** (LTS version recommended)
- **npm** (comes with Node.js)
- Terminal / Command Prompt access

---

## Installation Steps

### Step 1: Install Node.js and npm

Download and install Node.js from the official website:

🔗 https://nodejs.org/

Install the **LTS (Recommended)** version.

> `npm` (Node Package Manager) is automatically installed with Node.js.

---

## Step 2: Verify Node.js and npm Installation

```bash
node -v
npm -v
```
---
- You should see version numbers. Example:-

```bash
v18.17.0
9.8.0
```
---

| No | Description |
|---|-------------|
| 1 | **npm (Node Package Manager)** is used to install all the dependencies needed when creating a React application. These include packages like React itself, Webpack, Babel, etc. |
| 2 | All of these packages are installed via **npm**. |
| 3 | `npx create-react-app` is also an **npm command** that provides a ready‑made React project template. |

---

## Step 3: Create a React App

```bash
npx create-react-app <project name>
```
- This command downloads a template for a React application.
- It internally uses **npm** and **Node.js**.
- The development server that runs with `npm start` will not work without **Node.js**.

---

## Step 4: Start Development Server
- Navigate into the project directory:
```bash
cd my-app
npm start
```
---
## Troubleshooting

| Problem                    | Solution                                                                 |
|---------------------------|--------------------------------------------------------------------------|
| `npx: command not found`  | Ensure that Node.js and npm (version ≥ 5.2.0, which includes npx) are properly installed :contentReference[oaicite:1]{index=1} |
| `Port already in use`     | Run the app on a different port, e.g.: `npm start -- --port=3001`, or free the port first (e.g. `lsof -i tcp:3000 && kill -9 <PID>`) :contentReference[oaicite:2]{index=2} |
| Permissions error         | On Linux/macOS, run the command with `sudo` to gain elevated privileges |

---

## Conclusion
Node.js and npm are essential for building and running React.js applications—not only in production but also during development. They are required to install dependencies, start the development server, and manage the build process.

---
## Contact Information

| Name          | Email                                |
| ------------- | ------------------------------------ |
| Aryan Mishra  | aryan.mishra@mygurukulam.co          |

---

## References  

|  Name                                  | References                                                                                                            |
|----------------------------------------|---------------------------------------------------------------------------------------------------------|
| **Node.js**                            | [Link](https://nodejs.org)                                                                                        |
| **React**                              | [Link](https://react.dev)                                                                                        |
 


