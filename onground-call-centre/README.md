# On-Ground.ai — Call Centre Workspace Demo

A responsive front-end prototype for the On-Ground.ai Call Centre assignment, built with **HTML, CSS and vanilla JavaScript**. It uses local sample data and requires no backend or package installation.

## Run locally

1. Extract the ZIP.
2. Open the `onground-call-centre` folder in VS Code.
3. Start a local server from that folder:
   ```bash
   python -m http.server 8000
   ```
4. Visit `http://localhost:8000` in your browser.

You can also open `index.html` directly, but a local server is recommended for consistent browser behaviour.

## Stack and rationale

- **HTML** for semantic page structure.
- **CSS** for responsive layout, component styling, and mobile adjustments.
- **Vanilla JavaScript** for navigation, local sample data, lead details, filtering, chat interactions, calendar controls, and the dialer demo. This keeps the project easy to run and review without a build step.

## Included demo features

- Dashboard with KPI cards, progress, lead/task panels and chart visuals.
- Calls-to-make, incoming calls and recent calls views.
- Calendar month navigation and Today shortcut.
- Pulse channel and sample chat interactions.
- Lead list, lead detail modal, buying signals, previous/next navigation and add-lead form.
- Search/filter interactions and responsive mobile layout.
- Phone dialler using a `tel:` handoff, plus optional browser speech practice where supported.

## Important calling limitation

The phone action hands the number to the user's configured phone app via a `tel:` URL. The optional speech feature uses the browser's local speech APIs for a scripted practice prompt. **Neither feature is a real AI-powered outbound telephone calling integration.** No telephony provider, server-side call control, or AI voice agent is connected in this demo. Do not present the calling feature as a production or real AI calling system.

## Sample data and persistence

All lead, calendar, and chat data is demonstration data in the front end. Changes are not saved to a server or shared with a team.

## AI assistance

AI assistance was used to help draft and refine the front-end implementation and documentation. Review, test, and understand the code before submission, and disclose AI use according to the assignment instructions.

## Before submitting

- Test every screen and action in your browser.
- Add your own GitHub repository link and optional live demo link to your submission email.
- Only claim features you personally verified. A live link and a short screen recording are bonus items in the assignment brief.
