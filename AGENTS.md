This project handles health data locally in the browser. All CSV processing must remain fully client-side, with **no external network requests** for file contents or derived data.

For all future changes within this repository:
- Never send CSV contents or user-entered data to any server.
- Do not add analytics or telemetry beyond a basic page view count.
- Keep all parsing, charting, and template generation strictly local in the browser.
