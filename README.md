# Tailwind CSS Classes Not Working - Import Issue

This repository demonstrates a common issue where Tailwind CSS classes appear to be correctly implemented, but they don't function as expected.  The problem lies in the inclusion of the compiled CSS file within the HTML.

## Bug
The `bug.js` file shows a standard Tailwind setup, but the compiled CSS isn't linked. This is simulated for demonstration.

## Solution
The `bugSolution.js` file corrects the issue by adding the correct `<link>` tag to include the compiled Tailwind CSS file.

## How to reproduce
1. Clone the repository.
2. Observe that Tailwind styles are not applied in `index.html`.
3. Uncomment the line in `index.html` within `bugSolution.js` to see the styles being applied.

## Lessons Learned
Always verify that your compiled CSS file (typically generated during the Tailwind build process) is properly included in your HTML file. This is a frequent oversight that causes styling issues.