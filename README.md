# Clare's Portfolio Website
## The Webpage link  
https://clareo-portfolio-project.netlify.app/ 

## GitHub Repository link  
https://github.com/clareahnem/portfolio 

## Purpose  
This portfolio page was created to showcase my coding skills with a particular focus on HTML and CSS/SCSS. 
The website was created with a purpose to showcase my current web development skill to the employers and other stakeholders of the tech industry, as well as the teachers and student cohort at Coder Academy. In order to challenge my knowledge and capabilities on HTML and CSS/SCSS, this page was created without the use of scripting languages such as JavaScript or Ruby.

## Theme  
The main theme of this portfolio website is "simple, clean and fresh". While individualiity and uniqueness is a great strength in showcasing your personality, I aimed to make the content and the features of the webpage more prominent than its visual appearance for this project. Hence, I aimed to use minimal range of colors and font styles to keep the design aspect relatively simple. 

For the colors, I decided to use white and light blue prodominantly. According to color theories, white is often associated with innocence and symbolises new beginnings, while light blue is associated with trustworthiness and reliability. As an individual who recently started coding, these two colors felt well suited for this project. To keep with my color theme, I chose to use an image of the sky with white clouds for the main background. Skies and clouds are often symbols of open spaces, imagination, dreams and inspiration, which further enhances the main theme of this webpage. 

## Features  
Each page on this website features a navigation bar, main content and a footer, which were formatted using a `Grid` display. The navigation bar is fixed on top of the screen (i.e. will not scroll out of the viewport) and contains links to different HTML pages with logos for simple yet user-friendly appearance. Text-shadow features were incorporated to give each link a cloud-like appearance to keep with the theme, as well as keyframes that make the logo "glow" when they are hovered over. 

The footer is positioned so that it will always appear at the bottom of the page without lifting off from the bottom of the viewport, and features links to my LinkedIn, GutHub and Codepen profiles. These links are each given the `target="_blank"` attribute so that when an audience click on the link, the profile will open on a new tab. 

As for the main section of the page, each of the 5 HTML pages contain the following features; 
### 1. Home page
this page includes a brief introduction about myself and a description on how to navigate the page. The themes and main components of this page is used consistently throughout this portfolio, including the keyframes and font styling for headings and text colors of paragraphs. In order to make this page visually appealing in all media devices, `flexbox` display was used for components in `<main>` tags to give a responsive design. 
### 2. About Me page
The main purpose of this page is to let the audience know a little bit about myself by describing my personality, study history and interests. It includes an insight on how I became interested in Coding and what led me to study at Coder Academy. The PDF of my resume is also linked on this site to showcase my work and study history outside of coding experiences. I have incorporated keyframes on the skill section of this page, where if you hover on the logos of each skill such as the HTML 5 logo, it will be enlarged, spin 360 degrees and shrink back to its original size - a fun little feature for visual entertainment. 

### 3. Project page
This is a simple page that showcases my past web development projects that I have worked on including those that I have done for Coder Academy classes and those I have worked on outside of this school. It gives the audience an idea of what I have been doing throughout my coding journey. At this current point in time this portfolio itself is the most complex piece of webpage I have created, hence viewers will be able to see how my skills have improved through viewing the projects that are listed on this page. However when there are more projects that I would consider more valuable for showcasing to the target audience, they would most likely replace the ones that are being listed at the moment. As for the visual styling, this page changes its visual appearance dramatically when screen size is larger (i.e. desktop size), where each project section appears small until you hover over. when hovered over, the project of interest will expand its size so viewers are able to see the project image more clearly. In order to make this transition smoother, keyframes were incorporated for when they are hovered over, as well as when they are unhovered. 

### 4. Blog Posts
This page features 5 separate blog posts about my personal travel journeys. However the highlight of this page is not the article content, but is on how I styled the blog posts using css/scss. The 5 posts are all separated by `<div>` tags and displayed in flexboxes, and is the page where keyframes and media queries are used most comprehensively to showcase my understanding of CSS features and responsive design.

In any screen sizes, each blog post content is hidden in `<detail>` tag where viewers must expand the tag in order to read the content. This allows for the page to be simplified and hence easier to navigate through. However the downside of the `<detail>` tag is that the contents will only fold unless you click on the `<summary>` located at the top of the `<detail>` content. Since the blog article contents are relatively long, when articles are viewed on a mobile screen the viewers must navigate themselves back to the top of the article in order to fold the content back. In order to simplify this process, I have added a button at the end of each article content that links back to its post heading, so that viewers can easily fold the blog article content back for a simplified view of the page. I have styled this button to be only visible on mobile-sized screens, as larger screens are already easy enough to navigate back to the post heading without the button.

### 5. Contact Page
This page includes a simple form for page viewers to contact myself directly. The purpose of this is to acquire feedback, job and experience offers and general comments from the readers. Those who wishes to write back must submit their name, email and some kind of text in the textfield, as they have been given the `required` attribute in their respective `<input>` tags. Each response will be sent to my coder academy email, so that I can respond back if necessary. Any feedback will be read and referenced for my self improvement in the future. 



# Tech Stack
- HTML 5
- CSS 3
- Sass
- Scss
- GitHub
    - For remote repository
- Formspree.io
    - For Email form on Contact page
- Google Fonts (fonts.google.com)
    - for letter fonts
- Unsplash.com
    - for background image
- w3schools.com
    - media query template
- Fontawesome.com
    - for icons
- draw.io
    - For visual sitemap
- xml-sitemaps.com
    - For sitemap.xml file
- Netlify.com
    - For deployment
- Trello.com
    - organisation and planning
- Balsamiq
    - for wireframes



# Sitemap  

![sitemap diagram of Clare's Portfolio](./images/Screenshots/Portfolio_sitemap.jpg)

# Progress rundown with screenshots
### Planning

I began working on my project by firstly creating a Trello Board for things that I needed to do. I created large-scale cards first with color coded tags. Tags would indicate whether this task is a preparation, coding, html, styling or documenting task. At the start of each day that I worked on my project I would create smaller tasks based on the large-scale tasks I had. This enabled me to organise my tasks into order that I would prioritise for the day, and overall helped me avoid confusion.
![Making Trello Board to plan](./images/Screenshots/06-04-MakingTrello.jpg)

In each Trello Card, I added brief description and specific components that are required in the completion of this task.
![Making Trello Cards](./images/Screenshots/06-04-TrelloCard.jpg)

### Planning Process
The first task I worked on was making wireframes. It took a little bit of time to get used to the functions of balsamiq, however in the end I had a lot of fun putting my ideas together. I then began gathering inspirations for fonts, color schemes, backgrounds...etc to settle on the aesthetics of my webpage. I used Google fonts to acquire my fonts and got my background image from Unsplash.com. Deciding on the theme and main color scheme earlier on helped me save a lot of time when I styled my pages later on.

### HTML Home Page
After creating wireframes, I began creating HTML structures of each page. Components that will be used for all HTML Pages were created first, including the navigation bar, footers and a title for each page. I created a GitHub remote repository to push my commits as I made progress. 
![Making HTML structures](./images/Screenshots/12-4-SS.jpg)

After creating basic HTML structures, these are what the pages looked like.
![after completing basic HTML of Home page (Mobile)](./images/Screenshots/12-04-SSHome2.jpg)

![after completing basic HTML of Home page (Tablet)](./images/Screenshots/12-04-SSHome3.jpg)

![after completing basic HTML of Home page (Desktop)](./images/Screenshots/12-4-SSHome.jpg)

### More HTML 

After creating HTML template for Home page, I added the main contents of about me page, project page and blogs page. This process was relatively easy as the template structure like navigation and footers were being reused, and there were no styling involved at this point.

![after completing basic HTML of About page (Tablet)](./images/Screenshots/12-04-SSAbout.jpg)

![after completing basic HTML of Project page (Tablet)](./images/Screenshots/12-04-SSProject.jpg)

![after completing basic HTML of Blog page (Mobile)](./images/Screenshots/12-04-SSBlogs.jpg)

#### Individual blog page that ceased to exist

Towards the start of the creating process, I had initially planned to create separate HTML pages for inividual blog posts. Each page would contain a link to "previous" and "next" most recent blog posts as well as a button to return to the blogs page where all blog contents were summarised onto one page. This structure was later discarded when I decided on using the `<display>` tag to "embed" blog content within the main Blog HTML page. 

![after completing basic HTML of blog post (Tablet)](./images/Screenshots/12-04-SSBlog2.jpg)

### Styling Main components with SCSS/CSS  
The next day, I created css and scss pages to style my website. I began styling from the main components i.e. navigation, footers, background, and imported the fonts I would use. I also added text-alignments and basic positioning to some elements so that I can decide on the font sizes and weights. These basic stylings were added to style.scss, which is my main scss file as they were to be used for styling multiple HTML pages.

![after completing basic CSS of Home page (Mobile)](./images/Screenshots/13-04-SSHome.jpg)

![after completing basic CSS of Home page (Tablet)](./images/Screenshots/13-04-SSHome3.jpg)

![after completing basic CSS of Home page (Desktop)](./images/Screenshots/13-04-SSHome2.jpg)

### Styling with partials
Inside a CSS directory, I created a partials directory where I stored saparate scss files for variables as well as separate scss files for each HTML pages. variables.scss contains all of the variables, mixins and keyframes to be used throughout different pages.

Each of the scss files in the partials directory are imported to the style.scss file in its parent directory, and this is linked to the css file imported in all HTML pages. 

After doing so I worked on styling the rest of HTML pages, adding extra html tags and classes along the way to make the pages more accessible, responsive and visually appealing.

##### About me page
![after completing basic CSS of About Me page (Mobile)](./images/Screenshots/14-04-SSAbout1.jpg)

![after completing basic CSS of About Me page (Tablet)](./images/Screenshots/14-04-SSAbout2.png)

![after completing basic CSS of About Me page (Desktop)](./images/Screenshots/14-04-SSAbout3.jpg)

### Changes to navigation and footer
During the styling process I decided to change the components in Navigation and Footers. I initially intended to have no individual page for Contacts, hence had an `<a emailto:(....)>` link in the footer. However after some consideration I decided to create a contact me HTML link hence moved this component to the navigation bar and removed it from the footer section. Since the `emailto:` option reveals your email address, it is safer to incorporate a `<form>` with email-style submission from the developer's perspective. It is also much more visually appealing to create a contact form this way.

### Adding pseudo classes
In order to make the webpage more interactive, I added several `:hover` pseudo classes to my web pages. These were mainly assigned to Desktop views as mobile and tablet screen audiences will not be able to "hover" over elements without a mouse console. Since my focus was to make the end result of hovers visually appealing, I decided to complete the pseudo classes before adding keyframes to it. 

##### Blogs page  

![after completing basic CSS of Blogs page (Desktop)](./images/Screenshots/14-04-SSBlogs1.jpg)

##### Projects Page  

![after completing basic CSS of projects page (Mobile)](./images/Screenshots/14-04-SSProjects1.jpg)

![after completing basic CSS of projects page (Tablet)](./images/Screenshots/14-04-SSProjects2.jpg)

![after completing basic CSS of projects page (Desktop)](./images/Screenshots/14-04-SSPeojects3.jpg)  


For the desktop view of the project page, I was not happy with how the smaller boxes (i.e. project `<div>` that was not hovered) had different heights. I made it my task to fix this later on.

##### Contacts Page  

![after completing basic CSS of contacts page (Desktop)](./images/Screenshots/16-04-SSContact.jpg)

###  Adding Keyframes
After I was satisfied with most of the styling of my pages, I went on to add keyframes to multiple elements throughout the website. For example, I created a keyframe for icons in the navigation bar to "glow" when hovered over, and made the `:hover` pseudo transitions smoother by incorporating the changes into keyframe animations. This was more time-consuming than I initially expected, since the Cascading trait of CSS became very important in how the keyframe displays its effects. I was also not considering the fact that I had to apply animation for elements to transition back to its original state after unhovering, which added extra time to work on one element's animation.  

![creating keyframes in variable.scss](./images/Screenshots/15-04-SSKeyframes.jpg)

### Accessibility features
Along with adding visual styling on elements to make the page easier to navigate, I also added attributes in some HTML tags to increase accessibility for those using screen readers. For example, in the `<footer>` link icons, I added a `title` attribute so that when the icon is in focus it will give you a guide on where the link will jump to.  

![adding accessibility features to footer](./images/Screenshots/16-04-SSFooter.jpg)

### Changing footer design
In the final refinement process I decided to change the styling of footers for Large Viewports. Since the previous design took 10rem height for footers with small logos, it was wasting screen space. To change this, I added media queries for footers so that the height of the footers are 5rem instead of 10rem, and added flexbox to contents so that they align horizontally instead of being in a `display: block;` like it was. The design overall look more simplified, as there is now less attention being led towards the footer and more towards the `<main>` section of the page.

![making changes to footer style in desktop view](./images/Screenshots/19-04-SSnewFooter.jpg)

### Making changes after Presentation Day
After seeing the presentations by class cohort, I decided to make a few small changes to my website. This included adding `<input type="text">` in the contact form to add sender's name, so that I know who has sent me a message. Furthermore, I changed the title and the text below it in the contact page. The new text had a more confident approach, leaving a more professional impression of myself for potential business partners.

![adding input section for your name in contact form](./images/Screenshots/21-04SScontact.jpg)

I also added a captcha feature on my email form through formspree website, in order to prevent spam emails from being sent. 
![view of formspree captcha users will see after email submission](./images/Screenshots/21-04-SSformspree.jpg)

Another thing I changed was the content of my resume. I initially had written in my contact details including my phone number, but after hearing multiple people in class talk about privacy matters, I was reminded to remove them from my resume. 
