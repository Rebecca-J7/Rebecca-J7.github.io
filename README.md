# CS110 - Personal Page: Rebecca's Portfolio

# Phase 1

For the first phase you’ll be creating only the HTML portion of your profile page without any CSS elements. Start by creating a GitHub repository for your site by following steps 1-2 of the GitHub Pages getting started page (you’ll be using GitHub pages to publish your site).
If you are already using GitHub Pages for another site you are hosting you can use a regular repository for this assignment instead.

Created an index.html file which contains the following: <br/>

Header Section <br/>
Title <br/>
charset <br/>
Body Section <br/>
Headshot photo (or Avatar) <br/>
Your name (h1) <br/>
Some type of subheading (h2) <br/>
Socials (your choice) <br/>
About section (h3 followed by a paragraph) <br/>
Work Experience (h3 followed by a table or flexbox) <br/>
First row should contain company name, title, and dates of employment <br/>
Second row should be a description of what you did at that job (and take up all three columns) <br/>
Education (h3 followed by a table or flexbox) <br/>
Coursework (h3 followed by an unordered list) <br/>
Note in my example I use “courses taught” instead of coursework <br/>
Skills (h3 followed by an unordered list) <br/>
Projects (h3 followed by an unordered list or table) <br/>

# Phase 2

For this phase you’ll be adding custom CSS in a <style> block in the header section of your index.html. For this phase you should concentrate on updating the layout of the page and should consider modifying the alignment, spacing (padding, margin, border), element sizes, fonts, etc. Don’t worry about additional design elements such as colors, you’ll update those in the next phase. You can bring your own personal style here to determine how you want to modify the layout, but must make changes to improve it. There is no specific layout that you need to adhere to, but should consider the following: <br/>

Updating the alignment between your photo and text to reduce bulk unused whitespace <br>
Update spacing around the page as well as between sections and elements so they are easier to make reading the page easier (recommended reading, importance of whitespace in design) <br/>
Update the indentation for your lists and tables so they are distinguishable from the headers, likely through indentation (note that lists are already indented) <br/>
Specify a set of fonts so your page looks more consistent across browsers (if you load a custom font, it will look the same on all browsers), consider using different fonts in different portions of the page to help break up the sections and improve readability <br/>


# Phase 3

For this phase you'll restructure your project to separate your HTML and CSS into separate files. Create one directory images/ for your profile photo and any other images you include. Create a secondary directory styles/, and migrate your CSS file(s) to that directory. Update your index.html document to update the references to your image elements and link to your now separated stylesheet(s). Don’t forget to remove the <style> section from the previous phase.  <br/>

Now that you have separate stylesheets, spend some time updating your page design with custom colors and/or images and fine tuning your layout. Your profile page should be a reflection of both your skills and your design taste, so spend some time on the details. The instructor's example should be considered the minimum design not the ideal. <br/>

Use icons or images as additional design elements for things like social links, section headers, list icons, etc. There are lots of place to find free icons online  <br/>
A vertical or horizontal line elements in addition to whitespace to break up sections and make the page more readable  <br/>
Style your links (including after they are clicked) to match you general page style, and set a target so it opens links in a new page  <br/>
Expand your custom CSS classes to use different styles in different sections of your page  <br/>

# Phase 4

For this last phase you’ll be updating the way your site is read and interpreted by other sites. Sites need to be performant and accessible so users want to use them, they need to be well formatted for consumption by bots so they can be indexed by search engines, and they may need additional meta information to support specific use cases like well formatted sharing on social media. In this phase you’ll make some basic updates to support these cases, and we’ll dig more into these topics during the course. <br/>

Start by updating your page with additional header information to support share cards in Facebook, Twitter, and LinkedIn and on the Fediverse. Each one requires a slightly different (and sometimes slightly overlapping) set of additional fields to be added to your site's header.
