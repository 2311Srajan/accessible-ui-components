# Accessible UI Components & WCAG 2.2 Testing Suite

An enterprise-ready repository featuring fully accessible UI components built using **Semantic HTML5**, **WAI-ARIA 1.2**, and modern **JavaScript**. Designed to showcase complete compliance with **WCAG 2.1 / 2.2 Level A & AA** requirements.

## 🚀 Key Features

* **WAI-ARIA Pattern Implementation:** Built-in modal dialogs and dynamic accordions adhering strictly to WAI-ARIA Authoring Practices.
* **Keyboard Navigation & Trap Management:** Complete keyboard support including `Tab`, `Shift + Tab`, and `Escape` key listeners for modal accessibility.
* **Screen Reader Friendly:** Fully tested and verified using **Apple VoiceOver**, **NVDA**, and **JAWS** screen readers.
* **High Contrast & Visual Focus:** Meets 4.5:1 minimum color contrast ratios and features standard `:focus-visible` ring indicators.

## 🛠️ Accessibility Audit Methodology

This project underwent manual and automated auditing process:
1. **Automated Testing:** Evaluated using **axe DevTools** and **WAVE** browser extensions to detect structure and contrast issues.
2. **Screen Reader Testing:** Verified reading order, focus shifts, and dynamic state announcements across **VoiceOver (macOS/iOS)** and **NVDA (Windows)**.
3. **Keyboard Only Testing:** Tested end-to-end interactions without a pointing device to ensure zero keyboard traps.

## 📋 Standard Compliance Checklist
* [x] WCAG 1.4.3 Contrast (Minimum 4.5:1)
* [x] WCAG 2.1.1 Keyboard Accessible
* [x] WCAG 2.1.2 No Keyboard Trap
* [x] WCAG 2.4.7 Focus Visible
* [x] WCAG 4.1.2 Name, Role, Value
