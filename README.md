# Luper-GWU-Module-1-Challenge
This repo will be used to complete the Module 1 Challenge assignment for GWU classwork.

The requirements to complete this Challenge are as follows:

User Story:

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

Acceptance Criteria

GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

I will be (attempting) to submit a functioning URL for the refactored index.html file, which if I understood correctly, is based on and edited from the provided starter code.

From what I can see, the semantic HTML elements are present and follow a logical structure (as far as I currently understand).

When I refactored the image elements, I checked the syntax by checking the relevant W3 resource (https://www.w3schools.com/html/html_images.asp). I referred to the relevant Harvard document
in order to look at examples of appropriate length of alt text for an image element (https://accessibility.huit.harvard.edu/describe-content-images).

The heading attributes seem to currently match what is sugested in the mockup for the assignment.

I believe the title element has a concise, descriptive title.

-----
DISCLAIMER: I had been working on this assignment and I think I must have started committing to two separate HTML files for the project because something about the following file was breaking the way it would display in the browser. I'm including the file I deleted to show what edits I have made to that particular file and hopefully receive feedback as to why it may have broken.

The following is my deleted HTML file:

<!DOCTYPE html>
<html lang="en-us">

<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>Horiseon home page</title>
</head>

<body>
    <div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
    </div>
    <div class="hero"></div>
    <div class="content">
        <div class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" alt="SEO and its vital elements: backlinks, content, headings, link building, mobile compatibility, and social media" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </div>
        <div id="online-reputation-management" class="online-reputation-management">
            <img src="./assets/images/online-reputation-management.jpg" alt="Chart on laptop that shows increasing reputation" class="float-right" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </div>
        <div id="social-media-marketing" class="social-media-marketing">
            <img src="./assets/images/social-media-marketing.jpg" alt="Desk that is covered in social media-related icons" class="float-left" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </div>
    </div>
    <div class="benefits">
        <div class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" alt="Symbol with gear going into a funnel and outputting coin" />
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </div>
        <div class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" alt="Symbol of man in tie with lightbulb for a head and waves radiating out" />
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </div>
        <div class="benefit-cost">
            <h3>Cost Management</h3>
            <img src="./assets/images/cost-management.png" alt="Symbol of gear with three overlapping coins overlaid in front of gear"/>
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </div>
    </div>
    <div class="footer">
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>
            &copy; 2023 Horiseon Social Solution Services, Inc.
        </p>
    </div>
</body>

</html>
