# Bloom Tracker 🤍

A usability issue tracker for design and testing work. Log what trips people up, rate how serious it is, assign an owner and a due date, and follow each issue until it is fixed. It is a single HTML file with no installs, no build step and no dependencies.

**Live demo:** _add your GitHub Pages link here_

## Features

- Add, edit, duplicate and delete issues, with **Undo** after deleting.
- Severity from 1 (Cosmetic) to 4 (Critical), Nielsen's 10 heuristics, status, owner and due date. Overdue issues are flagged.
- Search, filter by status, severity or heuristic, and sort any column.
- Bulk actions: select several issues, then mark them fixed or delete them.
- Summary tiles and a severity chart for open issues.
- **Export:** CSV for spreadsheets, JSON backup and restore, and a copyable summary for reports.
- Keyboard shortcut: press **N** to add an issue.
- 7 themes (Nude, Rose, Sage, Lavender, Blossom, Cocoa, Dusk) plus a soft High contrast theme.
- Comfort settings: text size, roomy text spacing and calm motion.

## Your data

Issues, theme and comfort settings are saved in your browser with `localStorage`. They are not synced between devices. Use **Backup (JSON)** to move your list, and **Restore backup** to load it again. If your browser blocks `localStorage` (for example in private mode), the tool still works but forgets your data when the tab closes.

## Run it

Download or clone the repo and open `index.html` in a browser.

```bash
git clone https://github.com/<your-username>/bloom-tracker.git
cd bloom-tracker
# open index.html
```

## Publish it (GitHub Pages)

1. Push the files to GitHub.
2. Go to **Settings → Pages**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
3. After a minute it is live at `https://<your-username>.github.io/bloom-tracker/`.

## Accessibility

- Text contrast is at least 4.5:1, and borders and focus outlines at least 3:1, in every theme. The High contrast theme reaches 7:1 for text.
- Everything works with a keyboard, with a visible focus outline and a skip link.
- Form fields have labels, errors are written in text, and status changes are announced to screen readers.
- Severity is shown with an icon and a word, not colour alone.

## Browser support

Current versions of Chrome, Edge, Firefox and Safari.

## License

Add a `LICENSE` file (MIT is a common choice).
