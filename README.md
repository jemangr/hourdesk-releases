<p align="center">
  <img src="docs/icon.svg" width="96" alt="HourDesk icon">
</p>

<h1 align="center">HourDesk</h1>

<p align="center">
  <b>White-Label Prepaid Support Hours, Live VoIP Screen Pop, Field Service Platform &amp; Android App</b><br>
  Πλατφόρμα Διαχείρισης Προαγορασμένων Ωρών Υποστήριξης, VoIP Screen Pop &amp; Επιτόπιων Επισκέψεων με Εφαρμογή Android
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Coming%20Soon-2563EB?style=for-the-badge" alt="Coming Soon">
  <img src="https://img.shields.io/badge/License-All%20Rights%20Reserved-1E293B?style=for-the-badge" alt="All Rights Reserved">
  <img src="https://img.shields.io/badge/Languages-EL%20%7C%20EN-0F766E?style=for-the-badge" alt="Greek and English">
</p>

<p align="center">
  <a href="#english">English</a> • <a href="#greek">Ελληνικά</a>
</p>

---

<a id="english"></a>

## English — Coming Soon

**HourDesk** is a turnkey commercial white-label software suite built for **IT / MSP providers, Electrical &amp; Plumbing contractors, HVAC teams, and Technical Service companies** delivering support under prepaid hour packages.

This public repository is the official showcase and upcoming release distribution hub for **HourDesk** installers, release notes, and companion Android builds.

### Core Capabilities

- **Prepaid Hours &amp; FIFO Package Ledger**
  - Purchase date, start date, expiration, and queued future packages per client.
  - Strict FIFO consumption across active/queued packages, optional negative balance (overage), and automatic credit restoration when an entry is marked non-billable.
  - Configurable minimum billing blocks, rounding steps, and multipliers per channel (Calls, On-Site Visits, Manual Adjustments).
- **Real-Time VoIP Screen Pop (`3CX v18/v20` &amp; `Yeastar S/P-Series`)**
  - Instant caller identification normalized to E.164 (`libphonenumber`), showing client company, caller employee, remaining hours, equipment/assets, open tasks, and call history the moment the phone rings.
  - Dual notes saved live during the call: **Client Note** (visible in client portal &amp; PDF reports) and **Internal Note** (strictly team-only).
- **Android Companion App (Closed-Source Native Kotlin — Bilingual EN / EL)**
  - Automatic corporate mobile call logging with Dual-SIM company card filtering and missed-call follow-up reminders.
  - Offline Room cache + WorkManager background sync + in-app language switcher (`Auto` / `English` / `Ελληνικά`).
  - On-site visit timer, GPS check-in, visit type, asset linking, materials log, and customer digital signature capture.
- **Field Service Web &amp; PWA Portal (Bilingual EN / EL) + Read-Only Client Portal**
  - Multi-industry templates (**IT / MSP**, **Electrical**, **Plumbing / HVAC**, **General Service**) switchable directly from Settings.
  - **AES-256-GCM** encrypted asset secrets, **Argon2id + 2FA (TOTP)** authentication, strict RBAC (`ADMIN`, `TECHNICIAN`, `CLIENT_USER`), and Audit Log.
  - Automated SMTP low-balance/expiry email alerts, daily/weekly digests, CSV/XLSX bulk import, and filtered **Excel / PDF** reports per technician and per client.

### Licensing &amp; Commercial Availability

HourDesk is proprietary commercial software (**All Rights Reserved** — see [LICENSE](LICENSE)).  
Public releases and deployment packages are **coming soon**.

---

<a id="greek"></a>

## Ελληνικά — Σύντομα Διαθέσιμο

Το **HourDesk** είναι μια ολοκληρωμένη εμπορική white-label πλατφόρμα σχεδιασμένη για **εταιρίες IT / MSP, Ηλεκτρολόγους, Υδραυλικούς, Τεχνικούς Κλιματισμού / Θέρμανσης και Συνεργεία Υποστήριξης** που παρέχουν τεχνική υποστήριξη με προαγορασμένα πακέτα ωρών.

