# Getting Started With CSS Framework

## Contents
[Custom properties and variables](#custom)
[CSS Frameworks](#frameworks)
[Bootstrap](#bootstrap)
[TailwindCSS](#tailwind)
[References and Resources](#ref)

## CSS Custom Properties and Variables <a name="custom"></a>
**CSS custom properties (aka CSS variables or cascading variables)** allow you to store and reuse values throughout your stylesheet.They act as placeholders for values that can be easily changed in one place, affecting all styles that use them.

**Benefits:**

- **Maintainability:** Reduce code duplication and make your styles more organized and easier to update.
- **Themeability:** Easily switch between different themes by changing only the values of custom properties.
- **Dynamic styles:** Create dynamic styles that react to user interaction or browser features using JavaScript.

**How to use them:**

- 
 **Declare the custom property:**
    - Using two dashes as a prefix (`--variable-name: value;`)
    - Using the `@property` at-rule (`@property --variable-name { syntax: <value-type>; initial-value: value; }`)

- 
 **Use the `var()` function** to access the value (`background-color: var(--primary-color);`)

**Key points:**

- Custom properties are **scoped** to the element(s) they are declared on and participate in the cascade.
- They can be used to store all types of CSS values, including colors, lengths, fonts, and even complex calculations.
- Values can be **overridden** by declarations with higher specificity.
- JavaScript can be used to access and modify custom properties dynamically.

## Use Case: Theme Switching with CSS Custom Properties

Imagine you're building a website with two distinct themes: light and dark. You want to make it easy for users to switch between these themes on the fly.

**Without Custom Properties:**

You would need to duplicate your entire stylesheet, replacing all the color values for each theme. This would lead to a lot of code duplication and make it difficult to maintain.

**With Custom Properties:**

- 
Define custom properties for your primary colors:

![theme.css](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/u8gybacfamp67xve2h4k.png)

- 
Use these custom properties throughout your stylesheet:

![custom properties](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/o3z8pyrglmlhml627mw3.png)

- 
Create buttons or a toggle to switch the values of the custom properties:

![button](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/4268ezzgez5auo4qml1g.png)

By changing the values of just these four custom properties, you can instantly switch the entire theme of your website. This demonstrates the power and flexibility of CSS custom properties.

## CSS Frameworks <a name="frameworks"></a>
CSS frameworks are pre-built collections of CSS styles that provide a solid foundation for web development. They offer pre-defined styles for common elements like buttons, forms, and grids, saving you time and effort.

**Benefits:**

- **Faster development:** Jumpstart your project with ready-made styles and components.
- **Consistency:** Ensure consistent design across your website.
- **Responsiveness:** Many frameworks provide responsive design features, making your website look good on all devices.
- **Community and resources:** Access a large community of developers and extensive documentation for support.

**Popular Frameworks:**

- **Bootstrap:** Widely used, mobile-first framework with a vast library of components.
- **Tailwind CSS:** Utility-first framework for building custom designs with low-level classes.
- **Material Design:** Google's framework based on their design principles, offering a clean and modern aesthetic.
- **Foundation:** Flexible framework with a focus on accessibility and modularity.
- **Bulma:** Lightweight and minimalist framework with a focus on simplicity.

**Choosing a Framework:**

Consider your project needs, desired level of customization, and team experience when choosing a framework.

**Key Points:**

- Frameworks can simplify development but may add complexity and bloat to your code.
- Learn the framework's core principles to leverage its full potential.
- Customize the framework to suit your specific needs and brand identity.

## Bootstrap <a name="bootstrap"></a>
**Quickstart**
Skip the setup, jumpstart your web project with Bootstrap's CDN!

- 
Create a new index.html file in your project directory and create the basic boilerplate.

![index](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/fgo2v6tbp4esky73iwmc.png)

- 
Include Bootstrap's `.min.css` in your `<head>` for styling and Add Bootstrap's `.bundle.min.js` before closing `<body>` for interactivity (includes Popper for dropdowns etc.).

![Bootstrap CDN](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/s601eqr16s1u6cudr64a.png)

### Project 1: Arsenal Vibes
{% embed https://github.com/jrshittu/Arsenal-Vibes %}

**Check the finished project here👇**
{% embed https://jrshittu.github.io/Arsenal-Vibes %}

## TailwindCSS <a name="tailwind"></a>
**Quickstart**
Skip the setup, jumpstart your web project with tailwindcss's CDN!

- Create a new index.html file in your project directory and create the basic boilerplate, then add the cdn link in the head section.

![TailwindCSS](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/8xh5a7dwl3b8lssh4sik.png)

### Project 2: Arsenal Vibes with TailwindCSS
{% embed https://github.com/jrshittu/Arsenal-Vibes-TailwindCSS %}

**Check the finished project here👇**
{% embed https://jrshittu.github.io/Arsenal-Vibes-TailwindCSS/ %}

**References and Resources:** <a name="ref"></a>

- **MDN Web Docs:** [https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)
- **W3Schools:** [https://www.w3schools.com/css/css3_variables.asp](https://www.w3schools.com/css/css3_variables.asp)
- **GitHub Pages Sample:** [https://ucsb-meds.github.io/customizing-websites-css/](https://ucsb-meds.github.io/customizing-websites-css/)
- **Comparison of CSS frameworks:** [https://css-tricks.com/considerations-for-making-a-css-framework/](https://css-tricks.com/considerations-for-making-a-css-framework/)
- **A Beginner's Guide to CSS Frameworks:** [https://www.freecodecamp.org/news/best-css-and-css3-tutorial/](https://www.freecodecamp.org/news/best-css-and-css3-tutorial/)
## Bootstrap References & Resources: Dive In and Build!
* **Official Documentation:** Your comprehensive guide to Bootstrap's classes, components, and utilities. [https://getbootstrap.com/docs/5.2/getting-started/introduction/](https://getbootstrap.com/docs/5.2/getting-started/introduction/)
* **CDN Links:** Grab pre-built production-ready CSS and JS with no setup needed. [https://getbootstrap.com/docs/4.0/getting-started/download/](https://getbootstrap.com/docs/4.0/getting-started/download/)
* **Starter Templates:** Jumpstart your project with pre-designed layouts and components. [https://getbootstrap.com/docs/4.0/examples/starter-template/](https://getbootstrap.com/docs/4.0/examples/starter-template/)
* **Bootstrap Tutorial:** Step-by-step guide to building your first Bootstrap website. [https://www.w3schools.com/bootstrap5/](https://www.w3schools.com/bootstrap5/)
* **Interactive Playground:** Experiment with Bootstrap components and explore their different options. [https://www.codeply.com/](https://www.codeply.com/)
* **Bootstrap Cheatsheet:** Quick reference for key classes and utilities. [https://devhints.io/css](https://devhints.io/css)
* **Bootstrap Forums:** Ask questions, get help, and connect with other Bootstrap enthusiasts. [https://stackoverflow.com/questions/66365247/getbootstrap-com-vs-bootstrapdocs-com-are-these-supposed-to-be-the-same-things](https://stackoverflow.com/questions/66365247/getbootstrap-com-vs-bootstrapdocs-com-are-these-supposed-to-be-the-same-things)
* **Bootstrap Showcase:** Get inspired by amazing websites built with Bootstrap. [https://bootstrapbay.com/blog/built-with-bootstrap/](https://bootstrapbay.com/blog/built-with-bootstrap/)
* **Bootstrap Blog:** Stay updated on the latest news, releases, and tutorials. [https://blog.getbootstrap.com/](https://blog.getbootstrap.com/)
* **TailwindCSS Website** [https://tailwindcss.com/docs/installation](https://tailwindcss.com/docs/installation)
* **Documentation:** [https://tailwindcss.com/docs/installation](https://tailwindcss.com/docs/installation) - Comprehensive guide to installation, configuration, usage, and customization.
* **Play CDN:** [https://play.tailwindcss.com/](https://play.tailwindcss.com/) - Interactive playground to experiment with Tailwind classes.
* **GitHub Repository:** [https://github.com/tailwindlabs/tailwindcss](https://github.com/tailwindlabs/tailwindcss)
* **Tailwind UI:** [https://tailwindui.com/](https://tailwindui.com/) - Official Tailwind CSS components and templates.
* **Tailwind Labs Blog:** [https://tailwindcss.com/blog](https://tailwindcss.com/blog)
* **YouTube Channel:** [https://m.youtube.com/watch?v=UBOj6rqRUME](https://m.youtube.com/watch?v=UBOj6rqRUME) - Tutorials, tips, and discussions from official team and community.
* **Tailwind Essentials:** [https://www.frontendreference.com/get-started-with-tailwindcss.html](https://www.frontendreference.com/get-started-with-tailwindcss.html) - Interactive course for beginners.
* **Frontend Masters Workshop:** [https://frontendmasters.com/workshops/tailwindcss/](https://frontendmasters.com/workshops/tailwindcss/) - Advanced-level workshop by Adam Wathan, co-creator of Tailwind.
* **FreeCodeCamp Tutorial:** [https://www.freecodecamp.org/news/tag/tailwind/](https://www.freecodecamp.org/news/tag/tailwind/) - Comprehensive video tutorial.
* **Tailwind Discord:** [https://github.com/willianjusten/discord-tailwind](https://github.com/willianjusten/discord-tailwind) - Active community for discussions, Q&A, and sharing projects.
* **Awesome Tailwind:** [https://github.com/aniftyco/awesome-tailwindcss](https://github.com/aniftyco/awesome-tailwindcss) - Curated list of Tailwind resources, tools, and plugins.
* **Stack Overflow:** [https://stackoverflow.com/questions/tagged/tailwind-css](https://stackoverflow.com/questions/tagged/tailwind-css) - Search for solutions and ask questions.
* **Tailwind UI Showcase:** [https://tailwindcss.com/showcase](https://tailwindcss.com/showcase) - See how others are using Tailwind to build beautiful websites.
* **Design System with Tailwind:** [https://university.webflow.com/lesson/figma-to-webflow-plugin](https://university.webflow.com/lesson/figma-to-webflow-plugin) - Tool to convert Figma designs to Tailwind code.
* **Tailwind Hero Icons:** [https://heroicons.dev/](https://heroicons.dev/) - Free pack of SVG icons compatible with Tailwind.
* **Tailwind Starter Kits:** [https://www.creative-tim.com/learning-lab/tailwind-starter-kit/presentation](https://www.creative-tim.com/learning-lab/tailwind-starter-kit/presentation) - Pre-built UIs and templates to accelerate development.

**☕ Enjoyed this article? Support my work with a coffee: [https://www.buymeacoffee.com/cqvuesleq](https://www.buymeacoffee.com/cqvuesleq)**

**Also open for technical writing and frontend dev roles!**

