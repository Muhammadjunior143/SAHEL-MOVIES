# SAHEL MOVIES - Official VJ Luganda Streaming Platform & Admin CMS

**SAHEL MOVIES** is a web-based movie streaming application and Content Management System (CMS) tailored for VJ Luganda translated films. Built using single-file HTML, Tailwind CSS, Alpine.js, and FontAwesome, it delivers a liquid-glass UI with full client-side streaming and backoffice management tools.

---

## 🌟 Key Features

### 🎬 Client Streaming Experience
* **VJ Luganda Catalog:** Organized categories filtering VJ Junior, VJ Ice P, VJ Mark, VJ Jingo, VJ Emmy, and original audio releases.
* **Free vs. VIP Access Tiers:** Support for 100% free streaming titles alongside VIP pass-restricted content.
* **Embedded Video Player:** Native HTML5 player supporting local video blob uploads (`File API`) and web stream URL embeds (`iframe`).
* **User Authentication Gate:** Sign-up and login overlay modal enforcing account requirements for premium media access.
* **Promotional Ad Banner:** Integrated banner area for local sponsorship and promotional campaigns.

### 🛠️ Admin Backoffice & CMS
* **Analytics Dashboard:** Displays real-time Mobile Money revenue totals, registered users, pending payment verifications, and catalog counts.
* **Local File & Web Stream CMS:** Interface to upload movie files directly from local storage using Blob URLs or link external stream URLs.
* **Mobile Money Payment Verification Desk:** Manual verification and instant VIP activation for **Airtel Merchant (6967790)** and **MTN Mobile Money (0744902535)** transactions.
* **Auto-Verify Switch:** Optional automated verification mode for instant VIP access[cite: 1].
* **User Management:** View registered users and toggle VIP subscription access manually[cite: 1].

---

## 🛠️ Tech Stack & Dependencies

All dependencies are loaded via CDN, eliminating the need for complex build pipelines[cite: 1]:

* **HTML5**[cite: 1]
* **Tailwind CSS** (v3 CDN with custom dark mode theme configuration)[cite: 1]
* **Alpine.js** (v3 CDN for reactive state management)[cite: 1]
* **FontAwesome** (v6 CDN for UI iconography)[cite: 1]
* **Plus Jakarta Sans** (Google Fonts)[cite: 1]

---

## 🚀 Quick Start Guide

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/your-username/sahel-movies.git](https://github.com/your-username/sahel-movies.git)
   cd sahel-movies
