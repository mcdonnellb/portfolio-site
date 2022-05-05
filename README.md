Background to my idea & purpose of the project
For Project 1 my idea is to do a professional portfolio site for my work. The target audience will be recruiters or those looking for freelance web developers. The idea will be simple and consist of three responsive HTML pages. (There will be a fourth page but it is a dummy for the contact form)

I learned a lot from the love running project and planned to use the format as almost a template for what a good basic site should look like from a structural perspective. I drew inspiration from many sites for the purposes of this project, links below to 2 award winning sites that I found particularly intriguing.

http://www.rleonardi.com/design-portfolio/
http://y78.fr/3/


Requirements: Minimum 3 static HTML sites. Cloud Deployment 

User Stories:
o	As a recruiter I want to be able to make contact
o	I want to be able to learn about 
o	I want to be able to see past projects

User Goals:
o	Make contact
o	Fins information on experience / background










Planned layout and Features

Styling:
The overall appearance of the website is aimed to be airy and minimalistic as I am unfortunately not much of a visual artist. The site will be created using a colorscheme of White background, black text and light coral accents.

Font/ Typography
I have used the following throughout the website to ensure consistency. I chose this as I felt it aligned with my style preference but also was clear and concise for the ‘wordy’ sections.
Page 1. Homepage/index – basic landing page
o	Personal Bio
Fun interactive section inspired by Robby Leonardi, I of course will not be capable of producing the typ of engaging interactive Mario game, but am using it to inspire a fun feature on my homepage.
o	http://www.rleonardi.com/design-portfolio/
o	to engage the user to learn more about me, my experience and my skill set ( but not to make it so difficult it would put off an end user) 
Page 2. Porfolio
o	Gallery wheel or grid showing some sample projects that were not done by me
Images and links to portfolio sites I liked:

Page 3. Contact Page 
o	Basic HTML form
o	Buttons for call, CV, direct email

Common features:
o	Header Nav Bar
o	Footer with social media links
o	Landing page text

o	I want to use a regular Top  Nav bar that contains Home, Portfolio, Contact and an icon or my name to the right hand side.
o	Footer Containing social Media links
o	404 error page- providing a link back to safety if something is amiss, typo in web address etc to ensure user knows how to get back to the page.

Accessibility
Items I aimed to address from the accessibility testing;
1.	Ensure content is screen reader friendly using aria labels and meaningful sections/ any non text elements also labeled
2.	Ensure content is responsive for use on mobile/tablet etc.

o	Top navigation bar responsive to device use
o	Open all external sites in new tab
o	
My first pass at addressing scalability is using media queries alone and checking with web dev tools in browser to see the outcome.

To begin with I used percentages to try and address accessibility across devices, then added some flex to the CSS to ensure the site is suitable for mobile/ tablet use.



Mobile Accessibility testing:
I had to do a lot of changing around the CSS to get the look I wanted

Keep it simple
Having a testing plan is so important ( for me especially) as you can go down a rabbit hole and lose a lot of time when the plan is not structured.




1.Design
Key questions I asked myself
o	Is the design consistent across all pages?
o	Is the style displaying as expected in different browsers?
o	Is the layout meaningful and straightforward, with minimal clicks?
index.html
portfolio.html
contact.html
sendmail.html


 
Testing
2.Function
This stage of testing was to ensure all key functionality works as expected. 
Nav Bar, Footer, Gallery, CV download, direct mail, Contact form etc.
The first big issue encountered was the Nav bar becoming unusable when you scroll down the page. I addressed this by adding Z index to the navigation bar. 

Testing the scroll after fixing the Nav bar, lead me to discover the buttons were not clickable when the page was in certain positions, this lead me to adding a Z index for the Nav bar to ensure it has precedence over all else when user is scrolling.



Styling:
-	The first item to go in this phase was the left hand photo pane, it served no purpose and was not as aesthetically pleasing as I had imagined, it also lead to confusion in terms of what is the menu/ what is decorative.
-	The Footer styling changed too, removing the black and instead using white as this is more in line with the social media sites styling themselves.



Error log:
o	CSS missing from Portfolio HTML Page.


Error response – inspiring me to try to add an error response page to bring users back to safety 
 




CSS VALIDATION

 


Citations:
My code was loosely based around inspiration from Love Running

The Carousel for the Portfolio section is not of my own creation, I used code I found on the below website and have cited it within the code itself to ensure it is known I am not taking credit for anothers work.
Grid for images on Portfolio page:
o	https://www.quackit.com/html/html_editors/scratchpad/?example=/css/grid/examples/photo_gallery_flexible_width_span_3_columns_3_rows


Websites used for my portfolio section, inspired by the following blog post:
https://www.wix.com/blog/creative/2020/03/best-portfolio-websites/?utm_source=google&utm_medium=cpc&utm_campaign=9852964004^140722897092&experiment_id=^^592430043018^^_DSA&gclid=Cj0KCQjwyMiTBhDKARIsAAJ-9Vu2Ld_APEcRx4PsPUHJ7x2_MAP2tCF5aJva9UV2W3TNV0EFfvXkJ00aAinpEALw_wcB
o	https://www.krawec.org/
o	https://www.wenxinwendyju.com/
o	https://www.sophiebritt.com/
o	christinavanessa.com
o	https://www.studiobgz.com/
o	https://www.davidmilan.com/
o	https://www.thaiphamphotography.com/
o	analeovy.com
o	https://www.ryanhaskins.com/
o   http://www.rleonardi.com/design-portfolio/
o   https://samanthakeelysmith.com/
o   https://kennethreitz.org/

Icons taken from Font Awesome:
https://fontawesome.com/search?q=gradu&s=solid%2Cbrands


Lessons Learned:
o	My biggest error was starting this project before I had completed all of the HTML and CSS content. I built it in notepad++ and tested in the browser. I lost approx. 60 hours purely on trial and error, which had I focused on the content I would have had more knowledge built up before attempting to build the site. – this is why my first few commits are huge as I had the mammoth task of copying everything over from notepad++ to gitpod.
o	Use the Code institute template – as it contains all of the ne
o	Commit early and often, and use the meaningful messages. I found myself switching tenses a lot and adding generic notes as I had made so many changes I couldn’t recall the main items amended.
o	Style should be the final stage not the first, I wasted a lot of valuable time down google rabbit holes and moving elements pixel by pixel trying to make the page look aesthetically pleasing. (before using flex)
o	Progress bar – the value between the tags does not display and needs a label- this is something tiny that I spent a lot of time trying to fix.
o	Labels for the contact form – important for screen reader- I removes as I could not get it to align
o	Keep it simple! I tried to do several things which were far above my capabilities and lost a lot of time trying to implement these features which ended up being scrapped.(I tried to do some PHP to get a functioning contact form as well as many other items that were scrapped to ensure I was actually ticking the brief’s boxes before adding unnecessary items. 


Quirks;
o	Label display none – I left the labels in for screen reader purposes but set to display none as the placeholder text is sufficient for the end user.
o	The layout of the gallery is different on mobile and resizes into little circles which I felt was easier to view on mobile devices- this was intentional.



Future Features(items I wanted to implement but was unable to)
o	404 error page – I didn’t manage to get this aspect working unfortunatley
o	Update to gallery on portfolio page to include my own work
o	PHP for the contact form to send a mail to me on submit
o	Dark Mode button to switch the styling to Dark background and white text.


Wireframes of the finished product:

