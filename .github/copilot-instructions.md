# Copilot Workspace Instructions for DAEDUCK AI Hub

## Overview
This workspace is a single-page web application (SPA) for DAEDUCK AI Hub, providing a unified interface to search and use various internal AI Agents. The project is implemented as a static HTML/CSS/JS file (`index.html`).

## Build & Test
- No build step is required; open `index.html` directly in a browser.
- No backend or package dependencies are present.
- For local development, simply edit `index.html` and refresh the browser.

## Key Conventions
- All UI, logic, and data are contained in `index.html`.
- AI Agent metadata is managed in the `agents` array within the `<script>` tag.
- Korean is used for most UI text and comments.
- CSS custom properties (variables) are used for theming.
- No external libraries or frameworks are used.

## Project Structure
- `index.html`: Main and only file. Contains all HTML, CSS, and JavaScript.

## Potential Pitfalls
- Large file: All logic and styles are in one file, which can make navigation harder as the project grows.
- Manual agent management: To add or update agents, edit the `agents` array in the script section.
- No persistent storage: All data is in-memory; changes require editing the file.

## Documentation
- No additional documentation files are present. All relevant information is in this instruction file and in comments within `index.html`.

## Example Prompts
- "Add a new AI Agent for translation."
- "Change the primary color theme."
- "Update the description for the '코드 리뷰 AI' agent."

## Next Steps & Customizations
- For more complex logic, consider splitting code into separate JS/CSS files and updating this instruction file.
- To add agent-specific instructions, use `applyTo` patterns in future instruction files if the project grows.

---
For further customization, see the [agent-customization skill documentation](https://github.com/features/copilot).
