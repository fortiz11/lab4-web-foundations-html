# Lab 4 – Web Foundations: HTML Exploration  

## Overview  
This lab focused on learning the fundamentals of HTML. This assignment emphasized how writing clean, valid markup is important for accessibility, maintainability, and avoiding technical debt.  

## Key Activities  
- **Project Setup**  
  - Created a GitHub repository (`lab4-web-foundations-html`) and a `docs` folder to hold project files.  
  - Used VS Code with Live Server to preview HTML pages over HTTP.  
  - Practiced proper commit messages and incremental Git usage.  

- **Validation**  
  - Built an initial `index.html` with headings, paragraphs, entities, and comments.  
  - Explored how whitespace and malformed tags behave.  
  - Used the [W3C Validator](https://validator.w3.org/) to identify and fix errors/warnings until the page passed validation.  
  - Captured screenshots of both failure and success (`validation-fail.png`, `validation-pass.png`).  

- **Kitchen Sink HTML Page**  
  - Added a wide range of HTML elements to test their behavior using [Mdn](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/var).
  - Skipped deprecated/unsupported tags as instructed.  
  - Created a custom element `<my-school>` to display my school’s name.  
  - Demonstrated `data-*` attributes for storing custom data inside elements.  
  - Applied a CSS style rule to make `<h1>` headings blue.  
  - Wrote a simple `<script>` to display the current date and time.  

- **Publishing**  
  - Committed all changes to GitHub with a clear history of progress.  
  - Published the page with GitHub Pages.  

## Reflections / Issues  
- Validator helped me understand the difference between **errors** (must fix) and **warnings** (best practices).  
- Discovered how `data-*` attributes and custom elements can extend HTML meaning.  
- Practiced separating **content (HTML)**, **style (CSS)**, and **behavior (JavaScript)**.  
- Some challenges were debugging validation errors caused by misused or misplaced tags and correcting certain tags with proper tag ending (i.e. `/>` or `>`)

## Deliverables  
- `index.html` with a wide variety of HTML tags.  
- Validation screenshots: `validation-fail.png` and `validation-pass.png`.  
- Published site via GitHub Pages.  

## License

This project is licensed under the MIT License- see `LICENSE.md` for details. 

## Author 
Francis Ortiz
