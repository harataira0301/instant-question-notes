# Instant Question HTML Notes

Use this skill when the user asks to turn a question into a static HTML technical note, especially when the prompt starts with `質問:` or `質問：`.

## Workflow

1. Identify the topic, audience, and safest category path.
2. Research primary or official sources when the topic may be current, factual, technical, legal, medical, or otherwise sensitive.
3. Create or update one static HTML note under a category directory.
4. Add the note to the root `index.html`.
5. Include `Summary` and `References` in the note.
6. Run a lightweight local check, such as verifying links and opening the HTML structure.
7. Show the diff summary and wait for explicit approval before pushing.

## Content Rules

- Prefer official documentation, standards, source repositories, papers, or vendor docs.
- Do not include secrets, private data, internal company details, or credentials.
- Do not invent citations.
- Mark uncertain or fast-changing claims clearly.
- Keep the page build-free: HTML, CSS, SVG, and images only.

