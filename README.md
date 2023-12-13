# SuperPhysio


SuperPhysio is a physiotherapy practice web page where potential and already existing patients can get reliable information about the practice.


In this website the patients can find the different services provided, the opening times, information on how the therapy sessions works and the patients are able to make a request to book an appointment.


All this information is divided in three different pages:
- Home.
- Services and Prices.
- Book Now.






![picture of a laptop, table, mobile and computer monitor showing SuperPhysio page](/assets/images/responsive.jpg)




## Features


- **Navigation**


    - Is on the top of the page, it shows the logo and name of the practice on the left side of the screen.
    - On the right side of the screen are the links to the different pages Home, Services and pricing and Book Now.
    - In phone devices the links are wrapped in a menu button. Wen is clicked it displays the links on the left side underneath the logo and name of the practice.






![navigation bar on tablets and desktop devices, navigation bar in mobiles with the menu button and navigation bar displaying the options after being clicked](/assets/images/navigation.jpg)




**Home**


- **Introduction**
    - In this section we make a brief introduction about the specialisation of the practice so the patience will know exactly the type of practice he is getting to.
    - A background image of a physiotherapist treating a patient gives a visual feedback of the treatment.






![background of a therapist treating a knee and a green box in the meddle with the introduction of the consultory](/assets/images/introduction.jpg)




- **Pain section**


    - This section is made to give a brief description on what pain is and explain how is treated by the therapist.
    - The intention is to give the user a road map on how is going to be the treatment of his injury, starting by relieving the pain.
    - The description is followed by an image of a man with back pain, that is one of the most frequent reasons to consult a physiotherapist.




![explanation of what the pain is and how is going to be treated on the practice follow by a image of a man with back pain](/assets/images/pain-section.jpg)




- **Footer**
    - The footer includes the Opening times so the patient have an idea of when they can Book the session.
    - It has links to social media and will open in a new tab. This is made to engage the patient in the practice.


![image of the footer with the opening times and the logos of the different social media pages](/assets/images/footer.jpg)




- **Therapeutic exercise
    - In this section we make a description on what is the therapeutic exercise.
    - We make a emphasis in differentiate it from the typical gym workout because patients tend to decline the service thinking that they are going to make hard work.
    - The image was chosen to demonstrate the kind of exercise that is going to be made.
    - This section works as a follow up of the pain section showing the next step after relieving the pain.




![explanation of what the pain is and how is going to be treated on the practice follow by a image of a physiotherapist guiding a elderly patient on how to perform an exercise](/assets/images/texercise.jpg)




- ** Services and pricing **
    - This page describes all the services that the practice make and the prices
    - There 3 different services:
        - Diagnostic.
        - Physiotherapy session.
        - Therapeutic exercise.
    - The Diagnostic and Physiotherapy sessions are booked individually but the Therapeutic exercise have 3 different plans of 5, 10 or 15 sessions.
    - A table for the price of the therapeutic exercise was made to make it easier for the patients to understand.
    - Image of a physiotherapy session was added for visual feedback.




![image of the services and pricing page](/assets/images/services-and-pricing.jpg)




- ** Book now **
    - This page allows the patient to book a session, allowing them to specify the kind of session they want. There is the option to make a brief description of the reason for the session so the physiotherapist can prepare for it. The patient will be asked for a full name, email, mobile number and the date when he wants to be in the session.




![image of the Booking page](/assets/images/booking-page.png)




### Features Left to implement ###
- Block the booking for days and times where the practice is close.
- Create a user interface where the physiotherapy can upload all the documentation from the diagnostic, different test and the patient progression.
- A news section.
- I attempt to create a list with the different pathologies that we treat. I try to make a single list on mobile devices and then split in 2 different ones for tablets and monitors but it gives accessibility problems and there are bugs in the implementation.




## Testing ##
- Tested in Google Chrome, Firefox, Edge.
- The web site is responsive in all the browsers.
- Links for social media open correctly on different tabs.
- The booking validation works and retrive the relevant information to the back end.
- Navigation links work properly.


### Bugs ###


*** Solved bugs ***
- Css weren't targeting the nav toggle check making it appear on the screen. The id name on the html was changed to nav-togle-label instead of nav-toggle. Change the name on the HTML documents to nav-toggle
- Originally the submit button was in the centre of the form but when the size changes on the screen it goes out of the centre.
- Try to centre it giving values of vw for the margin on the left but it didn't work in all sizes.
- I decided to leave the button on the left side of the form and increase the size.


*** Validator Testing ***
- *** HTML ***
    - No errors were found on the W3C validator.
- *** CSS ***
    - No errors found in W3C (Jigsaw) validator
- *** Accessibility ***
    - Perform a light house test on all the pages
        - Home.
        [lighthouse Home page result: 97 performance, 100 accessibility, 95 best practices, 80 search engine optimization](/assets/images/lighthouse-home.jpg)
        - Services and price.
        [lighthouse Services and price page result: 92 performance, 98 accessibility, 95 best practices, 80 search engine optimization](/assets/images/lighthouse-services-and-prices.jpg)
        - Book now.
        [lighthouse Book now page result: 100 performance, 100 accessibility, 95 best practices, 80 search engine optimization](/assets/images/lighthouse-book-now.jpg)


### Unfixed Bugs ###


No unfixed bugs


## Deplayment ##
- The deployment was done on GitHub pages as follow:
    - Open the settings section on the repertory.
    - Click the option of pages on the left side bar.
    - Select the master branch in the source section.


Live link [SuperPhysio](https://luisg882.github.io/Super-Physio-main/index.html).

## Credits ##
- The css basic struture and footer of the page were taken from (Love running)[https://luisg882.github.io/Love-Run/]

## Media ##


- The image of the background for the Book now page comes from [Freepik](https://www.freepik.com/premium-photo/physiotherapist-giving-shoulder-therapy-woman_7875941.htm)
- Logo image [Adobe Stock](https://stock.adobe.com/search?k=%22spine+vector%22)
