# qa-real-world-bugs

> Denys Yanovskyi · QA Engineer · Warsaw  
> [kubismatism@gmail.com](mailto:kubismatism@gmail.com) | [Main Portfolio](https://github.com/Des-ua/qa-opencart-manual-testing)

---

## About This Repository

This repository documents real bugs found in **commercial, released products** during everyday use.

Unlike controlled portfolio projects, these bugs were discovered organically — while playing games, using apps, or browsing websites. This reflects a real QA mindset: always testing, always noticing what's wrong.

---

## Bugs Found

| ID | Product | Type | Severity | Status |
| BR-001 | 007 First Light | Localization (Russian) | Minor | Reported |

---

## BR-001 — 007 First Light: Typo in Russian Localization

**Product:  007 First Light (IO Interactive)  
**Platform:  PC  
**Language:  Russian  
**Screen:  Epilepsy & Health Warning (startup screen)

### Bug Description

Missing letter "р" in the word "при" on the epilepsy warning screen shown at game startup.

### Steps to Reproduce

1. Launch 007 First Light with Russian language selected
2. Observe the health/epilepsy warning screen at startup
3. Read the last bullet point

### Expected Result
> "Не играйте "при" ощущении усталости или головной боли."

### Actual Result
> "Не играйте "пи" ощущении усталости или головной боли."

### Screenshot

![BR-001 Screenshot](./007_First_Light/screenshot.png)

### Severity: Minor | Priority: Low

**Notes:** Single missing letter in a legal/health warning screen. Low severity but should be corrected as it appears on every game launch.

---

## Testing Approach

Every bug in this repository follows standard QA documentation practices:
- Clear steps to reproduce
- Expected vs Actual result
- Severity and Priority classification
- Screenshot evidence

---

## More Bugs Coming

This repository is actively updated as new bugs are discovered.  
Main QA portfolio (OpenCart): [github.com/Des-ua/qa-opencart-manual-testing](https://github.com/Des-ua/qa-opencart-manual-testing)
