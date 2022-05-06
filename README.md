**Background to my idea & purpose of the project**
For Project 1 my idea is to do a professional portfolio site for my work. The target audience will be recruiters or those looking for freelance web developers. The idea will be simple and consist of three static HTML pages styled using CSS. (There will be a fourth page but it is a dummy for the contact form)

*   index.html
*   portfolio.html
*   contact.html
*   sendmail.html

The idea is simple and will allow me to keep building on this site as my skillset grows.

I learned a lot from the love running project and planned to use the format as almost a template for what a good basic site should look like from a structural perspective. I drew inspiration from many sites for the purposes of this project, links below to 2 award winning sites that I found particularly intriguing.

http://www.rleonardi.com/design-portfolio/
http://y78.fr/3/


My site can be accessed at the below Github repository:
https://mcdonnellb.github.io/portfolio-site/


# Table of Content
+ [User Experience](#userexperience "User Experience")
  + [User Stories](#user-stories "User Stories")
  + [User Goals](#user-goals "User Goals")
  + [Requirements](#requirements "Requirements")
  + [Design](#design "Design")
    + [Typography](#typography "Typography")
    + [Personal Bio](#personalbio "Personal Bio")
    + [Contact Page](#contactpage "Contact Page")
    + [Common Features](#commonfeatures "Common Features")
+ [Accessibility](#accessability "Accessability")
  + [Testing](#testing "Testing")
    + [Functionality](#functionality "Functionality")
    + [Styling](#styling "Styling")
    + [Error Log](#errorlog "Error Log")
    + [CSS Validation](#cssvalidation "CSS Validation")
    + [HTML Validation](#htmlvalidation "HTML Validation")

  + [Citations](#citations "Citations")
+ [Lessons Learned](#lessons-learned “Lessons Learned")
+ [Quirks](#quirks "Quirks")
  + [Future Features](#future-features "Future Features")



### User Experience


#### User Stories:
*   As a recruiter I want to be able to make contact
*	I want to be able to see past projects

#### User Goals:
*	Make contact
*	Fins information on experience / background

#### Requirements
* 3 static HTML pages styled using external CSS file
*   Responsive for mobile use
*   Deployment through cloud solution eg GIT



### Design

The overall appearance of the website is aimed to be airy and minimalistic as I am unfortunately not much of a visual artist. The site will be created using a colorscheme of White background, black text and light coral accents.


### Wireframes of the finished product:

/assets/images/electrocat.png

assets/images/desktop-contact.jpg
assets/images/contact-mobile.jpg
assets/images/desktop-index.jpg
assets/images/iphone-index.jpg
assets/images/desktop-portfolio.jpg
assets/images/portfolio-mobile.jpg
assets/images/desktop-sendmail.jpg
assets/images/iphone-sendmail.jpg




**Key questions I asked myself**
*	Is the design consistent across all pages?
*	Is the style displaying as expected in different browsers?
*	Is the layout meaningful and straightforward, with minimal clicks?

**Typography**
I have used the following throughout the website to ensure consistency. I chose this as I felt it aligned with my style preference but also was clear and concise for the ‘wordy’ sections.
Page 1. Homepage/index – basic landing page

**Personal Bio**
*   Small section to introduce me using a small image- this is only on the homepage, not seen throughout other pages. 
*   Page 2. Porfolio*
*	Gallery wheel or grid showing some sample projects that were not done by me
Images and links to portfolio sites I liked:

**Contact Page**
*	Basic HTML form
*	Buttons for call, CV, direct email

**Common features:**
*	Header Nav Bar
*	Footer with social media links
*	Landing page text
*	I want to use a regular Top  Nav bar that contains Home, Portfolio, Contact.
*	Footer Containing social Media links
*	404 error page- providing a link back to safety if something is amiss, typo in web address etc to ensure user knows how to get back to the page.

**Accessibility**
Items I aimed to address from the accessibility testing;
*	Ensure content is screen reader friendly using aria labels and meaningful sections/ any non text elements also labeled
*	Ensure content is responsive for use on mobile/tablet etc.
*	Top navigation bar responsive to device use
*	Open all external sites in new tab
	
My first pass at addressing scalability is using media queries alone and checking with web dev tools in browser to see the outcome.

To begin with I used percentages to try and address accessibility across devices, then added some flex to the CSS to ensure the site is suitable for mobile/ tablet use.


 
#### Testing
**Functionality**
This stage of testing was to ensure all key functionality works as expected. 
Nav Bar, Footer, Gallery, CV download, direct mail, Contact form etc.
The first big issue encountered was the Nav bar becoming unusable when you scroll down the page. I addressed this by adding Z index to the navigation bar. 

Testing the scroll after fixing the Nav bar, lead me to discover the buttons were not clickable when the page was in certain positions, this lead me to adding a Z index for the Nav bar to ensure it has precedence over all else when user is scrolling.



**Styling:**
*   The first item to go in this phase was the left hand photo pane, it served no purpose and was not as aesthetically pleasing as I had imagined, it also lead to confusion in terms of what is the menu/ what is decorative.
*   The Footer styling changed too, removing the black and instead using white as this is more in line with the social media sites styling themselves.



**Error log:**
* CSS missing from Portfolio HTML Page.
* Nav bar not usable if you scroll down the page
* 

Error response – inspiring me to try to add an error response page to bring users back to safety 
 




#### CSS VALIDATION**

 ** Insert Image of CSS Validation**


### Citations:
My code was loosely based around inspiration from Love Running

The Carousel for the Portfolio section is not of my own creation, I used code I found on the below website and have cited it within the code itself to ensure it is known I am not taking credit for anothers work.
Grid for images on Portfolio page:
o	https://www.quackit.com/html/html_editors/scratchpad/?example=/css/grid/examples/photo_gallery_flexible_width_span_3_columns_3_rows


Websites used for my portfolio section, inspired by the following blog post:
https://www.wix.com/blog/creative/2020/03/best-portfolio-websites/?utm_source=google&utm_medium=cpc&utm_campaign=9852964004^140722897092&experiment_id=^^592430043018^^_DSA&gclid=Cj0KCQjwyMiTBhDKARIsAAJ-9Vu2Ld_APEcRx4PsPUHJ7x2_MAP2tCF5aJva9UV2W3TNV0EFfvXkJ00aAinpEALw_wcB
*   https://www.krawec.org/
*	https://www.wenxinwendyju.com/
*	https://www.sophiebritt.com/
*	christinavanessa.com
*	https://www.studiobgz.com/
*	https://www.davidmilan.com/
*	https://www.thaiphamphotography.com/
*	analeovy.com
*	https://www.ryanhaskins.com/
*   http://www.rleonardi.com/design-portfolio/
*   https://samanthakeelysmith.com/
*   https://kennethreitz.org/

Icons taken from Font Awesome:
https://fontawesome.com/search?q=gradu&s=solid%2Cbrands


### Lessons Learned:
*	My biggest error was starting this project before I had completed all of the HTML and CSS content. I built it in notepad++ and tested in the browser. I lost approx. 60 hours purely on trial and error, which had I focused on the content I would have had more knowledge built up before attempting to build the site. – this is why my first few commits are huge as I had the mammoth task of copying everything over from notepad++ to gitpod.
*	Use the Code institute template – as it contains all of the ne
*	Commit early and often, and use the meaningful messages. I found myself switching tenses a lot and adding generic notes as I had made so many changes I couldn’t recall the main items amended.
*	Style should be the final stage not the first, I wasted a lot of valuable time down google rabbit holes and moving elements pixel by pixel trying to make the page look aesthetically pleasing. (before using flex)
*	Progress bar – the value between the tags does not display and needs a label- this is something tiny that I spent a lot of time trying to fix.
*	Labels for the contact form – important for screen reader- I removes as I could not get it to align
*	Keep it simple! I tried to do several things which were far above my capabilities and lost a lot of time trying to implement these features which ended up being scrapped.(I tried to do some PHP to get a functioning contact form as well as many other items that were scrapped to ensure I was actually ticking the brief’s boxes before adding unnecessary items. 
*Do not copy your readme from a word file! This lead to a massive panic last minute to try and format my readme.


### Quirks
*	Label display none – I left the labels in for screen reader purposes but set to display none as the placeholder text is sufficient for the end user.
*	The layout of the gallery is different on mobile and resizes into little circles which I felt was easier to view on mobile devices- this was intentional.
* I have used a deprecaited tag on the homepage to animate the text asking the user to scroll down the page- I am using this as a placholder as it will eventually be replaced with a javascript function to gamify that section.



### Future Features
	404 error page – I didn’t manage to get this aspect working unfortunatley
*	Update to gallery on portfolio page to include my own work
*	PHP for the contact form to send a mail to me on submit
*	Dark Mode button to switch the styling to Dark background and white text.


