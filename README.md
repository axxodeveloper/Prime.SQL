# <center>Prime SQL Visualizer & ERD Generator</center>


<br>

> **A Serverless, Offline-Capable SQL Live Previewer & Entity-Relationship Diagram (ERD) Generator.** No servers, no complex installations, and no internet dependencies. Just download, click, and design.

---
## Overview

**Prime SQL Visualizer** is a client-side database playground designed to make SQL practice, database schema design, and query testing frictionless. Powered by **PyScript** and **SQLite WebAssembly**, it executes real SQL commands instantly inside your browser.

With the integrated **Interactive ERD Generator**, you can visually model databases, create tables with a clean GUI, establish relationships, and automatically export your visual model as ready-to-run DDL SQL statements.

---
## Previews

### Screenshot

<img width="1913" height="1001" alt="preview2" src="https://github.com/user-attachments/assets/a3aeac14-1ee9-4cc1-88a9-fa79191fa79e" />

<br>

<img width="1912" height="999" alt="preview1" src="https://github.com/user-attachments/assets/15e53f44-314f-4c72-90df-f78cced9a372" />




---

  

## Features

  

*   **100% Serverless Execution**: No backends or network constraints. Powered entirely inside your browser sandbox by WebAssembly and PyScript.

*   **Fully Offline Capable**: Designed to run seamlessly directly from the local file system (`file://` protocol) by double-clicking the `index.html` file. Handles storage limitations gracefully.

*   **Monaco Code Editor**: Professional query editing with syntax highlighting, automatic theme toggles (Dark/Light mode sync), and bracket matching behavior.

*   **Live ERD Canvas**: Drag-and-drop layout engine designed with modern aesthetics. Synchronously connects visual relationships to underlying export scripts.

*   **Dual Mode Schema Synchronization**: Generate visual nodes directly from SQL schemas or translate visual node configurations into standard SQLite syntax scripts.

---

  

## How to Run It (Zero Setup)

  

## Single Double-Click (Local ZIP File Mode)

1. Download or output the project files as a ZIP archive.
2. Extract the archive contents onto your local device.
3. Locate the `index.html` file and double-click to immediately open it in any web browser (Chrome, Firefox, Edge, Safari, etc.).
4. *Enjoy zero-config interactive database schema design!*

---
## Built With

*   **Layout Engine**: Tailwind CSS
*   **Sandbox**: PyScript (incorporating Python 3 WebAssembly builds with robust sqlite3 bindings)
*   **Editor**: Monaco Editor (with custom client-side Worker configurations)
*   **Icons**: Lucide Icons & Boxicons

Need live preview ? - 
				🔵 **https://axxodeveloper.github.io/Prime.SQL/**
