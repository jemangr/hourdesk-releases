<p align="center">
  <img src="docs/icon.svg" width="96" alt="HourDesk icon">
</p>

<h1 align="center">HourDesk</h1>

<p align="center">
  <b>Modular White-Label MSP &amp; Technical Service Suite — Prepaid Hours, Support Contracts &amp; Subscriptions, Inventory &amp; Expenses, VoIP Screen Pop, Client Portal &amp; Android App</b><br>
  Ολοκληρωμένη White-Label Πλατφόρμα Τεχνικών Υπηρεσιών — Προαγορά Ωρών, Συμβάσεις &amp; Συνδρομές, Αποθήκη &amp; Έξοδα, VoIP Screen Pop, Client Portal &amp; Android App
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-v1.4.0%20Wave%204-2563EB?style=for-the-badge" alt="Version v1.4.0">
  <img src="https://img.shields.io/badge/License-All%20Rights%20Reserved-1E293B?style=for-the-badge" alt="All Rights Reserved">
  <img src="https://img.shields.io/badge/Languages-EL%20%7C%20EN-0F766E?style=for-the-badge" alt="Greek and English">
</p>

<p align="center">
  <a href="#english">English</a> • <a href="#greek">Ελληνικά</a>
</p>

---

<a id="english"></a>

## English Overview

**HourDesk** is a turnkey commercial white-label platform built for **IT / MSP providers, Electrical &amp; Plumbing contractors, Security/CCTV teams, HVAC/Solar engineers, Accounting/Legal offices, and Technical Service companies**.

It runs as **3 independent modular suites** (separately or combined into one unified workspace), adapting navigation, dashboards, portals, VoIP popups, and the Android companion app automatically.

### Modular Commercial Suites

1. **Prepaid Hours &amp; FIFO Ledger**
   - Purchase/start/expiry dates, queued future packages, strict **FIFO allocation**, optional overage (negative balance), and automatic credit restoration on non-billable adjustments.
   - Per-channel billing rules (Mobile Calls, VoIP PBX Calls, On-Site Visits, Manual Entries) with minimum duration, rounding steps, and multipliers.
2. **Support Contracts, Subscriptions &amp; Payment Tracking**
   - **Support Contracts**: Fixed-fee contracts with cost tracking, optional hour caps per cycle (e.g., 72h/year or monthly) with per-contract overage behavior (**Bill Excess Hourly** vs **Notify Only**), or **Time &amp; Materials (T&amp;M)** contracts.
   - **Subscriptions &amp; Renewals**: Dedicated tracking for recurring licenses/domains (e.g., Microsoft 365 monthly/annual, `.gr` 2-year domains, `.com/.eu` 1-year domains), payment statuses (`PAID` / `PENDING` / `OVERDUE`), 1-click renewal, and internal team comments.
   - **Contract Catalog &amp; Bulk Import**: Reusable contract types with **CSV / Excel import** and customizable renewal alert templates, test emails, and **Gmail / Microsoft 365 OAuth2 draft creation**.
3. **Expenses, Inventory &amp; Automated Price Sync**
   - Stock items with SKU, min-stock alerts, cost/sell pricing, **QR / Barcode label printing**, and movement ledger.
   - **Inventory → Subscriptions Bulk Price Sync**: Update a unit price once in Inventory, preview all affected client contracts/subscriptions, and update all with one confirmation.
   - **Technician €0 Pending Cost Inbox**: Field technicians who do not handle pricing can log a part at `€0` (*Pending Office Pricing*), triggering instant office recipient alerts and a dedicated completion queue.

### Core Platform &amp; Integrations

