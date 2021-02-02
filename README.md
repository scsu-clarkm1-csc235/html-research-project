# HTML Research Page
In this assignment you will research an area of web application security and present your findings as an HTML page.

## Objectives
* Practice constructing an HTML page with fundamental HTML elements.
* Understand the difference between absolute and relative URL's.
* Identify and describe a security threat that affects web applications.
* Implement images in a web page.
* Implement hyperlinks in a web page.

## Instructions
Web application security is an extremely important topic in web development today. Poorly designed applications that don't properly implement security measures are often compromised leading to financial loss, identify theft, etc.

For this assignment, you are to research a specific web application security threat that interests you (i.e. SQL Injection, XSS attacks, Denial-of-service attacks, etc.) and develop a web page to summarize your findings from your research.

### Page Content
Use the included `index.html` as your starting point. Your page should contain the following sections ...

#### Title & Heading
Give the page a title in the head section (`<title>` tag). This should be the name of your chosen security threat. Also, place a level-1 heading (`<h1>`) tag at the top of the page within the `<body>` tags. Repeat the title of your page here.

#### Overview
Give a brief summary in one paragraph describing your choosen topic. Start off this section with a level-2 heading `<h2>` with the content "Overview". Do this for each remaining section of the document ("Mode of Attack" and "Mitigation").

Find an image relating to your topic on Google, download it, and place in the folder named `img/`. Include this image somewhere in this area of the document. Use a *relative* URL for the `src` (relative to the page document). Also, create a hyperlink to the source of this image (URL of page this image was originally used in) and place after the image tag. This should be an *absolute* URL (full address of web page) and open up in a new tab/window (`target='_blank'`). Place appropriate text in the hyperlink.

> Make sure to download the image and store the file locally. It is bad etiquette to directly include images hosted on other sites as absolute links without permission.

#### Mode of Attack
Describe the basics of how a hacker would use this technique to compromise an application. Introduce this section with a paragraph or two and use an ordered list to describe the attack steps. Youd don't need to be overly technical here.

Find another image relating to this section (could be a generic image that makes you think of "attacking"), download it, and include it in this part of the document. Make sure to create a hyperlink to reference the source as before.

Include several links in this section as well(either links within the paragraphs you wrote, or an unordered list of links) to sites you used as a reference. Refer the reader here for more information.

#### Mitigation
Describe ways to prevent this threat. Write a paragraph or two and include either an ordered or unordered list (whichever is semantically more correct). Also, include another image here relevant to this section. Like the previous section, this is a general explanation and does need to be overly technical.

### HTML Validation
Use the [W3C HTML Validator](https://validator.w3.org/) to ensure your page is syntacitcally correct. You should do this often while developing your page, as there may be issues that are cleared up after you fix the mistakes.

This service is straight forward. You will need to either use the "File Upload" or "Direct Input" option. The URI option will not work as your site is not publicly accessible.

For full credit, your page must validate fully with no errors.

## Tips & Tricks
Resize your images to the appropriate dimensions with an image editing application of your choice before submitting your project. While you can use the `<img>` tag's attributes `width` and `height` to resize the image on the page, this does not actually change the size of the image downloaded by the user. Instead, use these attributes for fine tuning.

Don't think of this as a web page. Instead, think of this as an alternative to MS Word (or other word processing program) for writing a research paper. This is what HTML was originally intended for.

This page **will not look pretty**. But it's okay, because that's not what HTML is for. We will make things look nice once we get to *CSS*.

When needed, use `<br>` takes to go to the next line of the document. We won't need these as much with *CSS*.
   
## Submission
Push your final submission to GitHub and submit the Blackboard assignment with your repository URL. All feedback will be given through GitHub once the Blackboard assignment is submitted.