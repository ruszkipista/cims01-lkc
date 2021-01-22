# Limerick Kettlebell Lifting Club

Static website to promote the [Limerick Kettlebell Club](https://www.facebook.com/Limerick-Kettlebell-Club-201978196542853) and [Kettlebell Sport](https://en.wikipedia.org/wiki/Kettlebell_lifting) around Limerick city, Ireland. This project is the first milestone in obtaining a [Full Stack Web Development](https://codeinstitute.net/full-stack-software-development-diploma/) diploma from [Code Institute](https://codeinstitute.net/)

![the webpage on different devices](./assets/doc/responsive-am-i.png "the webpage on different size devices")

### Attention assessor
I kept a journal during the development about my daily activities, see it [here](./assets/doc/ci-ms1-study-notes-journal.pdf) frozen in time or [live](https://docs.google.com/document/d/19ohtJUawBUjIifB0DIKjILhsNA2ryk4tIevXz4fkTWM/edit?usp=sharing).

## Contents
- [1. UX design](#1-ux-design "1. UX design")
  - [1.1 Strategy Plane](#11-strategy-plane "1.1 Strategy Plane")
  - [1.2 Scope plane](#12-scope-plane "1.2 Scope plane")
  - [1.3 Structure plane](#13-structure-plane "1.3 Structure plane")
  - [1.4 Skeleton plane](#14-skeleton-plane "1.4 Skeleton plane")
  - [1.5 Surface plane](#15-surface-plane "1.5 Surface plane")
- [2. Features Left to Implement](#2-features-left-to-implement "2. Features Left to Implement")
- [3. Technologies and Tools Used](#3-technologies-and-tools-used "3. Technologies and Tools Used")
- [4. Testing](#4-testing "4. Testing")
- [5. Deployment](#5-deployment "5. Deployment")
- [6. Credits](#6-credits "6. Credits")

## 1. UX design
### 1.1 Strategy Plane
Stakeholders of the website:
- visitor - a person visiting the website, not a club member
- member - club member, who actively trains or trained with the club
- officer - affiliated with the club who executes or organises club matters though official capacity
- AIKLF - sport organization which the club is associated with

#### 1.1.1 Goals and Objectives of Stakeholders (users)
|G#|User|Goals, Needs, Objectives|
|--|----|------------------------|
|G1|AIKLF|member organizations feature their affiliation with national (AIKLF) and world organization (IUKL) in info materials|
|G2|officer|provide adequate, easy access training facilities with certified instructors at fair price in popular day/week times|
|G3|officer|increase number of active members by attracting new members and retaining current members|
|G4|officer|organise workshops for the public and other gym trainers|
|G5|officer|promote the club via members’ social networks|
|G6|officer|make available club documents, rules, photos and forms|
|G7|officer|present an attractive image of the club to the public|
|G8|officer|inform about out of ordinary events (e.g. competition results, upcoming events, closure, etc.)|
|G9|officer|send out low cost instant delivery periodicals and notifications to individuals who signed up for it|
|G10|officer|facilitate calendar where members can sign up to events or cancel the same|
|G11|officer|inform about the history of Kettlebell and Kettlebell Sport|
|G12|visitor|find training community which caters for my particulars and interests (gender, age, experience level, dedication to training)|
|G13|visitor|learn about training related questions of what, why, how, who, when, where|
|G14|visitor|learn about venue facilities: reception, change room, locker, parking, price, discount|
|G15|visitor|learn about tools used for training|
|G16|visitor|learn what to expect on the first training|
|G17|officer|make available template training plans|
|G18|member|our heroes: get information about club related competition results|
|G19|officer|increase our authority on the subject in the eyes of the visitors|

### 1.2 Scope plane
It has been decided to create a static website. In light of that decision we do not go forward with
- G5: this goal would be for presence on a social network site, not for a homepage,
- G10: the calendar functionality would require database and programming, therefore ot of scope for now,
- G17: at the moment could not obtain these training plans

The following table lists the planned features, each feature referenced with original goal(s):

|F#|Goal|Feature|
|--|----|-------|
|F1|G3|build a custom static website with responsive pages for mobile, tablet and desktop|
|F2||have navigation bar on each pages|
|F3|G1, G19|display LKC’s logo and name, display club’s affiliation with AIKLF and IUKL with logo, name and link, provide description about each|
|F4|G16|provide description about how to prepare, what to bring, what to expect on the first training|
|F5|G7, G12|display attractive photos and texts, member testimonials|
|F6|G13, G19|describe what we do|
|F7|G13|describe why we train|
|F8|G13, G19|describe how: training methods|
|F9|G13, G19|describe who we are, how to contact us|
|F10|G13|inform about training times|
|F11|G13|describe where we train including venue facilities|
|F12|G8|present news articles|
|F13|G8, G9, G18|sign up to newsletter (email)|
|F14|G6, G16|ask Medical Form to be filled|
|F15|G3|allow first time applicant to announce self for training, so coach is notified, can learn more beforehand, this way improving first time experience|
|F16|G3, G6, G14|explain membership|
|F20|G10|display an event/training calendar, allow members to sign up/off|

### 1.3 Structure plane
The structure of the website to be built consist of
- a **Home** page with short leads - all pointing to longer descriptions on the About page,
- a long **About** page receiving traffic from the landing page with many sections with bookmark navigation, end of all sections refer back to **Home** with link
- a **SignUp** page to sign up to receive emails
- a picture **Gallery** page about training, meetups, competitions
- a **News** page related to club events
- a **TryOut** page with every important to know for the first training
- a **Mission** (statement) page
- a **Constitution** page

![pages with navigation links](./assets/doc/ci-ms1-site-structure.jpg "Website structure")

### 1.4 Skeleton plane
Feature list in page/section structure with content hinting and navigation links. The following table is a sample, describes the page **TryOut**. Check out the whole list [here](ci-ms1-features.pdf) in PDF format.

|Page / *section*|Feature#|Feature / Content description|Link or Action|
|--------------|--------|-----------------------------|--------------|
|**TryOut**|F4|come to your first free training||
|*navbar*|F2|*same as on Home*||
||F4|all you need to know for the first occasion: clothes, footwear, water, eating, attention from coach (first line - last line)|https://www.youtube.com/watch?v=cKx8xE8jJZs|
||F4|- coach led, instructed exercises with kettlebell or bodyweight,<br>- everybody is doing the same, but varied to strength level and experience,<br>- length, composition of training,<br>- new joiners get more attention to ramp up their skills,<br>- coach gives out correction instructions to individuals to improve form,<br>- number of attendees are not limited, enabled by the size of the court||
||F14|If you can, download, print, fill, sign Medical Self Assessment|file `MedicalSelfAssessment`|
||F15|Give us a heads up:<br>Form: name /email / telephone / about yourself + Submit button|Send email to coach|


### 1.5 Surface plane
Used the website coolors.co to come up with base colors for styling:
![base colors](./assets/doc/color-palette.gif "Base colors")
Also decided that for secondary colors will use kettlebell weight color codes. See this image for sample of those colors:
![secondary colors](./assets/doc/competition-kettlebell-lineup.png "Secondary colors")
Choose font [Roboto](https://fonts.google.com/specimen/Roboto) for the headers.

## 2. Features Left to Implement
- **Gallery** page - Show images/videos about trainings, competitions and meet-ups
- **SignUp** page - Let visitors sign up with email address for newsletter
- **News** page - collection of news items in date descending order, 2 of the news articles goes on the **Home** page into `news` section
- store news articles in database, automatically fill **News** page with them, enable news article editing to authorized users
- send a selected group of articles in email to subscribers
- create **Calendar** page of actual month, add reference date field to news articles, fill calendar page with news titles which have reference date in given month

## 3. Technologies and Tools Used

- The project's product (the website) was written in HTML and CSS, utilising [Bootstrap](https://getbootstrap.com/docs/5.0/) framework (which itself uses CSS and JavaScript). Bootstrap is used for its responsive utilities. There is a petite JavaScript in `index.html` to solve a specific issue.
- The images were manipulated with program [Paint.NET](https://www.getpaint.net/). Mainly used for cropping, resizing, background removal and format conversion.
- Created wireframes with program from [balsamiq](https://balsamiq.com/wireframes/)
- Written study notes and collected textual content on [Google Docs](https://docs.google.com/)
- The code was edited with [Visual Studio Code](https://code.visualstudio.com/), the preview was provided via [Live Server](https://github.com/ritwickdey/vscode-live-server) VS Code extension.
- The code versions were managed with [Git](https://git-scm.com/downloads)
- The code and project deliverables are stored on cloud service [Github](https://github.com/) repository with versions.
- The website is deployed on [GitHub Pages](https://pages.github.com/)
- The development machine runs [Windows 7](https://www.microsoft.com/en-us/software-download/windows7) operating system.
- The website was tested on desktop on [Chrome](https://www.google.com/intl/en_ie/chrome/) and [Firefox](https://www.mozilla.org/en-US/firefox/) web browsers, also on a [OnePlus2](https://www.oneplus.com/ie/support/spec/oneplus-2) mobile phone running [Android](https://www.android.com/) and mobile [Chrome](https://play.google.com/store/apps/details?id=com.android.chrome&hl=en) browser.
- Generated favicons with [Favicon & App Icon Generator](https://www.favicon-generator.org/)
- Played with colors on [coolors](https://coolors.co/), choose the base colors with it
- Choose font using [Google Fonts](https://fonts.google.com/)
- Searched the internet to find content, documentation and solution for issues using [Google](www.google.com)'s search service.
- connected to the internet using [Vodafone](https://n.vodafone.ie/shop/broadband.html)'s broadband service.

## 4. Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## 5. Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## 6. Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X