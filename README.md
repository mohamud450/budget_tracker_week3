# Week 3: Design the Visual Identity of Your Budget Tracker

## Project overview
This project continues the Personal Budget & Expense Tracker built in Weeks 1 and 2. Week 3 focuses on visual design using CSS. The existing page content and functionality have been retained; the main update is a more consistent and polished visual identity.

## Project files
- `index.html` — the existing page structure, including the header, Add Expense form, expense table, help details, and budgeting video.
- `style.css` — the visual design: color palette, Google Fonts, card styling, table and form styling, spacing, borders, shadows, and responsive adjustments.

## How to run the project
1. Extract the ZIP file.
2. Open the `budget_tracker_week3` folder.
3. Double-click `index.html` to open it in a browser.
4. Keep `index.html` and `style.css` together in the same folder.

## Design choices

### 1. Color palette
The design uses a small, consistent palette:
- Deep navy (`#17324d`) for the header and table headings.
- Teal (`#168b82`) for the main action button and accents.
- Soft mint (`#e7f4f1`) for supporting content.
- Light neutral background (`#f3f7f6`) for the page.
- White surfaces and muted grey-blue text for readability.

### 2. Typography
Google Fonts are imported in the stylesheet:
- **Manrope** is used for headings and table headings.
- **DM Sans** is used for body text, labels, form controls, buttons, and table content.

An internet connection is needed for Google Fonts to load. The page will use a sans-serif fallback if they are unavailable.

### 3. Table and form styling
The expense table has a dark header, cell padding, subtle borders, alternating row backgrounds, and a hover state. Form inputs and the category dropdown share consistent sizing, borders, rounded corners, and focus styling. The Add Expense button uses the teal accent color.

### 4. CSS Box Model
Margin separates the page sections. Padding creates space inside the header and content cards. Borders define card and input boundaries. Border radius softens the corners. The header, Add Expense form, and Expense Table each appear as distinct cards.

## Existing static-project note
The sample expense rows are hardcoded. The Add Expense button remains a visual placeholder and does not add expenses yet, as required by the earlier project stage.