Αυτό το δημόσιο repository αποτελεί το επίσημο κέντρο παρουσίασης (**showcase**) και μελλοντικής διανομής εκδόσεων (**releases**) και Android εφαρμογής του **HourDesk**.

### Βασικές Δυνατότητες

- **Διαχείριση Προαγορασμένων Ωρών &amp; FIFO Κατανάλωση Πακέτων**
  - Ημερομηνία αγοράς, έναρξης, λήξης και πακέτα σε αναμονή (`QUEUED`) ανά πελάτη.
  - Αυστηρή χρέωση **FIFO** σε ενεργά/επόμενα πακέτα, προαιρετικό αρνητικό υπόλοιπο (overage) και αυτόματη επιστροφή χρόνου όταν μια εγγραφή εξαιρείται ως **Μη Χρεώσιμη (`NON_BILLABLE`)**.
  - Παραμετροποιήσιμος ελάχιστος χρόνος χρέωσης, βήμα στρογγυλοποίησης και συντελεστής ανά κανάλι (Κλήσεις, Επιτόπιες Επισκέψεις, Χειροκίνητες Προσαρμογές).
- **Ζωντανό VoIP Screen Pop (`3CX v18/v20` &amp; `Yeastar S/P-Series`)**
  - Ακαριαία αναγνώριση καλούντος σε μορφή E.164 (`libphonenumber`), προβάλλοντας εταιρία, υπάλληλο, υπόλοιπο ωρών, εξοπλισμό/assets, ανοιχτές εκκρεμότητες και ιστορικό τη στιγμή που χτυπάει το τηλέφωνο.
  - Διπλές σημειώσεις κατά τη διάρκεια της κλήσης: **Σημείωση Πελάτη** (ορατή σε Client Portal &amp; PDF) και **Εσωτερική Σημείωση** (αποκλειστικά για την ομάδα).
- **Εφαρμογή Android (Native Kotlin — Δίγλωσση ΕΛ / EN)**
  - Αυτόματη καταγραφή εταιρικών κλήσεων κινητού με φιλτράρισμα **Dual-SIM**, ώρες εργασίας και υπενθυμίσεις αναπάντητων κλήσεων.
  - Offline Room βάση + WorkManager background sync + επιλογή γλώσσας μέσα από την εφαρμογή (`Αυτόματη` / `English` / `Ελληνικά`).
  - Χρονόμετρο επιτόπιας επίσκεψης, GPS check-in, υλικά και λήψη ψηφιακής υπογραφής πελάτη στην οθόνη.
- **Web &amp; PWA Πλατφόρμα (Δίγλωσση ΕΛ / EN) + Read-Only Client Portal**
  - Έτοιμα προφίλ κλάδου (**IT / MSP**, **Ηλεκτρολόγοι**, **Υδραυλικοί / HVAC**, **Γενικές Υπηρεσίες**) με εναλλαγή από τις Ρυθμίσεις.
  - Κρυπτογραφημένα credentials εξοπλισμού (**AES-256-GCM**), αυθεντικοποίηση **Argon2id + 2FA (TOTP)**, αυστηρό RBAC (`ADMIN`, `TECHNICIAN`, `CLIENT_USER`) και Audit Log.
  - Αυτόματα SMTP alerts χαμηλού υπολοίπου/λήξης, ημερήσια/εβδομαδιαία digests, μαζικό import CSV/XLSX και φιλτραρισμένες εξαγωγές **Excel / PDF**.

### Άδεια Χρήσης &amp; Εμπορική Διάθεση

Το HourDesk αποτελεί ιδιόκτητο εμπορικό λογισμικό (**All Rights Reserved** — δείτε [LICENSE](LICENSE)).  
Οι δημόσιες εκδόσεις και τα πακέτα διανομής **έρχονται σύντομα (Coming Soon)**.

© 2026 jemangr (Giannis Oikonomakis). All rights reserved.
