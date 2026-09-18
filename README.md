PROJECT OVERVIEW
Your name: William Mensah Effah
Project title: Capstone project
Assigned industry: Real Estate and Construction
Business: Real Estate Agency 
Target: Real Estate agencies, agents, property buyers, NGOs, Organizations  
Main goal: The goal is to use the page to make the organizations work visible and known to customers.

FEATURES
The website uses JavaScript to implement a responsive mobile navigation menu, animated statistics counters, and smooth scrolling navigation. These interactions improve usability, user engagement, and overall user experience on both desktop and mobile devices.

DESIGN RESEARCH 
Design inspiration was taken from;
https://midtide.co/
https://dribbble.com/shots/27053503-Modern-Real-Estate-Website-Hero-Section-Property-Landing-Page


GOLDEN GATE CONSTRUCTIONS PAGE DEVELOPMENT PROCESSES

## 1. Business Selection

The business selected for this project was **Golden Gate Constructions**, a real estate and construction company. The company was chosen because the construction and real estate industry requires a strong online presence to showcase projects, attract potential clients, and provide information about services. A landing page was considered an effective solution for promoting the company's brand and services.

## 2. Research and Planning

Before development began, research was conducted on modern real estate and construction company websites. Several industry websites were reviewed to understand common design elements, layouts, and user experience practices. Key sections identified during the research included:

* Hero section with a compelling headline and call-to-action.
* Services section highlighting core offerings.
* How We Work section explaining the company's process.
* Recent Projects section displaying completed work.
* Contact section for client inquiries.
* Professional footer with company information.

The research helped establish a clear structure and design direction for the website.

## 3. Local Development Environment Setup

A project folder named **golden-gate-constructions** was created on the local machine. The following files and folders were organized:

* index.html
* style.css
* script.js
* README.md
* images folder

Visual Studio Code (VS Code) was used as the code editor. The project was tested locally using a web browser to ensure all components functioned correctly during development.

## 4. GitHub Repository Creation and Initial Push

A new GitHub repository named **golden-gate-constructions** was created. Git was initialized locally using the following commands:

```bash
git init
git add .
git commit -m "Initial project setup"
git branch -M main
git remote add origin <repository-url>
git push -u origin main
```

This initial push established version control and allowed project progress to be tracked throughout development.

## 5. HTML Development

The website structure was created using HTML5. Semantic elements were used to improve readability and accessibility. The following sections were implemented:

* Navigation Bar
* Hero Section
* Statistics Section
* Services Section
* How We Work Section
* Recent Projects Section
* Contact Form
* Footer

Proper headings, paragraphs, buttons, images, and form elements were included to create a complete landing page.

## 6. CSS Styling and Responsiveness

CSS was used to enhance the visual appearance of the website. Styling included:

* Professional typography using Google Fonts.
* Consistent color scheme.
* Card layouts for services and projects.
* Hero background image.
* Hover effects for cards and project images.
* Shadows and spacing for modern aesthetics.

Responsive design techniques such as Flexbox, CSS Grid, and media queries were implemented to ensure the website displays properly on desktops, tablets, and mobile devices.

## 7. JavaScript Functionality

JavaScript was used to add interactivity and improve the user experience. Three key interactions were implemented:

### Mobile Navigation Menu

Allows users on smaller screens to open and close the navigation menu using a hamburger button.

### Animated Statistics Counter

Animates company statistics from zero to their target values when the page loads.

### Smooth Scrolling Navigation

Provides a smooth scrolling effect when users click navigation links that point to sections within the page.

These interactions make the website more engaging and user-friendly.

## 8. Testing and Quality Assurance

The website was tested throughout development to ensure functionality and responsiveness. Testing included:

* Navigation link functionality.
* Mobile menu responsiveness.
* Contact form display.
* Hover effects on cards and project images.
* JavaScript animations.
* Layout consistency across different screen sizes.

Any identified issues were corrected before final deployment.

## 9. Final GitHub Push

After all features had been implemented and tested successfully, the final version of the project was committed and pushed to GitHub using:

```bash
git add .
git commit -m "Completed Golden Gate Constructions landing page"
git push origin main
```

This ensured that the latest version of the project was available in the remote repository.

## 10. Deployment and Submission

The completed project was deployed using Netlify. The GitHub repository was connected to Netlify, which automatically built and published the website.

The following links were included in the final submission:

* GitHub Repository Link;
  
* Netlify Live Website Link;
  https://candid-dasik-2ddf82.netlify.app/

## Conclusion

The Golden Gate Constructions landing page was successfully designed, developed, tested, version-controlled using GitHub, and deployed on Netlify. The project demonstrates proficiency in HTML, CSS, JavaScript, responsive web design, Git version control, and web deployment practices.

RUNNING AND TESTING
# Opening the Project Locally, Testing Performed, Results, and Known Issues

## Opening the Project Locally

The project can be opened and run locally using the following steps:

1. Download or clone the project repository from GitHub.
2. Extract the project files if they are downloaded as a ZIP file.
3. Open the project folder in Visual Studio Code (VS Code) or any preferred code editor.
4. Ensure the project structure contains the following files and folders:

```text
golden-gate-constructions/
│
├── index.html
├── style.css
├── script.js
├── README.md
└── images/
```

5. Open the `index.html` file in a web browser by:

   * Double-clicking the file, or
   * Using the VS Code Live Server extension and selecting "Open with Live Server."

6. The website will load in the browser and all features will be available for testing.


## Testing Performed

Several tests were conducted to ensure the website functions correctly and provides a good user experience.

## Testing Results Summary

| Feature          | Status | Result                               |
| ---------------- | ------ | ------------------------------------ |
| Navigation Links | Passed | All links worked correctly           |
| Smooth Scrolling | Passed | Scroll animation functioned properly |
| Mobile Menu      | Passed | Responsive menu operated correctly   |
|                  |        |                                      |

<img width="1919" height="1078" alt="Screenshot 2026-09-18 162213" src="https://github.com/user-attachments/assets/580062ee-15f2-44aa-ae07-c6e9a2883ccf" />

The website was successfully tested across multiple screen sizes and browsers. All core functionalities, including navigation, responsiveness, animations, hover effects, and layout behavior, performed as expected. The identified issues are minor and do not affect the overall usability or presentation of the landing page.

**Known Issues**

The following limitations were identified:

1. Contact Form Backend

The contact form currently provides only front-end functionality.

Impact:

Form submissions are not stored or emailed.

Future Improvement:

Integrate a backend service such as Formspree, Netlify Forms, or a custom server-side solution.

REFLECTIONS AND LINKS
# Challenge Solved and What I Learned

## Challenge Solved

One of the main challenges encountered during the development of the Golden Gate Constructions landing page was making the website **responsive across different screen sizes**, particularly on mobile devices. The desktop layout looked well organized, but some elements could become crowded when the screen width was reduced.

To solve this, I used **CSS media queries, Flexbox, and CSS Grid** to adjust the layout for smaller screens. I also implemented a JavaScript-powered hamburger menu so that the navigation links could be accessed easily on mobile devices.

Another challenge was adding meaningful interactivity to the website. I solved this by using JavaScript to create an **animated statistics counter, mobile navigation menu, and smooth scrolling navigation**.

## What I Learned

Through this project, I learned how to:

* Structure a complete landing page using **HTML5**.
* Use **CSS Grid and Flexbox** to create responsive layouts.
* Apply media queries to make websites mobile-friendly.
* Create interactive features using **JavaScript**.
* Add hover effects and transitions to improve user experience.
* Organize website files into a professional project structure.
* Use **Git and GitHub** for version control and project management.
* Test a website at different screen sizes and identify layout issues.
* Deploy a website using **Netlify**.
* Research existing websites for design inspiration while developing an original layout.
* Understand the importance of testing and refining a website before final deployment.

Overall, the project improved my practical understanding of front-end web development and showed me how HTML, CSS, and JavaScript work together to create a functional, responsive, and interactive website.

LINKS
Netlify live link;
https://candid-dasik-2ddf82.netlify.app/

Github Repository link;