- **Real-Time VoIP Screen Pop (`3CX v18/v20` &amp; `Yeastar S/P-Series`)**: Instant E.164 caller identification (`libphonenumber`), full-width single-item client/asset cards, live **Client &amp; Internal Notes**, and inline **Follow-up Task creation with Due Date &amp; Client-Requested flag**.
- **Native Android Companion App (Kotlin + Jetpack Compose + Room)**: Dual-SIM corporate call logging, work-hours filtering, missed-call follow-up alerts, offline cache &amp; WorkManager sync, GPS check-in, digital customer signature, QR scanning, and module-adaptive UI.
- **Greek Tax &amp; Business Compliance**:
  - **Global VAT Mode (`Net` vs `Gross incl. VAT`)** applied consistently across inputs and displays.
  - **Automatic Greek VAT Lookup** (`AADE RgWsPublic2` &amp; `GEMI OpenData`) inside both client editing and Quick New Client creation.
  - **AADE myDATA XML v1.0 e-Invoicing**, consolidated Billing Queue, and PDF/XLSX P&amp;L profitability reports.
- **Client Portal, Quotes, SLA &amp; Operations**:
  - **Interactive Quotes / Proposals**: Public client approval link, PDF export, and conversion to work/packages/contracts.
  - **SLA &amp; Greek Public Holidays**: Business hours vs 24/7 SLA schedules per client with retroactive recalculation.
  - **Read-Only Client Portal** (with global &amp; per-client kill-switch), **AES-256-GCM Encrypted Credential Vault**, **RMM Webhook Alerts**, **SMS / Viber Gateway** (`Apifon`, `Yuboto`, `Routee`, `Twilio`) with setup guide, **14 Industry Vertical Templates**, **RBAC**, and **Ed25519 License Protection**.

### Licensing &amp; Commercial Availability

HourDesk is proprietary commercial software (**All Rights Reserved** — see [LICENSE](LICENSE)).  
This public repository is the official feature showcase and release distribution hub.

---

<a id="greek"></a>

## Ελληνικά — Επισκόπηση Δυνατοτήτων

Το **HourDesk** είναι μια ολοκληρωμένη εμπορική white-label πλατφόρμα σχεδιασμένη για **εταιρίες IT / MSP, Ηλεκτρολόγους, Υδραυλικούς, Συστήματα Ασφαλείας/CCTV, Κλιματισμό/Φωτοβολταϊκά, Λογιστικά/Νομικά γραφεία και Συνεργεία Υπηρεσιών**.

Λειτουργεί σε **3 ανεξάρτητα modules** (το καθένα μόνο του ή συνδυασμένα σε ένα ενιαίο σύστημα), προσαρμόζοντας αυτόματα τα μενού, το Dashboard, το Client Portal, το VoIP Screen Pop και την εφαρμογή Android.

### 3 Ανεξάρτητα Εμπορικά Προγράμματα (Modules)

1. **Προαγορά Ωρών &amp; FIFO Κατανάλωση**
   - Πακέτα ωρών με ημερομηνία αγοράς/έναρξης/λήξης, πακέτα σε αναμονή (`QUEUED`), αυστηρή χρέωση **FIFO**, προαιρετικό αρνητικό υπόλοιπο και αυτόματη επιστροφή χρόνου σε `NON_BILLABLE` εγγραφές.
   - Κανόνες χρέωσης ανά κανάλι (Κινητό, VoIP, Επίσκεψη, Χειροκίνητη) με ελάχιστο χρόνο, βήμα στρογγυλοποίησης και συντελεστές.
2. **Συμβάσεις Τεχνικής Υποστήριξης, Συνδρομές &amp; Πληρωμές**
   - **Συμβάσεις Υποστήριξης**: `Fix` συμβάσεις με παρακολούθηση κόστους, προαιρετικό όριο ωρών κύκλου (π.χ. 72 ώρες/έτος) και επιλογή υπέρβασης ανά σύμβαση (**Χρέωση Υπέρβασης €/ώρα** vs **Μόνο Ειδοποίηση**), ή συμβάσεις **Ωροχρέωσης (`T&amp;M`)**.
   - **Συνδρομές &amp; Ανανέωση**: Ξεχωριστή παρακολούθηση επαναλαμβανόμενων υπηρεσιών (`Microsoft 365` μήνα/έτος, `Domain .gr` 2 έτη, `.com/.eu` 1 έτος κ.ά.), κατάσταση πληρωμής (`PAID` / `PENDING` / `OVERDUE`), ανανέωση με 1 κλικ και εσωτερικά σχόλια ομάδας (κρυφά από τον πελάτη).
   - **Κατάλογος Τύπων &amp; Import**: Χειροκίνητη προσθήκη ή **εισαγωγή από CSV / Excel**, ξεχωριστή καρτέλα ειδοποιήσεων, αποστολή Test Email και **δημιουργία OAuth2 Drafts σε Gmail &amp; Microsoft 365**.
