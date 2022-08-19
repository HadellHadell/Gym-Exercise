 # Gym Exercise
 
## Purpose of the project
The purpose of the project is to build an easy to use static Website for people interested in gym exercising.
You can find the website <a href="https://hadellhadell.github.io/Gym-Exercise/contact.html">Here</a>.
 
## User stories
 
### Visitor home page:
As a visitor i want to find the home page with informative content and internal links to navigate the website and social media links

### Visitor gallery page
As a visitor i want to be able to see pictures and videos from the gym 

### Visitor Contact page
As a visitor i want to be able to find contact information and get in contact with the gym
 
## Features
 
### Header and navigation:
The header contains the logo of the gym "Gym Exercise" and navigation links. The logo has the function that when you click it you automatically gets directed to the homepage. In the header a navigation element is also nested which enables the visitor to navigate the website without using "forward" and "back" buttons. The ``` nav ``` element works by navigation links to the different pages

### Homepage:
A page with the main content and introductory text which show the user what he or she will find on the site and what the use of the site is for. Display main content and is the center page of the websites information and structure
 
### Gallery page:
This page conatins pictures and videos from the gym which works as a tool to give the visitor a perception of what the gym looks like and give a short feeling on the social atmosphere.

### Contact page:
This page contain the gyms all contact information which enables users to get in contact easily with the gym and find it on the map
* The contact page is also containing a "message form" to enable visitors to send dircet message directly from the website.

### Footer
The footer sits at the bottom of all the websites pages and display links and font awesome symbols to social media platforms where the gym is active 
## future features:
### Schedule page for training sessions:
In the future I would like to implement a schedule feature where the user can observe a schedule with training sessions led by the gym staff. The schedule should display which time the sessions are taking place and where in the gym (or perhaps if it is an outdoor session).
 
### Member login:
I would also in the future implement a member page where members log in via the main page and get directed to this new page. On this page I want to show the user features as when the user last visited the gym and for how long that session lasted. I would like to give the user the ability to log and track progress related to their training sessions from the gym so the member page becomes a useful tool.
 
## Typography and color scheme
The fonts and color scheme I have chosen derives from the basic idé that the site is going to look professional, slick and pleasing. This without taking the focus from the content
### Fonts:
I have chosen the fonts Cormorant SC because it looks slick and professional. It gives a sense of clarity and is easily read. Together with the second font i´ve chosen it works perfect they compliment each other really well. The second font is Lora which has a small roundness to the look and isn't as sharp as Cormorant SC and this is a good relationship between them
### Color:
The colors on the website are shades of grey which works well with the fonts used. The text has a darker shade of grey to make it easier to read and the background color for the footer and the quotes section are set in grey with a slight tint of light blue for contrast.
 
## Technology
* HTML5
* CSS3
* Markdown
* Gitpod
* Github
* Balsamiq Wireframes
* Imgbb
## Testing

### code validation

#### HTML: 
Passed through the w3c html vlaidator without errors.

#### CSS: 
Passed trhought the w3c css validator without errors.

#### Accesability:
The colors and fonts have been confirmed to be accessible and easy to read by run the website through the developer tool lighthouse. 

<a href="https://ibb.co/FwgNhM2"><img src="https://i.ibb.co/856Tmpq/Sk-rmbild-16.png" alt="developer tools preformance check" border="0"></a> 

### test cases 
* The websites navcigation elements has been tested and works on diffrent browsers and smaller devieces.
* The website is responsive and looks good on common screen sizes: comfirmed by developer tools.
* The form has been ckeck and works as intended. 
* The website has been overhauled and corresponds to the user stories where the visitor can find information of the purpose of the website, pictures, videos and a page with contact information. 

### Homepage

<a href="https://ibb.co/41dKb7z"><img src="https://i.ibb.co/PDQF2NK/Homepage-firsthalf.png" alt="Homepage-firsthalf" border="0"></a>

<a href="https://ibb.co/Wgm0kbJ"><img src="https://i.ibb.co/PwqMc7H/Homepage-secondhalf.png" alt="Homepage-secondhalf" border="0"></a>
### Gallery

<a href="https://ibb.co/TrXTp5m"><img src="https://i.ibb.co/LvwPbfn/Gallery-pictures.png" alt="Gallery-pictures" border="0"></a>

<a href="https://ibb.co/bj9tGtL"><img src="https://i.ibb.co/1YWc4cK/Gallery-video.png" alt="Gallery-video" border="0"></a>
### Contact page

<a href="https://ibb.co/NjVzhzv"><img src="https://i.ibb.co/7WYFcFf/Sk-rmbild-11.png" alt="Contact-page" border="0"></a>
### fixed bugs
When i deployed the project the the linking between html files and css stylesheet were broken which resulted in an unstyled website. The root of the problem was that the linking were set to be looking in the wrong file and could not find the files i told i to find. see example below.
```html
<link rel="stylesheet" href="../assets/css/style.css">
```
When removing the ``` ../ ``` before the ``` assets/css/style.css ``` the linking was repair and functioning.

### supported screens and browsers
* The website have been tested and works on following browsers: Chrome, Firefox, Microsoft Edge, Safari.
* The website have been tested on a smaller device (Oneplus Nord CE 2) and works fine.
* The webbsite corresponds well to smaller browser windows.
## Deployment steps
 
### Gitpod
1. Commit all data to github by using the `git add .` command and commit.
2. When you have committed your data and changes use the `git push` command to push the data to Github.

### Github pages:
1. Enter the repository and navigate to `settings`.
2. On the left side find the category `pages`.
3. Go down to the `branch section` and select `main` in the `drop-down menu`.
4. After you have done these steps press `save button` in the branch section. 
5. A link to your deployed website should appear at the top of the page. 
 
## Credits

### Content
* Parts of the code is taken from https://www.geeksforgeeks.org/
* Parts of code is taken from the Code Institute Love Running project.
* Code beautifcation html: https://codebeautify.org/htmlviewer
* Code beautification css: https://www.cleancss.com/css-beautify/

### Media

Photo by Jonathan Borba: https://www.pexels.com/photo/woman-kneeling-with-barbel-on-shoulders-3076514/

Extra help with footer layout: https://www.geeksforgeeks.org/how-to-create-footer-to-stay-at-the-bottom-of-a-web-page/

Photo by Ketut Subiyanto: https://www.pexels.com/photo/man-in-gray-tank-top-and-blue-shorts-doing-push-up-4720309/

Photo by cottonbro: https://www.pexels.com/photo/woman-practicing-plyometrics-7675414/

Photo by Andres  Ayrton: https://www.pexels.com/photo/obese-woman-lifting-dumbbells-in-gym-6551426/

Photo by ShotPot: https://www.pexels.com/photo/photo-of-man-in-red-shirt-4047039/

Photo by Cliff  Booth: https://www.pexels.com/photo/woman-doing-boxing-4058375/

Photo by Mikhail Nilov: https://www.pexels.com/photo/elderly-man-doing-yoga-exercise-7500641/

Video by Mikhail Nilov: https://www.pexels.com/video/man-in-wheelchair-lifting-weights-with-trainer-7699778/

Video by Andres  Ayrton: https://www.pexels.com/video/a-personal-trainer-talking-to-his-client-about-healthy-food-and-junk-food-6547780/

Photo by Gleb Krasnoborov: https://www.pexels.com/photo/man-in-black-tank-top-lifting-barbell-at-the-gym-2628215/

Photo by Pixabay: https://www.pexels.com/photo/bodybuilding-close-up-dumbbells-equipment-260352/

Photo by Ivan Samkov: https://www.pexels.com/photo/man-exercising-with-dumbbells-4164769/