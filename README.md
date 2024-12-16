# Photo Guides

**Photo Guides** is a site that aims to provide explanations, advice and guidance on camera bodies, lenses and settings. So beginner and amateur photographers have a good starting point for equipment required and how to use the equipment. Therefore, this site will be targeted at users who are beginners or amateurs in photography. It will provide in simple language different camera bodies, lenses and how to use the equipment. To help inspire the users we will also provide an area that explains the history of photography and some famous photographers to draw inspiration from. **Photo Guides** therefore will be useful for beginner and amateur photographers by helping them understand the equipment, how to use it and providing inspiration to guide them and their style.

The decision to make this website is due to the user stories found [here](userstory.md).

![Responsice Mockup](https://github.com/lucyrush/readme-template/blob/master/media/love_running_mockup.png)

## Features 

Below are the features for the website and at the end is listed any features that weren't able to be implemented but would be with more time.

### Existing Features

- __Navigation Bar__

  - Featured on all the pages, the full responsive navigation bar includes links to all pages and contact form in the footer page and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.
  - The navbar is fully responsive across all sizes of devices and become a drop down on smaller screens to make navigation easier on smaller screens.

![Nav Bar](https://github.com/lucyrush/readme-template/blob/master/media/love_running_nav.png)

- __Home__

  - The landing includes a photograph with text overlay to allow the user to see exactly which location this site would be applicable to. 
  - This section introduces the user to Love Running with an eye catching animation to grab their attention

![Landing Page](https://github.com/lucyrush/readme-template/blob/master/media/love_running_landing.png)

- __Overview of Website__

  - The club ethos section will allow the user to see the benefits of joining the Love Running meetups, as well as the benefits of running overall. 
  - This user will see the value of signing up for the Love Running meetups. This should encourage the user to consider running as their form of exercise. 

![Club Ethos](https://github.com/lucyrush/readme-template/blob/master/media/love_running_ethos.png)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for Love Running. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media

![Footer](https://github.com/lucyrush/readme-template/blob/master/media/love_running_footer.png)

- __Success Page__

  - The gallery will provide the user with supporting images to see what the meet ups look like. 
  - This section is valuable to the user as they will be able to easily identify the types of events the organisation puts together. 

![Gallery](https://github.com/lucyrush/readme-template/blob/master/media/love_running_gallery.png)

- __Equipment Advice__

  - The gallery will provide the user with supporting images to see what the meet ups look like. 
  - This section is valuable to the user as they will be able to easily identify the types of events the organisation puts together. 

![Gallery](https://github.com/lucyrush/readme-template/blob/master/media/love_running_gallery.png)

- __Settings Tutorial__

  - The gallery will provide the user with supporting images to see what the meet ups look like. 
  - This section is valuable to the user as they will be able to easily identify the types of events the organisation puts together. 

![Gallery](https://github.com/lucyrush/readme-template/blob/master/media/love_running_gallery.png)

- __Photo History__

  - The gallery will provide the user with supporting images to see what the meet ups look like. 
  - This section is valuable to the user as they will be able to easily identify the types of events the organisation puts together. 

![Gallery](https://github.com/lucyrush/readme-template/blob/master/media/love_running_gallery.png)

### Features Left to Implement

- Another feature idea

## Testing 

- Contact Form in footer wasn't submitting nor saying why the form wasn't submitting, upon inspection the input type was set to "button", so this was changed to input type "submit"
- Contact form button was decreasing in size when hovered over and pulling up the social media links at the bottom, therefore the border was made solid so there was no change in size, this meant the socials in the footer didn't move up
- Contact button in navbar always took you back to homepage due to the href was linked to index.html#contact therefore the index.html was removed and just the #contact was left to enable the contact button to take you to the contact form in the footer of the page, enabling a smoother user experience
- The cards on the homepage were the different heights and widths across different screen sizes, therefore media queries were added to ensure they all matched across the different screen sizes
- The gaps between the cards on the homepage were too big on the bigger screen sizes, therefore media queries were added to ensure they were responsive across all screen sizes


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)
- Lighthouse Score
  - Below you can see my lighthouse score
  ![Lighthouse](Lighthouse screenshot)

### Unfixed Bugs

- Sharp corners from CSS to be added to all buttons across the site to add uniformity

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the "Settings" tab 
  - Under "Code and automation" selected "Pages"
  - Ensure Deploy from branch is selected
  - In the "Branch" section "main" was selected as the branch then "/root" was selected
  - Click "save" and the GitHub Pages was deployed

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 

## Credits 

Below are my credits for where I got inspiration for some of the code, where the content came from and where media is from.

## Code

- There has been use of Bootstrap library for CSS and JS across all pages and sections
- Sharp-corners code in custom CSS is from Portfolio Website Mei
- Love Running inspired the code for the footer being at the bottom of the page and the social media icons in the footer*
- Boardwalk games inspired the code for the success page*

*Not all the code for these items is an exact copy, some edits were made 

### Content 

- The text for in each header was first generated by chatgpt and then edited
- All icons were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used in each header and on the cards on the homepage are from [Unsplash](https://unsplash.com), the exact photographer is credited under the image in the header.
- T