3. **Έξοδα, Αποθήκη Υλικών &amp; Συγχρονισμός Τιμών**
   - Διαχείριση αποθέματος με SKU, όρια ειδοποίησης, κόστος/πώληση, **εκτύπωση QR / Barcode ετικετών** και ιστορικό κινήσεων.
   - **Σύνδεση Αποθήκης → Συμβάσεων με Ποσότητα**: Αλλάζοντας μια τιμή στην Αποθήκη, προβάλλεται επιβεβαίωση (*«Επηρεάζονται X συμβάσεις — Ενημέρωση όλων;»*) για μαζική αναπροσαρμογή.
   - **Εκκρεμότητες Κόστους Τεχνικών (€0 Inbox)**: Όταν ο τεχνικός περάσει υλικό με `€0` (*Εκκρεμεί τιμή*), αποστέλλεται ειδοποίηση στον ορισμένο υπεύθυνο και εμφανίζεται στην ουρά τιμολόγησης του γραφείου.

### Κύριες Λειτουργίες &amp; Ενσωματώσεις

- **Ζωντανό VoIP Screen Pop (`3CX v18/v20` &amp; `Yeastar`)**: Ακαριαία αναγνώριση E.164, διπλές σημειώσεις (Πελάτη &amp; Εσωτερική), δημιουργία ανοιχτού Task με **checkbox Ημ. Λήξης (`Due Date`) &amp; Απαίτηση Πελάτη**, και inline επεξεργασία ημερομηνιών.
- **Εφαρμογή Android (Native Kotlin + Jetpack Compose + Room)**: Dual-SIM καταγραφή εταιρικών κλήσεων, ειδοποιήσεις αναπάντητων, offline βάση, GPS check-in, ψηφιακή υπογραφή πελάτη, QR scanner, έξοδα πεδίου (με επιλογή `€0 — Εκκρεμεί τιμή`) και δυναμική απόκρυψη πεδίων ανά module.
- **Ελληνική Φορολογική &amp; Επιχειρησιακή Συμμόρφωση:**
  - **Καθολική Ρύθμιση ΦΠΑ (Καθαρές vs Μεικτές Τιμές με ΦΠΑ)** παντού σε φόρμες, πίνακες και αναφορές.
  - **Αυτόματη Αναζήτηση ΑΦΜ (ΑΑΔΕ RgWsPublic2 &amp; ΓΕΜΗ OpenData)** απευθείας και στη γρήγορη προσθήκη νέου πελάτη.
  - **Ηλεκτρονική Τιμολόγηση ΑΑΔΕ myDATA (XML v1.0)**, Ουρά Τιμολόγησης και Αναφορές Κερδοφορίας (P&amp;L) ανά πελάτη, σύμβαση και τεχνικό σε Excel/PDF.
- **Ολοκληρωμένο Operations Suite:**
  - **Προσφορές (Quotes)** με δημόσιο link έγκρισης &amp; PDF.
  - **Εργάσιμο Ωράριο SLA &amp; Ελληνικές Αργίες** με default πολιτική και **αναδρομικό υπολογισμό ανά πελάτη**.
  - **SMS / Viber Gateway** (`Apifon`, `Yuboto`, `Routee`, `Twilio`) με ενσωματωμένο αναλυτικό οδηγό ρυθμίσεων.
  - **Πύλη Πελάτη (Read-Only Portal)** με δυνατότητα απενεργοποίησης γενικά αλλά και ανά πελάτη, **Κρυπτογραφημένο Vault (`AES-256-GCM`)**, **RMM Alerts**, **14 Προφίλ Κλάδων**, **RBAC ανά τεχνικό**, **Ed25519 License Protection** και **Full Demo Dataset** (με επιλογή μόνιμης διαγραφής μόνο των demo εγγραφών).

© 2026 jemangr (Giannis Oikonomakis). All rights reserved.
