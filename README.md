Bootstrap 5 UI "Remix" Project

Live URL: https://YOUR-USERNAME.github.io/YOUR-PROJECT-NAME
(Remember to replace this with your actual GitHub Pages link after you deploy!)

Project Overview

This project is a 3-page static website built to fulfill the internship task of exploring and remixing Bootstrap 5 components. The goal was to create a clean, modern, and responsive website by combining different components from the Bootstrap examples, rather than just copying a single template. The final site includes a Home page, an About Us page, and a Contact page with a working form.

My Process (Our Process!)

Our development process was very step-by-step, focusing on building the site one component at a time.

Setup: We started by creating the three required files (index.html, about.html, contact.html) in VS Code. We also set up the "Live Server" extension to see our changes in real-time.

Boilerplate: We added the official Bootstrap 5 CDN links for CSS and JavaScript to our index.html file to get a basic "Hello, Bootstrap!" page working.

Component "Shopping": As per the task, we went to the Bootstrap Examples pages to "remix" our site.

Building index.html: We built the home page by adding components one by one:

First, we explored the Navbar examples, copied the HTML for one, and pasted it into our index.html.

Next, we went to the Heroes example page, used the "Inspect" tool to find the code for a hero we liked, and copied/pasted that right after the navbar.

We did the same for the Features example ("Custom cards") and the Footers example.

Building Other Pages:

We copied the full index.html code into about.html and contact.html to keep the navbar and footer.

For about.html, we deleted the middle (hero/features) and added a new "About Us" section using a different Bootstrap component.

For contact.html, we did the same, adding a form from the Bootstrap Forms documentation.

Connecting & Polishing: Finally, we went back through all three files and updated the links in the navbars and footers to point to each other (index.html, about.html, contact.html) so the site navigation worked.

Tools Used

HTML5 & Bootstrap 5: Used for all layout and styling, primarily using the CDN.

VS Code: Our code editor.

VS Code Live Server: This was essential for seeing our changes instantly.

Bootstrap 5 Docs & Examples: We used this constantly to find and copy component code.

Gemini (My AI Teacher): I used my AI training teacher, Gemini, quite a bit. It helped me form a step-by-step plan. I also relied on it for debugging when I got stuck and didn't understand why my site was broken.

Challenges Faced & How We Solved Them

This was the most important part of the project. We faced one major, critical challenge that stopped the entire project from working.

The Big Challenge: The xintegrity Typo

Problem: After pasting all our components, the entire website was unstyled. The navbar was a blue list of links, and everything was broken, just like my first screenshot. I had no idea why.

Solution: We debugged this together with Gemini. We found a tiny, almost invisible typo in my code on both the <link> and <script> tags for Bootstrap. I had written xintegrity="..." instead of integrity="...". This single x typo caused the browser's security to block both the CSS and JavaScript files from loading.

Fixing this typo by deleting the x in all three files (index.html, about.html, contact.html) instantly solved the problem and made the entire site appear perfectly styled.

Minor Challenge: Broken HTML

Problem: At one point, I had also accidentally pasted my entire page inside an <h1> tag, which was breaking the layout.

Solution: We fixed this by correcting the HTML structure, making sure the navbar, hero, and all other sections were separate elements in the <body>, not nested inside each other incorrectly.

Time Taken

Total Time: Approximately 1-2 hours (This includes learning, exploring, and debugging the xintegrity issue).