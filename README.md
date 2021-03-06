# CuteCakesByBronaghMS1 (https://lornajane92.github.io/CuteCakesByBronaghMS1/)

## First Milestone project for Code Institute by Lorna Clarke. 

### User Experience:
===================

My project is to build a website for small business Cute Cakes by Bronagh. 
Bronagh runs her business from her kitchen/studio on a small scale selling her cakes directly to customers. 
Each cake is carefully prepared and decorated in accordance to customer’s specifications and all health and safety criteria.
Bronagh runs her business solo, along-side her full-time job, this means Bronagh needs her website to do a little work on her behalf;    
A visually pleasing and easy to use website that will showcase her work and entice customers to book her for their cake needs.    

* There will be a gallery area presenting some of Bronagh’s most impressive and popular cakes.
* Bronagh runs seasonal cakes on holidays such as Christmas, Valentine's Day, Halloween, Communion/Confirmation season etc. 
  These cakes are to be showcased on a modal when the website loads, encouraging customers to order while there is still availability. 
* A menu section where Bronagh lists the types of cakes and icings she uses.
* Bronagh would like to omit pricing from the website as it very much varies on a cake to cake basis, depending on: number of people to feed, 
   filling, icing, sponge/chocolate biscuit cake and details such as hand made characters and accents. Leaving pricing off the website not only 
   ensures that customers aren’t expecting one price and disappointed when they are potentially quoted something higher, 
   but it also creates an opportunity for Bronagh to work within someone’s budget as a customer could potentially be put off purchasing by seeing a price that
   is outside of their budget.
* A FAQ section where there will be answers to Bronagh’s most asked questions to reduce the amount of general queries in her inbox.
* A reviews section of past customers to assure potential buyers they are getting a high quality product.
* A calendar section where customers can see Bronagh’s availability as a means to reduce the amount of emails she will have to respond to informing 
   customers she is fully booked.
* The calendar will also be colour coded into three levels “Spaces Available”, “Some Spaced Available” and “Fully Booked”.
   Bronagh will be able to update this herself so that she may work her bookings into her busy schedule easily. 
* A clear and easy to use contact form where customers can make a selection of “book a consultation” to book a meeting for large events 
   such as weddings, also “make a booking” for oderers such as seasonal offerings and "general query" to answer any potential questions
   not covered in the website. These messages will be sent to Bronagh’s email and they will also arrive to her account marked as important. 
* Links to social media so that customers may peruse her work and follow her on her various platforms.
* Contact and location details so that customers may easily find Bronagh’s studio where she hosts consultations and is also a collection point.    

*User story*    

Bronagh’s customer base consists primarily of people living in the Celbridge/Lucan/Leixlip/Maynooth areas and she also provides cake delivery for these areas. 
Organising delivery or collection specification will not be available on the website as this is organised on a client to client basis depending 
on their needs and Bronagh’s schedule. 
Bronagh’s skills, qualifications and the extent to which she can customise cakes sets her aside from other bakeries in the area. 
Although there are other independent cake makers in the area many of Bronagh’s customers have been coming to her for years, 
she has gathered enough repeat custom that within her schedule that she is always busy.     


* As a first time user, I would like to be able to easily navigate throughout the website so that I can find the information I require. 
* As a first time user, I would like to learn about and see Bronagh’s work, so that I can make an informed purchase.
* As a first time user, I would like to find Bronagh’s location, so that I know if I am within her service area/ can transport a cake easily to the venue. 
* As a first time user, I would like to easily check availability, so that I know in advance of making a booking that she can facilitate it.
* As a first time user, I would like to contact Bronagh, so that I may book a consultation. 
* As a return user, I would like to be informed of Bronagh’s seasonal cake availability, so that I may make a repeat order before she sells out.
* As a return user, I would like to access Bronagh’s social media, so that I can recommend her to my friends and show them a high quality picture
  of the cake she made for me. 
* As a return user, I would like to book well in advance for a big party in a few months time, so that I can be positive I have the cake I want for the event. 
* As a return user, I would like clear and direct access to the contact form and calendar, as I am making a repeat order and already know what I want and for when. 
* As a potential collaborator, I would like to contact Bronagh, so that we can collaborate on a project I am working on.     


