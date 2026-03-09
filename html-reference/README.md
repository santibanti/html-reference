# HTML Elements Exploration Project

This project is a comprehensive exploration of HTML elements, semantics, and historical features. The goal of the assignment was to demonstrate understanding of modern HTML structure, accessibility considerations, media embedding, forms, tables, and semantic elements while also recognizing deprecated or obsolete tags that should no longer be used in modern development. The project includes multiple pages that systematically showcase different categories of HTML elements, such as metadata, text semantics, embedded media, interactive elements, and form controls. It also includes a dedicated page highlighting deprecated elements to illustrate the evolution of web standards and why modern HTML favors semantic structure and CSS-based styling over presentational markup.

Note on LLMs: if you ask ChatGPT to help you understand and produce example cases for a couple tags at a time, it does a fairly good job at explaining and correctly using them, only having minimal validator errors. Additionally, it came up with good edge cases/ creative ways to stretch the capabilities of html when I was coming up with experiment examples. However, the description of LLMs as dumb interns is pretty accurate, as it also ended up defaulting to overriding the linked css stylesheet to optimize for presentation in the experiments.html, but it made the experiments look more self-contained and so I decided to keep its overide. Additionally, the use of div tags for the architecture here I was found was applicable due to the nature of the experiments file (the fact that we're supposed to be stretching the capabilities/allowed functions of the tags and html in general)

## Custom Experiments

In addition to the required demonstrations, the project includes three experimental sections designed to push HTML to its limits and explore unconventional uses of native elements:

1. **Disclosure Labyrinth** – This experiment abuses nested `<details>` and `<summary>` elements to create an interactive "collapsing universe" structure where the user drills down through increasingly deep layers of content.

2. **Faux Operating System Dashboard** – This section uses `<meter>`, `<progress>`, animated text, and unusual layout choices to simulate a fictional system monitoring interface entirely with basic HTML and CSS.

3. **Mrs. Chicken Reality Intake Form** – A deliberately absurd form that combines a wide variety of input types, outputs, dialogs, and interactive controls to demonstrate form capabilities while stretching them into a surreal user experience.

These experiments intentionally push beyond conventional web design to explore how far native HTML features can be extended or repurposed in creative ways.
