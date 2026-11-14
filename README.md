<p align="center">
  <img src="docs/icon.svg" width="96" alt="HourDesk icon">
</p>

<h1 align="center">HourDesk</h1>

<p align="center">
  <b>White-Label Prepaid Support Hours, Live VoIP Screen Pop &amp; Field Service Platform</b><br>
  Πλατφόρμα Διαχείρισης Προαγορασμένων Ωρών Υποστήριξης, VoIP Screen Pop &amp; Επιτόπιων Επισκέψεων
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Coming%20Soon-2563EB?style=for-the-badge" alt="Coming Soon">
  <img src="https://img.shields.io/badge/License-All%20Rights%20Reserved-1E293B?style=for-the-badge" alt="All Rights Reserved">
  <img src="https://img.shields.io/badge/Languages-EL%20%7C%20EN-0F766E?style=for-the-badge" alt="Greek and English">
</p>

---

## Coming Soon / Σύντομα Διαθέσιμο

**HourDesk** is a turnkey commercial software suite designed for **IT / MSP providers, Electrical &amp; Plumbing contractors, HVAC &amp; Technical Service teams** who deliver support under prepaid hour packages.

This public repository is the official showcase and upcoming release distribution hub for **HourDesk** installers, release notes, and companion Android builds.

### Core Capabilities

- **Prepaid Hours &amp; FIFO Package Ledger**
  - Purchase date, start date, expiration, and queued future packages per client.
  - Strict FIFO consumption across active/queued packages, optional negative balance (overage), and automatic credit restoration when an entry is marked non-billable.
  - Configurable minimum blocks, rounding steps, and multipliers per channel (Calls, On-Site Visits, Manual Adjustments).
- **Real-Time VoIP Screen Pop (`3CX v18/v20` &amp; `Yeastar S/P-Series`)**
  - Instant caller identification normalized to E.164 (`libphonenumber`), showing client company, caller employee, remaining hours, equipment/assets, open tasks, and call history the moment the phone rings.
  - Dual notes saved live during the call: **Client Note** (visible in client portal &amp; PDF reports) and **Internal Note** (strictly team-only).
- **Android Companion App (Closed-Source Native Kotlin)**
  - Automatic corporate mobile call logging with Dual-SIM company card filtering and missed-call follow-up reminders.
  - Offline Room cache + WorkManager background sync.
  - On-site visit timer, GPS check-in, visit type, asset linking, materials log, and customer digital signature capture.
- **Field Service Web &amp; PWA Portal + Read-Only Client Portal**
  - Multi-industry templates (**IT / MSP**, **Electrical**, **Plumbing / HVAC**, **General Service**) switchable right from Settings.
  - **AES-256-GCM** encrypted asset secrets, **Argon2id + 2FA (TOTP)** authentication, strict RBAC (`ADMIN`, `TECHNICIAN`, `CLIENT_USER`), and Audit Log.
  - Automated SMTP low-balance/expiry email alerts, daily/weekly digests, CSV/XLSX bulk import, and filtered **Excel / PDF** reports per technician and per client.

---

## Licensing &amp; Commercial Availability

HourDesk is proprietary commercial software (**All Rights Reserved** — see [LICENSE](LICENSE)).  
Public releases and deployment packages are **coming soon**.

© 2026 jemangr (Giannis Oikonomakis). All rights reserved.
