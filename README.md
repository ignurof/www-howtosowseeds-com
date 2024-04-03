# www-howtosowseeds-com

howtosowseeds.com is an informational guide site to help people around the world with general information and guides on how to sow different kinds of seeds.
The intention is to bring more people into the gardening hobby and the main target demographic of the site is beginners to gardening and anything related to seed sowing. 
howtosowseeds.com will be a good place of reference for gardeners to know just when and how to sow their seeds even when they're not beginners anymore.

![Responsiveness](https://www.ignurof.com/responsive.png)

## Features 
The site features are very simple in nature since the focus of the site is on the informational guide content in both text, image and video format.

### Existing Features

Site Layout

Header
![Header](https://www.ignurof.com/features/header.png)

Content
![Content](https://www.ignurof.com/features/content.png)

Footer
![Footer](https://www.ignurof.com/features/footer.png)


Home Page
![Home Page](https://www.ignurof.com/features/home_page.png)

Guide Page
![Guide Page](https://www.ignurof.com/features/guide_page.png)

About Page
![About Page](https://www.ignurof.com/features/about_page.png)

Contact Page
![Contact Page](https://www.ignurof.com/features/contact_page.png)

### Features Left to Implement

- More than one guide
- Video content for guides

## User Experience

Great deal of thinking went into why the website should be structured the way it is and look the way it does.
I wanted it to convey information in a quick and easy manner to the user so that everything is clear and structured in a very readable way.
Taking inspiration from established web practices and how to layout a website and structure the content to best pull in the user and help them navigate the site through web familiarity.

### Wireframes

![Wireframe for Mobile Home page](https://www.ignurof.com/wireframes/howtosowseeds/wireframe_mobile_home.png)
![Wireframe for Mobile Guide page](https://www.ignurof.com/wireframes/howtosowseeds/wireframe_mobile_guide.png)
![Wireframe for Mobile Contact page](https://www.ignurof.com/wireframes/howtosowseeds/wireframe_mobile_contact.png)
![Wireframe for Mobile About page](https://www.ignurof.com/wireframes/howtosowseeds/wireframe_mobile_about.png)

![Wireframe for Laptop Home page](https://www.ignurof.com/wireframes/howtosowseeds/wireframe_laptop_home.png)
![Wireframe for Laptop Guide page](https://www.ignurof.com/wireframes/howtosowseeds/wireframe_laptop_guide.png)
![Wireframe for Laptop Contact page](https://www.ignurof.com/wireframes/howtosowseeds/wireframe_laptop_contact.png)
![Wireframe for Laptop About page](https://www.ignurof.com/wireframes/howtosowseeds/wireframe_laptop_about.png)

### Interaction Experience

I made sure that all interactables on the website had a feel to them in the form of special styling rules being applies while the user is either hovering over or pressing links or important call-to-action buttons.
To keep things in line with that users expect from a website, the logo is always a link that leads back to the home page, but this one is unaffected by the interaction design experience as that seems to be the standard from the research.

## Testing 

Manual testing with Firefox through development process.
During the whole development process as can be found through the git commit history, I have been painstakingly manually testing every single change and completed set of features by hand through the means of navigating around the site and it's features as a normal user would, testing out the responsiveness and how the content and/or features look by making use of the Firefox dev tools to change the viewport size.
Every button has been pressed and investigated more than hundres of times through the process, the same with any link, paragraph or image content.
The website has also been combed through with the use of a android phone to make sure that the mobile-first design has always been grounded in the real world!
After completed development cycle I have also gone through the whole site one last time to make sure I did not miss anything, and through the whole development process I have taken notes and crossed of those notes whenever I noticed there was a task that needed to be taken care of, for example seeing something not being perfectly responsive during testing I would note that down, keep testing and then return to address whatever the issue was when development was resumed.

After all was said and done with above testing and I noted that everything looked right, I ran the site through a HTML validator and CSS validator to go the extra mile and make sure I covered all my bases. The CSS was top notch but I had 4 unfixed bugs to deal with in the HTML, but nothing that affects the functionality, look or features or the website so they could be postponed from the MVP.

To cover all my bases since I have tested on Firefox and also an android phone which user Google Chrome, I wanted to make sure I also test using and hopefully not breaking the site while navigating around with Google Chrome on my laptop as one final test.
Everything looked like it did previously except in a different browser which means the site definitely passes the testing stage.

### Validator Testing 

HTML was tested through the w3.org validator found here: https://validator.w3.org

![HTML Validation](https://www.ignurof.com/validation/howtosowseeds/html_validation.png)

CSS was tested through the jigsaw.w3.org css specific validator found here: https://jigsaw.w3.org/css-validator/

![CSS Validation](https://www.ignurof.com/validation/howtosowseeds/css_validation.png)

### Unfixed Bugs

The four unfixed bugs currently deployed in production are the ones shown above that failed the HTML validation testing.
- Element div not allowed as child of element label in this context.
- The element button must not appear as a descendant of the a element.
- The element button must not appear as a descendant of the a element.
- Stray start tag script.

## Deployment

GitHub pages were used to deploy this website and this step by step guide will tell you how to deploy it yourself after you have forked the project.

- Click the "Settings" tab. 
- Go to "Pages" under the "Code and Automation" section. 
- Make sure Source is set to "Deploy from a branch".
- Under the "Branch" heading, click the dropdown and select "prod".
- Click "Save" and the site will be deployed to GitHub Pages.
- Now you can visit the site located at: https://your-username-here.github.io/repository-name-here

## Credits 

- The readme is from the template made by Code Institute (https://github.com/Code-Institute-Solutions/readme-template)
- The greatest documentation Mozilla Developer Docs: https://developer.mozilla.org/en-US/
- Invaluable syntax helper w3schools: https://www.w3schools.com/
- Repo Banner image with the help of: https://ui.dev/amiresponsive

### Content 

- Hamburger menu input checkbox functionality from Code Institute's Love Running project.
- Colorscheme heavily inspired by: https://www.fabmood.com/green-and-orange-papaya-color-inspiration-palette/

### Media

- Social media icons are from FontAwesome: https://fontawesome.com/
- All photos used are from Pexels: https://www.pexels.com/

###### Created and Maintained by (https://github.com/ignurof)
