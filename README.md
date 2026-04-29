# NIFT × Info Edge — Faculty Edition

Two self-contained HTML artifacts for the NIFT faculty workshop:

- [faculty.html](faculty.html) — facilitator deck
- [faculty-resources.html](faculty-resources.html) — AI tools list / takeaway page

Plus the student field guide ([resources.html](resources.html)) linked from the faculty resources page.

No build step. Each file is a single HTML page that loads React + Tailwind from CDNs and compiles JSX in the browser. Open directly or serve locally:

```bash
python3 -m http.server 8080
```
