--Readme document for Jiaxun Huang, jiaxunh1@uci.edu--

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
I added a personal photo with descriptive alt text, use headings and paragrahs to introduce my background and interests.
I also inclued external links to UCI, CCSF, and my github profile, used main and footer tag and Email and resume links.

(b) CSS features
I adjusted padding and margins to add space around the page and between sections. 
I used a dark background, light text, and purple links for the page. 
I also styled the photo to resize with the screen and added padding, borders, and a different header background color to the course table.

(c) Advanced features
I created a table showing my completed and current courses at UC Irvine. 
It includes multiple rows and columns, a caption, and row and column headers.
I used scope, id, and headers attributes to associate the data cells with their headers for screen readers(this is recommanded by AChecker).

3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.
I fixed the known problem in the course table by adding id and headers attributes. The final AChecker result showed 0 known problems, 0 likely problems, and 32 potential problems. These potential problems needed manual checking.
I checked the potential problems. I kept the code when the warnings did not apply to my page. My personal photo has alt text that identifies me. It is not just a decoration and does not need a long description. It does not use color alone to give information or contain important text that needs to be included in the alt text.
My page is written in English and does not change text direction. Cantonese, Mandarin, and English are language names written in English, so they do not need separate language attributes. The Languages list uses ul and li tags.
The course table has a caption that explains what it shows. It uses thead and tbody to separate the headings and data. It also has row and column headers linked to the data cells. It is a data table, so using th tags is correct. Its four-column structure is simple, so it does not need an extra summary or colgroup elements. It has no totals or summary rows, so it does not need tfoot.
The page does not tell users to find something only by its shape, size, color, or position. The h1 is the main page heading, and the h2 tags are section headings. They are not used only to make text look bigger. The page title, Jiaxun Huang, identifies the person the website is about.
The links explain where they go. The school links use the school names, the email link shows my email address, and the GitHub username has a GitHub label before it. The Resume link leads to my resume. The related contact links are grouped in the footer.
This website has one page and no repeated navigation before the main content. I did not add a site map or a skip-to-content link. There are no repeated navigation components in different orders. There are also no long quotations, so blockquote tags are not needed.
AChecker could not load my local photo because I only uploaded the HTML file. The photo displays correctly when I open my website locally.


4. How long, in hours, did it take you to complete this assignment?
10 hours


5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)
I used other people's portfolio as references: https://cheryllao.me/
I also asked help from ChatGPT about how to load bootstrap, how to review the report from AChecker and other tags that were not taught in class.

6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?
None.

7. Is there anything special we need to know in order to run your code?
An internet connection is needed to load Bootstrap from the CDN. 
Keep style.css, profile.jpg, and Resume.pdf in the same folder as index.html so the styles, photo, and resume link work correctly.
