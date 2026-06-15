# SauceLabs Demo App — Mobile Testing Project

A manual mobile testing project for the **SauceLabs Demo App** (Android), covering functional testing, mobile-specific testing, and additional features testing.

---

## Project Overview

| Field | Details |
|---|---|
| **App** | MyDemoApp V2.2.0-build 25 (Android) |
| **Test Type** | Manual Mobile Testing |
| **Environment** | Android Emulator — Pixel 6a / Android 17 (API 37.0) |
| **Tools** | Android Studio, Excel, Word |
| **Test Period** | 07/06/2026 – 13/06/2026 |
| **Tester** | Nguyen Hoang Lam Tan |

---

## Test Results Summary

| Total TC | Pass | Fail | Blocked |
|---|---|---|---|
| 101 | 87 | 10 | 4 |

- **Pass Rate:** 86% (all TC) / 90% (executable TC only)
- **Bugs Found:** 7 (2 Critical, 2 High, 1 Medium, 2 Low)

---

## Test Coverage

| Module | TC Count | Result |
|---|---|---|
| Launch | 3 | ✅ All Pass |
| UI | 4 | ⚠️ 1 Fail |
| Interruption | 3 | ✅ All Pass |
| Permission | 4 | ⚠️ 1 Fail |
| Navigation | 4 | ✅ All Pass |
| Media | 3 | ✅ All Pass |
| Authentication | 6 | ✅ All Pass |
| Product Catalog | 9 | ⚠️ 2 Fail |
| Product Detail | 10 | ✅ All Pass |
| Cart | 11 | ✅ All Pass |
| Checkout & Payment | 20 | ⚠️ 2 Fail |
| About | 3 | ✅ All Pass |
| WebViewer | 6 | ⚠️ 1 Fail |
| Drawing | 8 | ⚠️ 3 Fail |
| Reset App State | 3 | ✅ All Pass |
| Crash App | 4 | 🔒 All Blocked |

> **Note:** Crash App module is fully blocked — the feature requires Backtrace SDK integration not available in the pre-built APK.

---

## Bug Highlights

| Bug ID | Module | Severity |
|---|---|---|
| BUG_001 | Product Catalog | 🔴 Critical — Bottom products unresponsive, causes app crash |
| BUG_002 | Checkout & Payment | 🔴 Critical — Empty Card Number shows no error message |
| BUG_004 | Drawing | 🟠 High — Save success shown despite storage permission denied |
| BUG_007 | Checkout & Payment | 🟠 High — Expired card date accepted without validation |
| BUG_003 | WebViewer | 🟡 Medium — HTTP URL navigates to WebViewer instead of blocking |
| BUG_005 | Drawing | 🟢 Low — Drawing lost after back navigation |
| BUG_006 | Drawing | 🟢 Low — Save success shown on empty canvas |

---

## Project Documents

| Document | Description |
|---|---|
| [`TestPlan_Mobile_MyDemoApp.docx`](./TestPlan_Mobile_MyDemoApp.docx) | Test strategy, scope, schedule, and risk assessment |
| [`TestCases_Mobile_MyDemoApp.xlsx`](./TestCases_Mobile_MyDemoApp.xlsx) | 101 test cases across 16 modules |
| [`BugReport_Mobile_MyDemoApp.xlsx`](./BugReport_Mobile_MyDemoApp.xlsx) | 7 bug reports with steps to reproduce |
| [`TestReport_Mobile_MyDemoApp.docx`](./TestReport_Mobile_MyDemoApp.docx) | Final test report with results and recommendations |

---

## Author

**Nguyen Hoang Lam Tan**  
QA Tester | Software Engineering Graduate  
🔗 [GitHub](https://github.com/nhlamtan) | 📧 [LinkedIn](https://www.linkedin.com/in/lam-tan/)