| Feature                                    | Importance | Feasibility |
|--------------------------------------------|------------|-------------|
| Gallery                                    |     1      |     5       |
| Seasonal Cake Showcase                     |     2      |     4       |
| Menu                                       |     1      |     5       |
| FAQ                                        |     2      |     5       |
| Reviews                                    |     1      |     5       |
| Link Reviews with Facebook/Google Reviews  |     5      |     2       |
| Calendar                                   |     2      |     4       |
| Color Coding                               |     3      |     3       |
| Social Media Links                         |     1      |     5       |
| Contact Form                               |     1      |     5       |
| Location Map                               |     2      |     3       |
     
 Bronagh’s client base is primarily made up of Women from the ages of late 20s to 50+. 
 With this in mind I will be keeping the design of the website as straight forward and uncluttered as possible, 
 while also keeping in mind mobile first principles. For the majority of interactions Bronagh would like to keep them either via mail 
 or in person as she would like to keep her personal details private and contact from customers to come in on one platform for simplicity.  
 I will use a relatively linear and easy to navigate hierarchical structure, keeping in mind the order of the cake booking process .ie 
 the opening page information, looking at work, perusing the menu, answering general queries, seeing if there is availability at the time of the event, 
 making contact. I hope to create a site that not only showcases the products but is intuitive for any potential customer/collaborator to use.    

*Wireframe*    

