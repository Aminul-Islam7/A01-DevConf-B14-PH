# Prompts Used for The Placeholder Section

**Prompts to Claude:**

- Suggest ideas for the missing section that matches with the DevConf 2026 theme (e.g. Sponsors, Venue, FAQ, Newsletter Signup, Hackathon Details, Past Highlights, Job Board, etc. or something similar or completely different). It should be something that's not too complex but visually stunning/impressive. Since it's a landing page, it can also be something interesting that convinces the user to make a purchase.
- I like the idea of combining #1 (countdown/urgency) with #3 (stats strip). But i need a visual design for this before i start coding. write a prompt for generating the ui design for the missing section using Google Stitch.
- you might've analysed wrong. the missing section is actually after the pricing section. and before the footer (which is dark background, but got cropped out in the image i sent you). so rewrite the prompt accordingly. also, i'm attaching the figma file into stitch. don't need to be too detailed and specific about the design. just write a short prompt

**Prompt to Google Stitch:**

Design a web section for "DevConf 2026" that sits after the pricing section (white background) and right before the footer (dark background) — so this section should work as a transition, using a dark background to match the footer below it.
Purpose: build urgency and social proof to convert visitors before they leave the page.
Include:

- A short headline like "Don't Miss Out" or "Seats Are Filling Fast"
- A row of 4 key stats (e.g. 4,000+ Attendees, 48 Talks, 3 Days, 92% Would Return)
- A live countdown timer (days/hours/minutes/seconds) until early-bird pricing ends
- A progress bar showing early-bird seats claimed (e.g. 783/1000)
- A closing CTA button to register

Keep it visually consistent with the rest of the page (fonts, colors, button and card styles from the attached Figma file).

**Prompts to Gemini:**

- how do i make a progress bar like this using only html and css?

## Other Prompts I Used for Learning / Assistance during The Project:

**Tools used:** Gemini, Google Search (AI Mode)

- I'm about to convert this design to an html css webpage for practice. how do i name the classes for each div of each section to keep it organized? what are the industry standards? how should i think when I need to name a class? should i follow any methodology as a beginner in html-css?
- i am only using html and css. and i'll also have images in the repo. what should be the file structure. i want to apply the industry standard practices even for this small project.
- can i personalize the vscode commit message generator sparkle button's message generation? i want it to always generate very concise messages and use the most relevant identifier (like, feat, style, refactor, etc.)
- what should be the serial/hierarchy of these elements: `<header>`, `<nav>`, `<main>`, `<section id="hero">` in a landing page?
- should i select header and nav tags directly from my css file? or add ids to them and select using ids?
- how and where (in which css file) should i organize reusable things like buttons, and how to name the classes?
- should i use .container in bem methodology for setting max-width? if yes, in which level in the html sections do i apply it?
- what's the best way to add a full width hero image and a semi-transparent overlay over it below hero content? should i use html or css to add the image?
- is there any css technique to use a defined variable color and use it's lighten or darkened version for hover effect
