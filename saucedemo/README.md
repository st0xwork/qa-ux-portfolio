# 🧪 saucedemo.com — Functional QA & UX Review

## 📋 Project Summary

- **Website**: [saucedemo.com](https://www.saucedemo.com/)
- **Type of Testing**: Functional testing + UX feedback
- **Time Spent**: ~1 hour
- **Tools Used**: Chrome DevTools, Screenshots, Notion
- **Device**: MacBook Air, Chrome browser
- **Goal**: Detect functional and UX flaws in e-commerce flow

---

## 🐞 Bugs & UX Issues

### 🐞 Bug #1 — User can checkout without entering shipping info
- **Issue**: No validation on shipping step (can proceed with empty fields)
- **Impact**: 🚨 Critical — fake orders / broken flow
- **Suggestion**: Add required field validation
- **Steps to reproduce**: Login → Add item → Checkout → Leave fields blank → Click Finish

---

### 🐞 Bug #2 — Cart icon does not reset after logout
- **Issue**: After logout and relogin, cart still shows previous count
- **Impact**: Data leakage across sessions
- **Suggestion**: Reset cart on logout

---

### 🐞 Bug #3 — Sort dropdown resets on page refresh
- **Issue**: Sorting by Price (Low to High) resets after refreshing the page
- **Impact**: Poor UX, inconsistency
- **Suggestion**: Preserve sort state using localStorage or query params

---

### 🐞 Bug #4 — Sort dropdown has no visual feedback
- **Issue**: Clicking sorting options doesn’t provide UI feedback
- **Impact**: Confusing UX
- **Suggestion**: Highlight selected sorting method

---

### 🐞 Bug #5 — Broken “Twitter” footer link
- **Issue**: Twitter icon leads to 404 page
- **Impact**: Hurts brand perception and trust
- **Suggestion**: Fix or remove broken links

---

## ✅ Final Recommendations

- Enforce form validation on checkout
- Reset user state fully on logout
- Preserve user UI selections across reloads
- Improve visual feedback for sort/filter UI
- Audit footer links for accuracy

---

## 🧠 Skills Demonstrated

- Functional QA
- UX Sensitivity
- Test case design
- Bug documentation (EN)
- Repro steps clarity

---

## 🔗 Links

- **Live site**: [saucedemo.com](https://www.saucedemo.com/)
- **Date tested**: September 13, 2025
- **Contact**: [My Upwork Profile](https://www.upwork.com/freelancers/~018bb602a002dd7baaid)