![wireframe](https://github.com/lornajane92/CuteCakesByBronaghMS1/blob/4a97acfdea172e19db93b4e71417de009828eb96/wireframe/CCBBWireframe.png)   

### Coding process & Bugs   
=========================== 

Before starting any coding on this project I first inserted my stylesheet links provided on Bootstrap and Fontawesome websites. 
Next created my files/folders and uploaded my branding logos that I made using the Canva app. 
To begin I divided the body into three sections for the navbar, the body and the footer of each page. 
For the Navbar I used and modified a template available on the bootstrap website, I then applied the small white branding to the 
upper left corner. The picture did not fit initially and with some reading and trial and error I got it to a size I was happy with.
I then added the information to the menu links in the navbar that take you from page to page within the website.     
When coding the body I found the resource of the layout grid provided by Bootstrap to be a great asset and used one of their 
default templates for a four and three column layout. I decided this would be best for my page as it allowed me to have the 
main content centered, branding to the left and any other information to the right as on each page I wanted the information available 
at first glance.    
When setting up the grid initially I used the “flex” class alongside the “container” class. This proved to be an issue down the line 
as I was having problems with a small amount of horizontal scroll. I rectified the problem after a google search and the help of the 
Bootstrap flex page. Next I added in my footer, I modified the sticky footer provided in the Bootstrap examples page and applied CSS to 
customise it to my needs. When I applied the copyright in the left of my footer, the text was not sitting where I would have liked 
because I was using a template. The Bootstrap float page helped me resolve this issue. 
Next I inserted the social media links in the bottom right. I sourced the icons from the FontAwesome website. 
I positioned and styled them using Bootstrap classes and CSS.    
When I had completed the footer I positioned the main brand logo using CSS parameters, keeping in mind on the homepage I wanted to 
present more information below the logo. I was now ready to add my about and reviews section to my homepage. 
I availed of information listed in the Bootstrap spacing page to help me position the content where I desired. 
Under the logo I added a location map and a notation asking that any contact for orders be made via the contact page on the website. 
To embed a google map of a specific location I found a particularly helpful youtube tutorial which I have linked below along with all 
other reading materials and in the code along with all other resources.    
Once I completed the homepage, I started on the menu. I copy and paste the code from the homepage and removed the about/reviews/map 
as I intended to use the same core layout for all pages.   
After the menu I began on the gallery page, copying and pasting the code from the menu page. I edited my links in the navbar and removed any
content I did not need for the page. I used a Bootstrap carousel template for the gallery and some CSS to adjust the size and positioning.
I carried out the same procedure for the FAQ page as the menu page as it was essentially just replacing the headings and text 
with the relevant information. I applied some minor CSS to reposition the text and headings. When editing the FAQ I could not view all 
of the content as some of the text was cut off and I couldn't scroll to view it. I addded the p-5 class to rectify this.    
While I was trying to scroll down I also found some horizontal scrolling that showed my navbar didn't go all the way to the edge of the page, 
I rectified this with CSS setting the width to 100%. Once I had done this the navbar logo no longer sat inside the navbar. 
I found the solution to this on stackoverflow. This glitch also moved the brand logo on all pages to be overlapped by the navbar 
and it moved the gallery and faq headings to be flush with the nav bar. This was rectified with CSS.    
Once I had solved these issues I began working on my calendar page, I had not used a calendar on a website before, 
so I opted to embed a Google calendar. I set up a dummy account and made the events only to find that when embedding 
a Google calendar you can only have one color per calendar. To have a calendar fully colour coded like I had planned I would have to set up
three different calendars. I had hoped to get back to do this but unfortunately I ran out of time. I also looked into building a more 
responsive calendar and found some resources on using Google APIs but I have not yet learned the skills to execute this and hope to 
add it in the future.    
I set up my contact page using a form template from Bootstap. I edited this template to suit my needs, to contain a drop down menu
and I also added and customised a "submit" button. The idea of this form would that it would send emails directly to the business gmail
marked as important, which I found some infomation on but unfortunately at this time I am unable to set up such a function.
Finally I went back to my navbar to insert a dropdown menu for tablet and mobile devices. I found a tutorial to be particularly helpful
and I used the code from there for the button and the expand/collapse function. I modified the look of the menu to match the website using
CSS. At this point I went back through my code making edits for small screen to tablet sized screens. I wanted my content to be displayed as
a scrolling site on screens this size. I added the required column classes but the padding class I had applied previously meant the sections 
had a large gap between them, which I did not like. To remove this I applied the px-5 and py-2 classes but this cut the upper content off 
with the navbar. I decided to revert to the original padding, as it meant the content could be viewed in full on all screen sizes. I did not
have enough time to fix this issue. Had I given myself enough time to carryout this project thoroughly I would have also liked to include 
more styling and a modal page to showcase seasonal offerings.        

### Credits  
============= 
* Branding and Logo belong to Lorna Clarke
* All cake images belong to Bronagh Fitzgerald sourced from: https://www.instagram.com/cutecakesbybronagh/
* Bootstrap stylesheets: https://getbootstrap.com/docs/4.4/getting-started/introduction/
* Fontawesome CDN: https://www.bootstrapcdn.com/fontawesome/
* Navbar template: https://getbootstrap.com/docs/4.5/components/navbar/
* Navbrand sizing: https://stackoverflow.com/questions/33929604/fit-image-to-bootstrap-navbar-height-responsively
* Bootstrap grid system: https://getbootstrap.com/docs/4.0/layout/grid
* Bootstrap flex: https://getbootstrap.com/docs/4.0/utilities/flex/
* Bootstrap spacing: https://getbootstrap.com/docs/4.0/utilities/spacing/
* Embedding Google map: https://www.youtube.com/watch?v=KIC0OK9nKXY&ab_channel=GeekTutorials
* Bootstrap sticky footer: https://getbootstrap.com/docs/4.0/examples/sticky-footer/
* FontAwesome Facebook: https://fontawesome.com/icons/facebook-f?style=brands
* FontAwesome Instagram: https://fontawesome.com/icons/instagram?style=brands
* Navbar brand image fix: https://stackoverflow.com/questions/33929604/fit-image-to-bootstrap-navbar-height-responsively
* Embed Google calendar: https://www.youtube.com/watch?v=vksO63XQQ3w&ab_channel=WordPressTutorials-WPLearningLab
* Bootstrap Form: https://getbootstrap.com/docs/4.0/components/forms/
* Dropdown menu: https://www.youtube.com/watch?v=L0uNai3XyKQ&t=679s&ab_channel=CleverTechie  
* Font Rajdghani: https://fonts.google.com/specimen/Rajdhani?query=raj&sidebar.open=true&selection.family=Rajdhani
* Font Lora: https://fonts.google.com/specimen/Lora?selection.family=Lora&sidebar.open=true&query=Lora*/ 

#### Further reading materials    
* Google calendar API tutorial: https://www.youtube.com/watch?v=zrLf4KMs71E&ab_channel=TheLifeOfADev
* Send email via form: https://www.youtube.com/watch?v=37tSrPc983s&ab_channel=DCodeMania
* https://www.justinmind.com/blog/single-page-vs-multi-page-websites-design-battle/
* https://getbootstrap.com/docs/4.0/utilities/display/
* https://www.w3schools.com/howto/howto_js_mobile_navbar.asp
* https://getbootstrap.com/docs/4.3/components/dropdowns/
* https://stackoverflow.com/questions/40267056/remove-spacing-between-cols
* https://stackoverflow.com/questions/18738712/how-do-i-add-spacing-between-columns-in-bootstrap
* https://www.w3schools.com/cssref/pr_grid-row-gap.asp
* https://stackoverflow.com/questions/30423892/bootstrap-gap-between-columns-on-mobile-display/30424015
* https://www.w3schools.com/bootstrap4/bootstrap_utilities.asp
* https://stackoverflow.com/questions/35532682/move-bootstrap-column-up
* https://getbootstrap.com/docs/4.5/examples/
* https://www.youtube.com/watch?v=oRLB3HKr9l4&ab_channel=CodingTheSmartWay.com
* https://getbootstrap.com/docs/4.0/utilities/position/
* https://getbootstrap.com/docs/4.5/layout/overview/
* https://getbootstrap.com/docs/4.0/content/images/
* https://getbootstrap.com/docs/4.2/utilities/text/
* https://profromgo.com/blog/google-calendar-responsive/
* https://stackoverflow.com/questions/30830733/how-to-change-google-calendar-embed-event-color/
* https://fullcalendar.io/docs/google-calendar
* https://getbootstrap.com/docs/4.5/content/tables/#examples
* https://getbootstrap.com/docs/4.0/components/buttons/
* https://getbootstrap.com/docs/3.4/css    

### Technologies used 
=======================   
* *HTML*  I used HTML as it is the language used to structure and execute webcontent.
* *CSS* I used CSS to style and customise the website.
* *Google Fonts* I used Google Fonts to stylise my fonts, pulling from a large collection of fonts that can be accessed anywhere.
* *Bootstrap* [Bootstrap](https://getbootstrap.com/) is a framework on which mobile first websites cant be built. I chose to use Bootstrap as I was unfamiliar with it and I saw the opportunity to gain experience and practise making a website with it. 
* *JQuery* I used [JQuery](https://jquery.com/) to facilitate the dropdown menu and fonts imported from Goolge Fonts.    

### Deployment     
===============     
To deploy my project I carried out the following procedure:
* Logged into GitHub and selected the lornajane92/CuteCakesByBronaghMS1 project.
* From the next page I selected the Settings menu, located beneath the project title.
* From the side bar I selected the Options tab and scrolled down to the GidHub Pages section.
* In the Source area I set the Branch drop down menu from None to Main.
* I then set the Folder menu to Root and clicked save.
* The site then deployed my project at the following link (https://lornajane92.github.io/CuteCakesByBronaghMS1/)     

#### Running this project locally     
To run this project locally carry out the following procedure:      
* Log into GitHub and locate the file lornajane92/CuteCakesByBronaghMS1 from my repositories.
* Beside the green GitPod button, select the Code drop down menu.
* From this menu copy the HTTPS link to my project to clone it.
* On your computer open your local IDE/ Git Bash.
* Change your working directory to wherever you would like to store the project. 
* Paste the HTTPS link and press enter.

### Testing
=============   

*Manual*    

I carried out a manual test to ensure all links lead to their desired location, that the "active" class was applied to the 
correct nav items, that dropdown menus worked and that all content was visable.   
*Browser*     

I opened the project in Chrome and Edge to verify that the fomat remained constant and that there were no cross browser
glitches. I then carried out the same proceedure as I had done for the manual testing.    

*Lighthouse*    

I carried out testing via the Lighthouse application provided in Chrome, I did not get percentages as highly as I would have liked
especially with regards to the "alt" descriptions, under the current circumstances I do not have the time to fill this in.     

*HTML Validator(https://validator.w3.org)*     

The validator found the following issues:
* Two cases of an image missing an alt attribute.
* Two cases of a stray <img> tag in my code.
* The frameborder attribute within the <iframe> calander tag was marked "0", this was not necessary to include.
  unfortunately, due to time restraints I did not have the time to rectify these errors.     

*CSS Validator(https://jigsaw.w3.org/css-validator/)*      
The validator found the following issues:
* "Property text-decoration-skip-ink doesn't exist: none"
* "Property overflow-anchor doesn't exist: none"
* "Padding-top: -10px; negative values are not allowed"
* Height too many values or values are not allowed 50%"
* Width too many values or values are not recognized 90%"
* Cross Device- I deployed the project and opened it on my mobile phone. I ensured the layout was consistent with the browser layout and I carried out a repeat
  manual test on the device.

