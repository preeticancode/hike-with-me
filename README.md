


## Welcome to Hike with Me! 

## **Site Overview**
This page is dedicated to community of hiking enthusiasts from all across Ireland. Our mission is to bring together people who share a passion for hiking, whether you're an experienced trekker or just starting out. Join us to explore Ireland's stunning trails, discover new places, and make lasting friendships.

***
***(By Preeti Singh)***

## [Link to Live Website](https://preeticancode.github.io/hike-with-me/)

![Am I responsive screenshot](docs/screenshots/am-i-responsive.jpg)

## Table of contents:
1. [**Site Overview**](#site-overview)
1. [**Planning stage**](#planning-stage)
    * [***Target Audiences***](#target-audiences)
    * [***User Stories***](#user-stories)
    * [***Site Aims***](#site-aims)
    * [***Wireframes***](#wireframes)
    * [***Color Scheme***](#color-scheme)
1. [**Current Features Common to all pages**](#current-features-common-to-all-pages)
    * [***Header Element:***](#header-element)
        * [*Title*](#title)
        * [*Navigation Bar*](#navigation-bar)
    * [**Hero Images:**](#hero-images)
      * [***About Page***:](#about-page)
          * [*Hero-Image*](#hero-image)
          * [*Quote*](#quote)
      * [***Teachings page***:](#teachings-page)
          * [*Hero-Image*](#hero-image-1)
          * [*Quote*](#quote-1)
      * [***Community page:***](#community-page)
          * [*Hero-Image*](#hero-image-2)
          * [*Quote*](#quote-2)
      * [***Contact and Form-Feedback pages:***](#contact-and-form-feedback-pages)
          * [*Hero-Image*](#hero-image-3)
          * [*Quote*](#quote-3)
    * [**Anchor Tags Within all Pages Main Content**](#anchor-tags-within-all-pages-main-content)
    * [**Footer**](#footer)
    * [**Typography**](#typography)
1. [**Individual Page Content features**](#individual-page-content-features)
    * [**About Page Content**](#about-page-content)
    * [**Teachings Page Content**](#teachings-page-content)
    * [**Community Page Content**](#community-page-content)
    * [**Contact Page Content**](#contact-page-content)
    * [**Form Feedback Page Content**](#form-feedback-page-content)
1. [**Future-Enhancements**](#future-enhancements)
1. [**Testing Phase**](#testing-phase)
1. [**Deployment**](#deployment)
1. [**Credits**](#credits)
    * [**Honorable mentions**](#honorable-mentions)
    * [**General reference**](#general-reference)
    * [**Content**](#content)
    * [**Media**](#media)

## **Planning stage**
### **Target Audiences:**
1. *Outdoor Enthusiasts*: People who love nature and outdoor activities.
2. *Fitness Enthusiasts*: Individuals looking for physical exercise through hiking.
3. *Adventure Seekers*: Those who enjoy exploring new trails and challenging terrains.
4. *Families*: Parents and children looking for family-friendly hiking activities.
5. *Environmentalists*: People interested in conservation and appreciating natural beauty.
6. *Social Seekers*: Individuals looking to make friends and connect with like-minded people.
7. *Beginners*: New hikers seeking guidance, tips, and beginner-friendly trails.
8. *Experienced Hikers*: Seasoned hikers looking for advanced trails and sharing their experiences.


### **User Stories:**
* User who are Nature Enthusiast / Hiker.
* Discover new hiking trails, connect with other hikers, share each-other experiences, and access hiking resources.
* User can enhance my hiking adventures, gain valuable insights, and contribute to the hiking community.

### **Site Aims:**
1. *Foster Community Engagement*: Create a vibrant and interactive platform where hikers of all levels can connect, share experiences, and support each other.

2. *Provide Comprehensive Trail Information*: Offer detailed and up-to-date information on hiking trails, including maps, difficulty ratings, directions, and user reviews, to help members plan their hikes effectively.

3. *Promote Safety and Preparedness*: Educate members on hiking safety, emergency procedures, and best practices to ensure safe and enjoyable hiking experiences.

4. *Encourage Outdoor Activity*: Inspire people to explore the outdoors and lead a healthy lifestyle by participating in hikes and outdoor events.

5. *Support Skill Development*: Provide resources, guides, and tips to help hikers improve their skills and knowledge, catering to beginners and experienced hikers alike.

6. *Facilitate Event Organization*: Streamline the process of organizing and participating in group hikes and community events through an easy-to-use event calendar and RSVP system.

7. *Enhance Environmental Awareness*: Promote responsible hiking practices and environmental stewardship, encouraging members to respect and preserve natural habitats.

8. *Enable Photo and Experience Sharing*: Allow members to upload and share photos, videos, and stories from their hikes, fostering a sense of community and shared adventure.

9. *Offer Personalized Experiences*: Allow members to create profiles, track their hiking progress, and receive personalized recommendations based on their preferences and activity.

10. *Provide Support and Feedback Channels*: Ensure members can easily contact community organizers for support, ask questions, and provide feedback to continuously improve the website and community experience.

### **Wireframes:**
To organize my thoughts and prevent scope creep, I created wireframes for this project. Below are links to each of the mobile and desktop versions of the four intended pages. 

* Mobile Wireframes:
    * [Homepage (About)](docs/wireframes/index-mobile.png)
    * [Gallery page](docs/wireframes/gallery-mobile.png)
    * [Sign Up page](docs/wireframes/signup-mobile.png)
    * [About Us page](docs/wireframes/aboutus-mobile.png)

* Desktop wireframes:
    * [Homepage (About)](docs/wireframes/index-desktop.png)
    * [Gallery page](docs/wireframes/gallery-desktop.png)
    * [Sign Up page](docs/wireframes/signup-desktop.png)
    * [About Us page](docs/wireframes/aboutus-desktop.png)
  There was some deviation from the original wireframes to improve the User Experience (UX).

### **Color Scheme:**
When deciding the color scheme, I wanted to go with something that gave an elegant appearance. For this reason, I selected a range of blue and gold's and used the following color grid created on [https://contrast-grid.eightshapes.com/](https://contrast-grid.eightshapes.com/?version=1.1.0&background-colors=&foreground-colors=%230000001A%0D%0A%234c1a11%0D%0A%23C1CDBF%0D%0A%234a1111%0D%0A%23fafafa%0D%0A%23752323%0D%0A%233a3a3a%0D%0A%23f16c6b%0D%0A%0D%0A%0D%0A&es-color-form__tile-size=compact&es-color-form__show-contrast=aaa&es-color-form__show-contrast=aa&es-color-form__show-contrast=aa18&es-color-form__show-contrast=dnp) to check the contrast scores. Using this grid allowed me to ensure all text remained visible and the site was accessible to all.

![Color contrast grid](docs/screenshots/color-grid.png)


## **Current Features Common to all pages**
###  **Header Element**
The header element sticks to the top of the page as the user scrolls up and down. Originally I had designed the page with a "return to top" link at the bottom of the page. However, a Code Institute graduate pointed out that the sticky header would provide a more pleasant UX and adhere to popular conventions better. The header itself contains the following features: 

#### *Title:*
![Page title](docs/screenshots/title.png)

* The title serves to state the name of the community.
* It also serves as a navigation link to the home page as per the well-established convention expected by the user.

#### *Navigation Bar:*
* The navigation bar appears on all four pages (including the form feedback page). 
* It contains links to the home, gallery,sign up, and about us page to allow easy navigation around the website. 
* The below image shows the user's current page highlighted in blue with a white border. 
![Navigation bar](docs/screenshots/nav-bar.png)
***

## **Footer**
* The footer includes direct links to all  social media accounts.

* These icons were imported from font awesome at the bottom of the page. 
![Page footer](docs/screenshots/footer.png)


## **Typography**
* Throughout the page, there are three fonts used:
  * Lato sans-serif - For the title to give it a strong presence.
  * Lato sans-serif - For all other headings including the navbar. 
  * Oswald sans-serif - for all content text.

* All fonts were sourced from Google fonts, as stated in the credits.

## **Individual Page Content features**
### **Home Page Content:**
This page gives encorages guided hikes across Ireland's scenic routes such as the Wicklow Way, Kerry Way, and Dingle Way. It emphasizes the expertise of local guides, the cultural and historical significance of the trails, and the camaraderie among hikers. The site encourages a deep connection with nature through Ireland's tranquil landscapes.

![Contact and Form-feedback pages hero image](docs/screenshots/home-page-content.png)

### **Gallery Page Content:**
The "Gallery" page on the "Hike with Me" website by Preetica showcases a collection of photos from various hiking adventures. The page is designed to visually engage visitors by displaying beautiful and scenic images of nature, trails, mountains, and other outdoor experiences. Each photo captures unique moments and landscapes from different hikes, reflecting the beauty and diversity of the natural world.

Key features of the page include:

Photo Grid Layout: The images are arranged in a grid format, allowing visitors to view multiple photos at once. This layout is visually appealing and makes it easy to browse through the collection.

High-Quality Images: The photos are high-resolution, ensuring that details are clear and the beauty of the landscapes is fully appreciated.

Captions and Descriptions: Each photo may include captions or brief descriptions, providing context such as the location of the hike or the significance of the moment captured.

User Experience: The gallery is designed to be user-friendly, with intuitive navigation and a clean, minimalist aesthetic that keeps the focus on the images.

Overall, the "Gallery" page serves as an inspiring visual showcase of hiking adventures, encouraging visitors to explore and appreciate the great outdoors.

![Zoomed out image of the gallery page content section](docs/screenshots/gallery-page-content.png)

### **Sign Up Page Content:**
The "Sign Up" page on the "Hike with Me" website by Preetica is designed to allow visitors to register for the website or specific hiking events and activities. Here's a brief overview of its features:

Registration Form: The page includes a registration form where users can enter their personal information. Typical fields might include:

Name
Email Address
Password
Confirm Password
Additional fields like phone number, preferred hiking difficulty level, or interests might also be present.
User-Friendly Design: The form is designed to be straightforward and easy to fill out, ensuring a smooth user experience. Labels and placeholders guide the user on what information is required.

Security Features: The page likely includes security features such as password strength indicators and validation checks to ensure that users provide valid and secure information.

Call to Action: Prominent "Sign Up" or "Register" buttons encourage users to complete the registration process.

Navigation Links: Links to other parts of the website, such as the login page for existing users, the home page, or the privacy policy, are typically included.

Visual Elements: The page maintains a consistent visual theme with the rest of the website, possibly incorporating images or graphics related to hiking to keep the aesthetic appealing and relevant.

Overall, the "Sign Up" page is a crucial part of the "Hike with Me" website, providing a gateway for new users to join the community and participate in hiking activities.

![Sign up page](docs/screenshots/signup-page-content.png)


### **About Us Page Content**
The "About" page on the "Hike with Me" website by Preetica provides visitors with information about the website's purpose, mission, and the people behind it. Here's a brief overview of its content and features:

Introduction: The page typically begins with an introduction that explains the main purpose of the website. This might include an overview of what "Hike with Me" is about, such as promoting hiking as a recreational activity, encouraging outdoor exploration, and building a community of hiking enthusiasts.

Mission Statement: A clear and concise mission statement outlines the goals and values of "Hike with Me." This might focus on themes like fostering a love for nature, promoting physical fitness, and encouraging sustainable hiking practices.

Founder's Story: Information about Preetica, the founder of the website, is provided. This section might include a personal story about how Preetica developed a passion for hiking, the inspiration behind creating the website, and any relevant background information.

Team Members: If applicable, the page might introduce other key team members or contributors who help run the website or organize hiking events.

Values and Philosophy: This section elaborates on the core values and philosophy guiding "Hike with Me," such as environmental conservation, community building, inclusivity, and adventure.

Activities and Services: An overview of the activities and services offered by the website, such as guided hikes, hiking tips, trail recommendations, and community events.

Visual Elements: The page is likely enhanced with relevant images, such as photos of hiking trips, scenic landscapes, and candid shots of the founder or team members enjoying outdoor activities. These visuals help create a personal connection with the audience.

Contact Information: Contact details or a link to a contact page might be provided, encouraging visitors to reach out with questions, feedback, or to get involved.

Overall, the "About" page serves to build trust and rapport with visitors by sharing the story, mission, and values behind "Hike with Me," while also providing a glimpse into the community and activities associated with the website.

![Sign up page content](docs/screenshots/aboutus-page-content.jpg)

### **Form Feedback Page Content**
* I created this page to mimic the effect of actually submitting a form. 
* I centered the text alignment on this page only. I set the text-alignment property to "justify" on smaller screen widths and to "left" on larger screens for all other pages. I made this decision because of the lack of text on the form feedback page. Matching the alignment to the other pages looked out of place.
* Since filling in the form suggests the user is interested in learning more, I have included a longer feature video about the tradition here. *Note: Originally, I had wanted to use this on the home page, but due to the length of the video, I deemed it too long for an introduction. There is no auto play on the videos, so the user can choose whether they want to engage with the video or not.*
* Link included within the content to take the user back to the initial contact page, in case they wanted to look at the ways to contact a local meditation center, send an additional message, or sign up to the mailing list.

![Form feedback content](docs/screenshots/form-feedback-content.jpg)

## **Future-Enhancements**

* The future intention of the site would be to serve as a website specifically for Malta, where there is no community until now. However, Due to the summer break, which the tradition undergoes every year, I could not reach the traditions director with my request for permission. I decided to build a tribute site to showcase to the head office and adapt the content to be more Malta specific later on. 

* At first, the purpose would remain to educate and raise awareness meaning the current content would still be applicable; however, There would be additional content I could add as interest grew. Such things would be: -

    * Times/dates/venues for Meetups in Malta to build a community
    * Times/dates/venues for Book clubs to study and discuss the materials and methods to apply them to daily life.
    * More information on the lineage of the tradition to include short biographies.

* Eventually, when Malta was designated a teacher by the head office, these would then convert into: -

    * Times/dates/venues/fees for Formal classes
    * Times/dates/venues/fees for Public talks/events
    * Include a bio for Malta's officially designated teacher at the end of the traditions lineage page or add a new page summarizing their experience.

* Once I better understand Javascript, I would like to add a burger menu for mobile-sized device screens. I found articles on achieving this with CSS and HTML alone; however, I did not deem this necessary to create the minimum viable product, which is this project.

* I would also make the contact form fully function with a post request and have a database to collate data for the mailing list.
***

## Features 
- __Navigation Bar__

  - Featured on all four pages, the full responsive navigation bar includes links to the  Home page, Gallery,Sign Up  and About US page and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

- __The landing page image__

    - The landing includes a photograph with text overlay to allow the user to see exactly which location this site would be applicable to. 
    - This section introduces the user to HIKE WITH ME with an eye catching animation to grab their attention

- __What We Offer__

   We aim to:
   - Encourage the exploration of the beautiful Irish outdoors.
   - Promote physical and mental well-being through hiking.
   - Provide a supportive and fun environment for all outdoor enthusiasts.


- __Trail Information__

  - This section will allow the user to learn about some of our favourite hiking trails. 
  - These are top-rated hiking trails recommended by our community members.

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for HIKE WITH ME. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media.

- __Gallery__

  - The gallery will provide the user with supporting images to see what the meet ups look like. 
  - This section is valuable to the user as they will be able to easily identify the types of events the organisation puts together. 

- __The Sign Up Page__

  - This page will allow the user to get signed up to Love Running to start their hikingjourney with the community. The user will be able specify if they would like to take part in road, trail or both types of running. The user will be asked to submit their full name and email address. 

- __Wireframe__
    <details open>
    <summary>Wireframe - Homepage Desktop & Mobile</summary>  

    ![homepage wireframe-mobile & desktop](readme-img/wire1.png)
    </details> 
     =<details >
    <summary>Wireframe - Gallery page Desktop</summary>  

    ![homepage wireframe-mobile & desktop](readme-img/wire2.png)
    </details> 
    <details>
    <summary>Wireframe - Gallery page Mobile</summary>  

    ![homepage wireframe-mobile & desktop](readme-img/wire4.png)
    </details>    
    <details>
    <summary>Wireframe - SignUp page Desktop</summary>  

    ![homepage wireframe-mobile & desktop](readme-img/wire3.png)
    </details> 
    <details>
    <summary>Wireframe - SignUp page Mobile</summary>  

    ![homepage wireframe-mobile & desktop](readme-img/wire6.png)
    </details>
  <summary>Wireframe - About Us page Desktop</summary>  

    ![homepage wireframe-mobile & desktop](readme-img/wire3.png)
    </details> 
    <details>
    <summary>Wireframe - About Us Mobile</summary>  

    ![homepage wireframe-mobile & desktop](readme-img/wire6.png)
    </details>              

## Testing 

- __Validation__

  * [HTML Validator](https://validator.w3.org/) was run at several points during the project and small syntax errors identified were fixed. At the final stage no errors or warnings were found
  * [CSS Validator](https://validator.w3.org/) was run several times during the project and picked up small syntax errors which were corrected. At the time of submission the css code successfully passed the validator with no errors.

- __Responsiveness__

   The website was tested on Chrome, Mozilla, Edge and Safari browsers with no problems found.

   The website was tested on numerous sized screens including Iphones 12 and 13,Samsung flip 5 , 15" laptop, 24" screen and Ipad and was found to respond as expected to all sizes.
Chrome development tools was used throughout the design process to check responsiveness and breakpoints. Adjustments were made accordingly.

- __Lighthouse Testing__

    Lighthouse testing was performed by Google's open source tool, 
    [Google Chrome DevTools](https://developers.google.com/web/tools/lighthouse). 

   - index.html 

    ![Lighthouse](readme-img/imglihthous.png)

   - gallery.html

   ![Lighthouse](readme-img/imlgallerylight.png)

   - signup.html

   ![Lighthouse](readme-img/imgsignuplight.png)



## Unfixed Bugs

Need to update

## Deployment

The site was deployed to GitHub pages. The steps taken to deploy are as follows:
1. Log in to [Github](https://github.com/)
2. Navigate to [preeticancode/HIKE-WITH-ME](https://github.com/preeticancode/HIKE-WITH.gitME) in  
   the list of repositories
3. In the GitHub repository, navigate to the [Settings] tab
4. In Settings scroll down to [GitHub pages] which opens in a new page.
5. From the source section drop-down menu, select the Master Branch
6. Once the master branch has been selected, the page is automatically refreshed and a display indicates the successful deployment and the link to the address.

The link to the live website is here:
https://preeticancode.github.io/HIKE-WITH-ME/


## Credits 

   ### Frameworks, Libraries & Programs Used

   - Balsamiq - Used to create wireframes.

   - Git - For version control.

   - Github - To save and store the files for the website.

   - Google Fonts - To import the fonts used on the website.

   - Font Awesome - For the iconography on the website.

   - Google Dev Tools - To troubleshoot and test features, solve issues with responsiveness and 
    styling.

   - Tiny PNG To compress images.

   - Convertio To convert images to webp format.

   - Favicon.io To create favicon.

   - Am I Responsive? To show the website image on a range of devices.

   - Responsive Image Linter - To optimise image sizing.

   ### Content 
  - The text for the Home page was taken google article.
  - Form contents and footer code used on main page taken from Love Running Project.
  - The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

   ### Media

  - The photos used on the home and sign up page are from our group hiking trip and some are mine.
  - The some images used for the gallery page were taken from this other open source site.



## Acknowledgements


I would like to take the opportunity to thank:
- My mentor David Bowers for his feedback, advice, guidance and support.
- My husband Rajesh for his support, advice, help with testing, and for giving me some kids free 
  time to work on my project.
- To the lovely people on the Code Institute Slack for providing peer code reviews.
- My friends and community memebers who are part of HIKE WITH ME.


  







[def]: /workspace/my-kitchen/documents/responsive.png
[def2]: #features