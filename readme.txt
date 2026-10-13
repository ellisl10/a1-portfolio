--Readme document for Ellis Liang, ellisl1@uci.edu--

A reminder on academic integrity, as described in the syllabus.

In general, the course staff expects that you will look at code and examples from many online resources as part of the assignments, particularly to resolve syntax and understand frameworks. We expect that you'll use other libraries you find, and will even require it in some assignments. These practices are often critical to the work of developers today. The best developers are adept at interpreting the examples they see, customizing them to their specific situation, and citing their sources so they can find them later. We expect you to do the same.

While learning from examples is encouraged, attempting to pass an existing project or example from the web as your own is not allowed. If you ever have a question about what is or is not appropriate, feel free to ask the course staff!

Talking to classmates about class material, assignment requirements, etc. is a great way to verify ideas and get feedback. But this distinctly does *not* permit attempting to pass off someone else’s code as your own. Talking over ideas and approaches is allowed, but the work that you produce and submit must be your own.

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

10/10
- 1/1 Readme
- 2/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature
- 2/2 Responsive layout
- 1/1 Passes validation checks
- 2/2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features
Images with descriptive alt attributes, headings and paragraph text, links to external pages, multiple pages with navigation between them, and custom icons using Google Material Icons.


(b) CSS features
Modifying padding and margins, modifying link, text color, or other colors, adding custom fonts (with fallbacks)



(c) Advanced features
Creating a more complex page layout by including a navigation bar and leveraging nested selectors to specify format




3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.
The potential problems throughout my portfolio fell into these categories: images and icons, third-party scripts, navigation structure best practices, and link purpose elements. I chose to ignore these warnings because:

Automated tools cannot verify whether alt text perfectly captures contextual nuances.

Third-party scripts like the Bootstrap bundle trigger automated warnings due to the scanner's inability to statically analyze runtime DOM behavior.

Structural best practices, such as missing skip links, sitemaps, or text direction attributes, are advisory recommendations rather than strict WCAG 2.0 AA violations.

Link purpose warnings occur when icon fonts mixed with text confuse the scanner into thinking links are unlabeled.

Essentially, because the warnings from the accessibility checker are generally due to the checker's own limitations or involve advisory recommendations rather than strict violations, I chose to ignore them.

I did not ignore any errors.


4. How long, in hours, did it take you to complete this assignment?
8 hours


5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)
I used the Bootstrap documentation, especially for creating page layout and adding Bootstrap components such as the navbar. 
I also used generative AI on the use of components and generating alt text, using the following prompts: 
    1. "Is it better to have a new navbar component on each page, or have one section of the page re-render dynamically on page navigation?"
    2. "How do you navigate between pages using nav links?"
    3. "Describe this image for an alt text attribute."
    4. "How can I create a list of project cards?"
I used this tutorial to create the typing effect https://css-tricks.com/snippets/css/typewriter-effect/.

6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?
I did not consult with classmates or other individuals.


7. Is there anything special we need to know in order to run your code?
No

