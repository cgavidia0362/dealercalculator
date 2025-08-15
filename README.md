# Dealer Net Check Calculator

This is a simple, single-page calculator for determining the dealer net check amount.  
It is hosted with **GitHub Pages** and can be accessed here:  
**[LIVE SITE LINK](https://cgavidia0362.github.io/dealercalculator/)**

---

## 🚀 How to Update the Calculator

### 1. Prepare the New `index.html`
- Keep a **backup** of the current `index.html`.
- Edit your HTML file with the updated logic or design (or have someone do it for you).
- Test locally by double-clicking `index.html` to open in your browser.

### 2. Publish the Update
1. Go to the GitHub repository.
2. Click **Add file → Upload files**.
3. Drag your updated `index.html` into the upload area (same filename).
4. Add a commit message (e.g., `Updated index.html to include GPS in Total Contract Fees`).
5. Make sure **Commit directly to the main branch** is selected.
6. Click **Commit changes**.

### 3. Verify the Update
- Open the live site link.
- If it looks the same, force refresh:
  - **Windows:** `Ctrl + F5`
  - **Mac:** `Cmd + Shift + R`
- Or add `?v=2` to the end of the URL to bypass cache.

---

## 🔄 Rolling Back to a Previous Version
If something breaks:
1. Open `index.html` in the repo.
2. Click the **History** button (clock icon).
3. Select the last working version.
4. Click **Revert** (or copy its contents and paste over the current file).
5. Commit the change — your site will be back online.

---

## 🧮 Formula Overview
- **Net Check** = **Total Amount to Finance** − **Total Contract Fees**
- **Total Contract Fees** = Acquisition Fee + Warranty Fee + GAP Fee + GPS + Total Hold
- All calculations are done in JavaScript within `index.html`.

---

## 🛠 Maintenance Tips
- Only **`index.html`** is needed for the site to work.
- If you add extra pages for testing (e.g., `index-preview.html`), delete them when done.
- Check **Settings → Pages** to ensure the site is publishing from:
  - Source: **Deploy from a branch**
  - Branch: `main` / folder `/ (root)`

---
## Updates
- 2025-08-15: Added GPS to Total Contract Fees calculation
- 2025-08-15: Rearranged sections (Front End + Amount Required on left, Backend Products + Fees & Discount on right)
- Removed old index-fixed-gps.html file

**Author:** Chris Gavidia  
**Hosting:** GitHub Pages
