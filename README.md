# Zero-Line Clinic Hub (`preetamdalabhanjan-ship-it/zero-line`)

**Zero-Line Clinic Hub** is an installable Progressive Web App (PWA) that connects the **Front Desk**, **Doctor's Tablet (Cloud EHR)**, and **Attached Pharmacy** so patients never wait in crowded lobbies or stand in multiple queues.

## Core Modules

1. **Front Desk & Live WhatsApp Token Tracker**: Assigns each patient a permanent **Unique Cloud ID (`CLD-XXXX`)** tied to their phone number and issues a live token so they can wait at home and arrive 10 minutes before their turn.
2. **Doctor Tablet (Cloud EHR & Error-Free Digital Rx)**: Pulls up lifetime patient history, vitals, and allergies immediately upon check-in, blocks prescriptions that conflict with recorded allergies, and calculates the bill from a standardized medicine dropdown.
3. **Pharmacy & Single-Window Exit**: Alerts the pharmacy to pack the medicine bag and sends the combined consultation + pharmacy bill to the counter the instant the doctor taps **Consultation Complete**.
4. **Cloud Patient ID Directory**: Searchable directory of every patient's lifetime visits, vitals, diagnoses, and prescriptions, with 1-click encrypted JSON backup export.
5. **Commercial White-Label SaaS Panel**: Customize the clinic brand name, currency (`₹`, `$`, `€`, `£`, `AED`), and monthly or perpetual license pricing to sell the software at your own price.

## Quick Start & GitHub Pages Deployment

1. Upload the files in this repository (`index.html`, `manifest.json`, `sw.js`, `README.md`, `LICENSE`) to the root of `preetamdalabhanjan-ship-it/zero-line`.
2. In your GitHub repository, open **Settings → Pages**, set **Source** to **Deploy from a branch** (`main` / `/ (root)`), and click **Save**.
3. Open your live URL on **Windows, macOS, Linux, Android, or iPadOS** and click **Install App on Any OS** (or your browser's **Install App / Add to Home Screen** button) to run it as a standalone application.
