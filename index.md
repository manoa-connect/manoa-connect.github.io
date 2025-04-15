<img src="img/assets/manoa-connect_logo-text_dark.png" width="100%" style="margin-left: auto; margin-right: auto; display: block; padding-bottom: 5%; padding-top: 2%">

## **Table of contents**
* [Overview](#overview)
* [Team](#team-and-roles)
* [Deployment](#deployment)
* [Page List](#page-list)
* [Mockups](#mockups)
* [Development Timeline](#development-timeline)



## **Overview**
To facilitate student connection, we introduce **Manoa Connect**, a social networking website that applies matching functionalities reminiscent of dating apps (_Tinder_, _Hinge_, etc.) but in the context of finding friends on the UH Manoa campus.



### **Motivation**
* Despite 20,000 students on the UH Manoa campus, some students have a hard time making friends outside of their (ongoing/previous) classes or majors
  * Difficulties being in a foreign environment (_i.e. incoming freshmen, sophomores, exchange students_)
  * Difficulty breaking into established social groups (_i.e. juniors/seniors_)
* Some students lack time to commit to social events
* Certain people may be socially inexperience/have an introverted nature
* Pandemic times may have shifted cultural norms on offline socialization (_i.e. people may prefer socializing online more now_)



### **Goal**
Our "Big Picture" vision is to develop a thriving social platform distinct to members of UH Manoa (specifically students). Our ideal outcomes for students include:

* Developing friendships with people from different majors at UH Manoa provide new perspectives
* New career/networking opportunities can arise from students in different fields of study
* Learning how to socialize with people who have unique backgrounds nurtures social skills applicable throughout life



## **Team and Roles**
Manoa Connect is designed, implemented, and maintained by [Codie Nakamura](http://codie-n.github.io/), [Chaezen-Lee Pebria](https://chaezenp.github.io/), [Masaki Sakai](https://masaki-sk.github.io/), and [Aaron Ramos](https://aar0m.github.io/).

**Formal Team Contract**: Our formal contract with agreements and criteria can be found [here](https://docs.google.com/document/d/1HFMJAH2i93QQrADcZRahhympfoDfzt7imEc7af-ks4g/edit?usp=sharing).

**Chaezen Pebria - Page Specialist**\
_Develops design for certain pages and page-specific features._\
\- “Matching/Connect” page\
\- Settings page

**Masaki Sakai - Page Specialist**\
_Develops design for certain pages and page-specific features._\
\- Friends page\
\- Chat page

**Codie Nakamura - Project Manager, Page Specialist**\
_Tracks team actions on GitHub; develops design for pages and specific features._\
\- GitHub\
\- User home page\
\- User profile

**Aaron Ramos - Project Manager, Gopher**\
_Coordinate team and project direction; help others with design/code/testing._\
\- Landing page\
\- Login/Signup page\
\- Graphics

## **Tools and Organization**
**Meeting Time:** Sunday 6PM Discord + Tuesday in-class

**Discord Text Channels**\
\- Communication\
\- Links --- _important documents/links (i.e. proposal, sheets tracking, GitHub)_\
\- Assets --- _Preliminary assets for everyone to review and look at_

**Final Presentation:** [Google Slides](https://docs.google.com/presentation/d/1SNOkvmU1mH7Ymwontio2Z7-_S7rfsOa7PxnWv8czc8g/edit?usp=sharing)



# **Deployment**
Manoa Connect uses PostgreSQL, NextJS, and is deployed on Vercel. To visit the website, click [here](https://manoa-connect-app.vercel.app/).



## **Page List**
This section provides a set of pages for Manoa Connect that will be implemented.

* [Landing page](#landing-page)
* [Login/signup page](#loginsignup)
* [User home page](#user-home-page)
* [User profile page](#user-profile-page)
* [“Matching/Connect” page](#matchingconnect-page)
* [Friends list and chat page](#friends-list-and-chat-page)
* [Settings page](#settings-page)

**User Profile:** Add/edit name, photo(s), major, likes/interests, list of (previous/current) classes, dorm/commuter/other status, clubs, MBTI

**Matching/Connect:** Random person pops up and users have the option of “match” or “skip” with two buttons

**Friends:** _(Now combined with chat)_ Add freinds to a favorites/block list that can also be accessed; this page also includes the feature to delete friends

**Chat:** _(Now combined with friends)_ List of chats with people matched and a selected chat page that allows for message functioning

**Settings:** Settings to filter people shown (i.e. by major, interests, etc.)

## **Mockups**

### **Landing Page**
- Links to join now page

<img src="img/m1-progress/landing-page1.png" width="75%" style="margin-left: auto; margin-right: auto; display: block;">

<img src="img/m1-progress/landing-page2.png" width="75%" style="margin-left: auto; margin-right: auto; display: block;">

### **Login/Signup**

<img src="img/m1/signup.png" width="75%" style="margin-left: auto; margin-right: auto; display: block;">

<img src="img/m1/login.png" width="75%" style="margin-left: auto; margin-right: auto; display: block;">

### **User Home Page**
- New messages box will be a button leading to the chat page
- There is second connect button (besides the one in the navbar) to go to the matching page

<img src="img/m1-progress/user-home.png" width="75%" style="margin-left: auto; margin-right: auto; display: block;">

### **User Profile Page**
- **Dropdown:** Major, Year, Commuter status, MBTI
- **Textboxes:** List of current and previous classes, clubs, likes/interests
- Scroll down to upload/edit photos

<img src="img/m1-progress/card-back.png" width="75%" style="margin-left: auto; margin-right: auto; display: block;">

<img src="img/m1-progress/card-front.png" width="75%" style="margin-left: auto; margin-right: auto; display: block;">

### **“Matching/Connect” Page**
- Manoa ID-inspired layout (flips from front to back on button press)
- Contact object
  - Name
  -  Photo(s) - _limit to 3_
  -  Major
  -  Likes/interests
  -  List of (previous/current) classes
  -  Dorm/commuter/other status
  -  Extracurricular clubs
  -  MBTI

<img src="img/m1/connect-front.png" width="75%" style="margin-left: auto; margin-right: auto; display: block;">

<img src="img/m1/connect-back.png" width="75%" style="margin-left: auto; margin-right: auto; display: block;">

### **Settings Page**
- Access from profile page/dropdown from top right corner
- Scrollable 
- Test 
- Mostly dropdowns
- Some text boxes

<img src="img/m1/settings.png" width="75%" style="margin-left: auto; margin-right: auto; display: block;">

### **Friends List and Chat Page**
- Chat implemented using note and timestamp function
- Last conversation is the order of list
- Sort the chat box by the most recent conversation
- Default page is blank, just contacts
  - Clicking on the icon box will open the chat box
- Deleting is like blocking because we will not reconnect the same people again
  - It shows caution window to delete someone

<img src="img/m1/chat-default.png" width="75%" style="margin-left: auto; margin-right: auto; display: block;">

<img src="img/m1/chat-clicked.png" width="75%" style="margin-left: auto; margin-right: auto; display: block;">



## **Development Timeline**
- [Milestone 1](#milestone-1-m1)
- [Milestone 2](#milestone-2-m2)
- [Milestone 3](#milestone-3-m3)

### **Milestone 1 (M1)**

<img src="img/repo/milestone1.png" width="90%" style="margin-left: auto; margin-right: auto; display: block; padding-bottom: 2%;">

[Link](https://github.com/orgs/manoa-connect/projects/1/views/1) to the GitHub project view for Milestone 1.

- Completed landing Page
- Templates mockups of other pages in NextJS
- Setup GitHub issues and GitHub project
- Project home page

### **Milestone 2 (M2)**

<img src="img/repo/milestone2.png" width="90%" style="margin-left: auto; margin-right: auto; display: block; padding-bottom: 2%;">

[Link](https://github.com/orgs/manoa-connect/projects/2) to the GitHub project view for Milestone 2.

- Configure and test database for 'Friends' object
- Complete account creation process
- Test 1 account
- Continue refining incompleted pages

### **Milestone 3 (M3)**
_TBA_
