# Study Planner

**One‑line description:** A tiny web‑app that lets a student add subjects with a priority and estimated study time, displays a sorted study plan, and shows the total hours for the day.

## Problem it solves
Students often have a list of topics to study and need a quick way to organise them by importance while tracking how many hours they plan to spend. This app provides a **no‑install, single‑page** solution that handles prioritisation and total‑time calculation instantly.

## Key features
- Add a subject, set its **priority** (High / Medium / Low) and **time needed** (hours).
- Automatic sorting so **High‑priority** subjects appear first.
- Real‑time **total study hours** for the day.
- Pure client‑side – just open `index.html` in a browser.
- Simple, clean HTML/ CSS/ JavaScript with no build steps.

## Tech stack
- **HTML5** – structure and markup.
- **CSS3** – minimal styling.
- **Vanilla JavaScript** – DOM manipulation, sorting, and total‑hours calculation.
- **Git** – repository versioning (with a `.gitattributes` file to enforce LF line endings).

## How to run it (step‑by‑step)
1. **Clone / download** the repository or copy the folder `pp4` to your machine.
2. Open a terminal (PowerShell, CMD, Git Bash, etc.) and navigate to the project directory:
   ```
   cd C:\Users\bsuma\pp4
   ```
3. **Open the app** – simply launch the HTML file:
   ```
   start index.html   # Windows
   # or double‑click the file in Explorer
   ```
4. The browser will display the **Study Planner** UI. Add subjects, set priorities, and watch the table and total hours update automatically.

## How I built it using prompts in Google Antigravity
1. **Prompted Antigravity** to act as a senior developer and create a minimal web app that satisfies the user story (add subjects, priority sorting, total hours).
2. The assistant generated the full `index.html` with inline CSS/JS and saved it to the workspace.
3. When the user asked to run the app, Antigravity executed a `start` command to open the file in the default browser.
4. To address the Git line‑ending warning, I prompted Antigravity to add a `.gitattributes` file that forces LF line endings for HTML files.
5. Finally, I asked Antigravity to produce this `README.md`, summarising the project, its purpose, features, tech stack, usage steps, and a short “how‑I‑built‑it” narrative.

---

Feel free to customise the styling or extend the functionality (e.g., edit/remove entries, persist data with `localStorage`, or add export/import). Happy studying!