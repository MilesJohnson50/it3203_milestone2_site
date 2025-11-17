# IT 3203 Project Milestone #2 — Dynamic Frontend (HTTP Study Site)


## 1) Quiz Feature (Main Requirement #1)

### 1.a JavaScript + HTML Forms
- File: `quiz.html` (form UI) + `script.js` (grading + reset)
- Approach: Accessible labels, `fieldset`/`legend`, and `aria-live` region for results.

### 1.b UI Requirements (Form Elements)
- Separate page in menu: Quiz is in the global nav.
- Question types:
  - Q1 — Fill‑in‑the‑blank (text input)
  - Q2, Q3, Q4 — Single‑answer multiple‑choice (radio)
  - Q5 — Multi‑selection (checkboxes)
- Professional styling in single `styles.css`.

### 1.c Functional Requirements
- Immediate scoring after submit; total /100.
- In‑page display: PASS/FAIL, total score, per‑question correctness and answers with colors.
- Reset button clears all inputs and results.


---

## 2) Content & Style Improvements
- Expanded topic content and references.
- Updated nav across all pages.
- CSS refactor with comments; kept single stylesheet.
- Key Concepts page now includes Head‑of‑Line Blocking (HOL).


---

## 3) Other Requirements
- Comments included in HTML/CSS/JS.
- Deploy to same GitHub Pages repo as Milestone #1.
- Validate with https://validator.w3.org/

---

## 4) Testing Notes
- Tested empty inputs, partial selections, and full correct answers.
- Verified color classes for visual feedback.
- Confirmed Reset hides previous results.