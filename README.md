# Inclusivity Insight: offering advice and support on diversity and inclusion in workplace and educational settings

![image](https://github.com/user-attachments/assets/7169be24-c725-4e77-bbde-438e43f59960)

## Purpose
A website for a business offering a consultancy service on diversity and inclusion policies and their implementation in workplace and educational settings.

To support the project objectives, the website will provide definitions of diversity and includsion, provide tips on how to promote and diversity and inclusion policy, as well as relevant external links.

### User Stories (excerpts copied directly from Code Institute's LMS resources:

"External User’s Goal: The user wants to gain a basic understanding of diversity and inclusion in the workplace or educational environment. They seek straightforward information and tips presented in a clear, organised format."

"Site Owner’s Goal: The site owner aims to create a visually appealing, easy-to-navigate webpage that introduces diversity and inclusion concepts and offers basic guidance on how to implement these practices. The focus is on clear communication through effective use of HTML and CSS, utilising Bootstrap for layout and design."

## Design Decisions
### Wireframes
Given the limited scope of the project, I opted not to use wireframes for design planning purposes.  In hindsight, whilst I do not think this adversely impacted the project, it would have been useful practice for future site development; I feel the use of wireframes would be essential for more complex websites.
### Colours
I wanted to choose a colour scheme that would be professional, clear and relatively vibrant, as I wanted the webpage to encourage the user to trust it as a source of information, but also to be engaged by it.
I decided that a light blue with a white background, broken up with carefully selected images, would offer a clean and captivating palette for the user.  Initally, I styled the website using #209CEE as a background colour with white text (#FFFFFF) overlaying it for the navigation bar and anchor links, but upon testing this for WCAG compliance, I found that this colour combination failed: 

![image](https://github.com/user-attachments/assets/c00f30c8-1d23-4575-96e2-053c2faa259b)

As I did not test this until a late stage in the development process, I opted to use #2E2EFF, as it was WCAG compliant (please see the image below); unfortunately it is not as aesthetically pleasing, so in future I will carry out WCAG testing at a much earlier stage.

![image](https://github.com/user-attachments/assets/161ec277-b118-46bb-94ab-32cd12bf8d6c)


### Font
I used to similar fonts for this project, which I sourced from Google Fonts:
#### Roboto Condensed (for the title):
![image](https://github.com/user-attachments/assets/193ebed7-21b2-453b-88ea-44c9a6cfc26d)
#### Roboto Flex (for the body):
![image](https://github.com/user-attachments/assets/fbf5cefe-4fbf-4c67-ab1a-067214c7b855)


### Images
All images were sourced from https://www.pexels.com/ 
### Icons
All icons were sourced from https://fontawesome.com/
### Favicon
My favicon was designed using https://favicon.io/
## AI
I used Microsoft CoPilot to generate AI text, as well as to assist with and generate some CSS and JavaScript code.  I found that this was particularly helpful in helping me to fix bugs, as well as with areas of coding that I am less confident with, such as using CSS flexbox and the box method to change the position of elements on the page.

## Features Implementation
### Navigation
The main responsive feature of the page is the navigation bar (please see the image below), which links to other points on the same page.
![image](https://github.com/user-attachments/assets/2e79ecdd-13c4-4e49-8529-92bb09ab7e98)

This is responsive to screen size, so will change to a dropdown menu for smaller screens, as is shown in the image below:
![image](https://github.com/user-attachments/assets/15fa4436-5cef-4f56-98d7-065353fab252)

### Core Features
The webpage aims to meet the core aims of defining diversity and inclusion, as well as providing information on how they can be implemented; these are demonstrated in the screenshots below:

Definitions of diversity and inclusion:

![image](https://github.com/user-attachments/assets/83c68276-f6ca-4ac3-a431-bce38f8e5955)

Information on implementation:

![image](https://github.com/user-attachments/assets/6a707f06-176a-45a1-8171-44dd059eebc1)



### Advanced Features

In addition to the key information, external links are provided to enable users to navigate to other websites for further information:
![image](https://github.com/user-attachments/assets/1c5402ce-7266-4e5c-b9c2-485d899783fa)

### Optional Features

Vibrant images are included to break up the text and engage the user:


![image](https://github.com/user-attachments/assets/31baf447-3748-43ff-b801-34f2afc1106d)

## Testing and Validation

### Colour Testing
As mentioned above, I tested the colour scheme for WCAG compliance using https://webaim.org/resources/contrastchecker/

### Performance, Accessibility, Best Practices, and SEO
These were tested using https://pagespeed.web.dev/?hl=en-GB:

Mobile page results:
![image](https://github.com/user-attachments/assets/6d9fadbe-5dda-45f9-a764-caa07a91660d)

Desktop page results:
![image](https://github.com/user-attachments/assets/630a45e8-e81b-475d-b164-990126f3bcbf)


### HTML Validation
HTML validation was completed using https://validator.w3.org/:
![image](https://github.com/user-attachments/assets/25f865e2-904a-41e4-bb06-28d63f043576)


### CSS Validation
CSS validation was completed using https://jigsaw.w3.org/css-validator/:
![image](https://github.com/user-attachments/assets/81577fe6-9885-42d5-adc6-eae89b3fe2cc)


## Reflection of Development
### Successes
Overall, I am satisfied with the responsive of my website; the basic features largely work in the manner I want them to.

### Challenges
The project has highlighted to me that I need to gain much more familiarity with CSS, particularly with regard to the box model and flex box, as I was highly dependent on Bootstrap to assist me.  I also realise that I should have spent far more time thinking about the design of the website and considering accessibility at a much earlier stage.

### Summary
The website appears to meet the basic criteria and I greatly enjoyed this exercise, but I am highly aware that I need to make a lot more progress on design and on user experience.

## Code Attribution
I used code from the following sources:

Code Institute LMS lessons
Bootstrap
Microsoft CoPilot
Fontawesome.com
favicon.io
Google Fonts
