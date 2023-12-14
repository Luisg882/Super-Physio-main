# SuperPhysio


SuperPhysio is a physiotherapy practice web page where potential and already existing patients can get reliable information about the practice.


In this website the patients can find the different services provided, the opening times, information on how the therapy sessions works and the patients are able to make a request to book an appointment.


All this information is divided in three different pages:
-Home.
-Services and Prices.
-Book Now.



![picture of a laptop, table, mobile and computer monitor showing SuperPhysio page](/assets/images/responsive.jpg)




## Features


- **Navigation**


    - Is on the top of the page, it shows the logo and name of the practice on the left side of the screen.
    - On the left side of the screen are the links that links to the different pages Home, Services and pricing and Book Now.
    - In phone devices the links are waped in a menu button. Wen is cliked it displays the links on the left side underneath the logo and name of the practice.



![navigation bar on tablets and desktop devices, navigation bar in mobiles with the menu button and navigation bar displaying the options after being clicked](/assets/images/navigation.jpg)




**Home**


- **Introduction**
    - In this section we make a breafe introduction of the specialization of the practice so the patience will now exactlly the tipe of practice he is getting to.
    - A background image of a physiotherapist treating a patient giving a visual feed back of the treatment.



![background of a therapist treating a knee and a green box in the meddle with the introduction of the consultory](/assets/images/introduction.jpg)




- **Pain section**

    - This section is made to give a brefe description on what is pain and explain how is treated by the therapist.
    - The intention is give a the user a road map on how is going to be the treatment of his injuty starting by releaving the pain.
    - the discription if follow by a image of a man with back pain, that is one of the most frequent reason consult a physiotherapist.


![explanation of what the pain is and how is going to be treated on the practice follow by a image of a man with back pain](/assets/images/pain-section.jpg)




- **Footer**
    - The footer includes the Opening times so the patient have an idea of when they can Book the session.
    - It has links to social media and will open in a new tab. This is made to engage the patient in the practice.


![image of the footer with the opening times and the logos of the different social media pages](/assets/images/footer.jpg)




- **Therapeutic exercise
    - In this section we make a description on what is the therapeutic exercise.
    - We make a enphasis in defiriancete it from the tipical gym work out because the patients tend to decline the service thinking that they are going to make hard work.
    - The image was chosed to demostrate the kind of exercise that is going to be made.
    - This section works as a follow up of the pain section showing the next step after reliaving the pain.


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




- **Book now**
    - This page allows the patient to book a session, allowing specify the kind session that will be. There is the option to make a breafe description of the reason for the session so the physioterapist can prepare for the session. The pattien will be asked for full name, email, mobile number and the date wen he wants to be the session.


![image of the Booking page](/assets/images/booking-page.png)




### Features Left to implement ###
- Block the booking for days and times where the practice is close.
- Create a user interface where the physiotherapy can upload all the documentation from the diagnostic, different test and the patient progression.
- A news section.
- I attemp to create a list with the different patologies that we treath. I try to be a single list on mobile devices and then split in 2 different for tablets and monitors but it gives accessibility problems and there was bugs on the implementation.


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

Live link [SuoerPhysio](https://luisg882.github.io/Super-Physio-main/index.html).
