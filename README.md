# 11kV QRM Protection Relay Calculator
### ADDC Abu Dhabi — Fanox Relay — IEC 60255-151

[![Live Demo](https://img.shields.io/badge/▶%20Live%20Demo-Open%20in%20Browser-00b4d8?style=for-the-badge)](https://mohammed-engineer.github.io/QRM-Protection-Calculator)

---

## About This Project

Built by a commissioning and testing engineer who 
personally tested these exact relays on site for 
ADDC — Abu Dhabi Distribution Company.

All test results in this tool are real secondary 
injection data from Mafraq Area Substation, 
Abu Dhabi — September 2017.

**Signed off as:** Engr. Mohammad Azam — Contractor  
**Witnessed by:** ADDC Witness — 19-09-2017

---

## What This Tool Calculates

✅ IDMT overcurrent relay — Extremely Inverse (EI) curve  
✅ IDMT earth fault relay — Normal Inverse (NI) curve  
✅ Standby Earth Fault (SBEF) — Fanox SIA-C — LV 415V side  
✅ High Set Instantaneous I>> — all three phases + earth fault  
✅ Thermal lockout element I>>> — 180 second definite time  
✅ All four IEC IDMT curves — EI / SI / NI / VI  
✅ Real-time coordination graph — log-log scale  
✅ ADDC site test verification — calculated vs measured  
✅ Fault to trip timeline animation — 5 scenarios  

---

## Real Equipment Tested On Site

| Item | Details |
|------|---------|
| Client | ADDC — Abu Dhabi Distribution Company |
| Contractor | ACECO |
| Location | Mafraq Area Substation, Abu Dhabi UAE |
| Switchgear | Lucy VRE 2a — 12kV Ring Main Unit |
| Transformer | 1500 kVA — Dyn11 — Z% 6.22% — ONAN |
| HV Relay | Fanox — EI curve — CT 100/1A |
| SBEF Relay | Fanox SIA-C — EI curve — CT 2000/1A |
| Test Equipment | SVERKER 780 Secondary Injection Set |

---

## Screenshots

![Header and Relay Info](screenshot1.png)

![Coordination Curves](screenshot2.png)

![Test Verification](screenshot3.png)

---

## Standards Referenced

- IEC 60255-151 — IDMT relay curves and timing
- IEC 60947 — Low voltage switchgear
- IEC 62271 — High voltage switchgear
- IEC 60909 — Short circuit calculations

---

## IEC IDMT Curve Formula
| Curve | α | β |
|-------|---|---|
| EI — Extremely Inverse | 2.00 | 80.0 |
| SI — Standard Inverse | 0.02 | 0.14 |
| VI — Very Inverse | 1.00 | 13.5 |
| NI — Normal Inverse | 0.02 | 0.14 |

---

## How to Use

Click the Live Demo button above.  
Opens instantly in any browser.  
No installation required.  
Change any relay setting and click Calculate.  
Everything updates automatically.

---

## Author

**Mohammed Azam Ali — MIET**  
Electrical Commissioning and Testing Engineer  
11kV HV Systems — Abu Dhabi UAE  
github.com/Mohammed-Engineer
