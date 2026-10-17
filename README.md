StoryCast — Dream in Progress

StoryCast is a three-page accessible storytelling microsite for the Advanced Front-End Web Development assignment. Dream in Progress is the concept behind the project: sharing a sample story about a young entrepreneur in a clear, accessible format.
Content note: Amina and her story are fictional examples created for this prototype. They are not a real person or a real interview.

Pages
- index.html — Home page introducing StoryCast and highlighting stories.
- story/amina.html — Sample story detail page with written story content and a transcript.
- about.html — About / Access page explaining the project mission and accessibility features.
All pages use shared navigation so visitors can move between the main sections.
Research and Planning
- Research document: docs/research-document.pdf
- Sitemap source file: docs/sitemap.md
- Figma wireframes and high-fidelity mockups: Open the StoryCast designs
The sitemap file listed above is Markdown (.md), not a PDF diagram. If the assignment requires a sitemap diagram as a PDF, export or create the diagram and add the resulting PDF to the repository.
Technology
- Semantic HTML5
- Sass (sass/main.scss) with partials for colors, typography, and spacing
- Compiled CSS (css/style.css)
- CSS Grid and Flexbox
- Media queries and a container query
- No CSS or JavaScript frameworks
Run Locally
1. Clone or download the public GitHub repository.
2. Open the dream-in-progress folder in VS Code.
3. Open index.html in a browser, or use the Live Server extension.
4. If you edit the Sass files, install Sass and run this command from the project root:
   sass sass/main.scss css/style.css --watch
Accessibility Checklist
- [x] Semantic HTML landmarks and a logical heading hierarchy
- [x] Skip link to the main content
- [x] Visible keyboard focus states
- [x] Descriptive alternative text for informative images
- [x] Written content/transcript for the fictional sample story
- [x] Responsive layout for desktop, tablet, and mobile
- [x] Reduced-motion preference supported
- [x] Container query used for the media panel
- [ ] Test all final color combinations with a WCAG contrast checker
- [ ] Test every page using keyboard-only navigation
- [ ] Test screen-reader behavior
- [ ] Run an HTML validator and Lighthouse accessibility audit
Media note: The current prototype does not include a recorded video or real interview. Therefore, it does not claim to provide video captions. If audio or video is added later, provide an accurate transcript and captions where appropriate, including a <track kind="captions"> element for video when needed.
The checked items describe features intended to be implemented in the project. Verify each item against the actual code before relying on it as a completed test.
Design Rationale
The cream background, dark green typography, and lime accents create a warm editorial style. Large headings and story imagery help visitors scan the content. The story page emphasizes readable written content and a transcript so that understanding the example does not depend on audio or video.
# Project Structure


```text
dream-in-progress/
├── index.html
├── about.html
├── story/
│   └── amina.html
├── sass/
│   ├── _colors.scss
│   ├── _typography.scss
│   ├── _spacing.scss
│   └── main.scss
├── css/
│   └── style.css
├── docs/
│   ├── research-document.pdf
│   └── sitemap.md
└── README.md
```

# figma link
https://www.figma.com/design/nE6KJ6mURLlW4a2NmgE9bu/storycast--website--mockups?node-id=0-1&p=f&t=F8ilEXS0KWLgQPJ7-0
