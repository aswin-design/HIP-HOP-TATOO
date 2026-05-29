# TODO - Fix device responsiveness

## Plan summary
- Identify viewport breakpoints + issues causing overflow / sizing problems.
- Add/adjust responsive CSS rules across: navbar, hero, about, experience, gallery, masterclass, courses, providing, footer.
- Ensure images use correct paths and scale with `max-width:100%` and responsive height.
- Add mobile-friendly layout for grids (2-5 columns -> 1 column) and reduce large font sizes/paddings.
- Re-run a basic sanity check by opening in browser and resizing.

## Steps
1. Review current `style.css` and `index.html` structure for missing/incorrect responsive rules.
2. Implement a consolidated responsive section in `style.css` (breakpoints at 1200/992/768/576/400) to fix: font sizes, paddings, grid columns, image heights.
3. Fix any obvious CSS/HTML issues impacting responsiveness (e.g., duplicate `.courses-section` definitions, wrong image paths, overflow-x).
4. Verify footer layout and iframe sizing on small screens.
5. Final test: ensure no horizontal scrolling and key sections fit on 320px width.

