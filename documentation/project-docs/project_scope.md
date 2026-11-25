# Project Scope

## Objective
Build a clean, responsive, static website for the Programming Club using **HTML, CSS, and JavaScript**, deployed via **GitHub Pages**, that showcases member projects, introduces members, shares beginner learning resources, answers FAQs, and lets new students apply to join.

## In-Scope Sections
1. **Homepage (`index.html`)**
   - Club introduction, mission, meeting highlights, and quick navigation to all sections.
2. **Project Showcase**
   - Filterable list/grid of club projects—covering both **completed** and **in-progress** projects via status tags/filters.
   - Displays project name, description, status (`Completed` / `In Progress`), tech stack, contributors, screenshot/preview, live demo URL (when available), and GitHub repo URL.
3. **Member Directory**
   - Member cards with name, avatar (`assets/`), club role, favorite programming languages, short bio, and GitHub profile link.
   - Only publish member details/avatars with that member's permission.
4. **Starter Resources & Wiki**
   - Curated beginner guides, environment setup tips, language/Git tutorials, and club workflow references.
5. **Join Us Form**
   - Collects student name, contact info, programming experience, and interests/motivation.
   - Sends submissions to the club lead's email via an external form service or serverless endpoint (never hardcode email credentials in frontend JS).
6. **FAQ**
   - Answers common questions: experience needed, what to bring to meetings, languages covered, meeting schedule, joining projects, and how to join.

## Out of Scope (v1)
- Custom backend server or database hosted in this repo.
- User accounts, login/authentication, or admin dashboards.
- Heavy frontend frameworks or complex build pipelines.