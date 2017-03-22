# Measuring the Development of an Open Source Contributor
### Open Innovation (Open Source Student Clubs)

## Personal Details
- Name: Rajat Patwa
- Email: razat249@gmail.com
- Github: https://github.com/razat249
- LinkedIn: https://www.linkedin.com/in/rajatpatwa/ 
- Telephone: +917597305718
- Country of residence: India
- Timezone: GMT/UTC +05:30
- Primary language: English, Hindi

## Project Proposal
**Overview**: I am applying to the project “Measuring the development of an open source contributor”. This project aims at developing a tool which will help in measuring both the impact of an individual in open source projects and also, how being involved in open source, impacts a contributors life. Goals of this project are:
- A user is visiting the tool/website where he/she is able to track activities (commits, pull requests, issues) between a set of users.
- The user can also track the repositories, these users have been contributing at over time. 
- The tool will have to fetch the user's' repositories on its own using the github APIs.
- The username will be the input to the tool and different visualizations related to the user will be the output.

**Flow Diagram**: The flow diagram of how the tool will work is given below.


Mock Ups: I have created some mock ups below for the tool.
In the below mockup a user can search other users in the search sidebar (here we will use the github search API).
After searching a user, we can analyse all his activities in the right window.
Dropdown, just above the chart in the right side, will be used for visualizing all contributions, commits, pull requests or issues opened/closed by particular user (here we will use the github commits, pull requests and issues APIs for visualizing charts).
Dropdown just above chart in the left will be used to for changing visualization.
I think we can also use a pi chart to show different activities related to student.
We should also brainstorm about what other visualizations we can use.



APIs to Use: I have researched, what all github APIs we need, to pull up this project. I am listing some APIs below.
Github search API - https://developer.github.com/v3/search/: For implementing search feature for searching different users.
Github users API - https://developer.github.com/v3/users/: For fetching user’s data.
Github commits API - https://developer.github.com/v3/repos/commits/: For implementing the chart/board of commits.
Github pull requests API - https://developer.github.com/v3/pulls/#list-pull-requests: For implementing the charts/boards of pull requests made by a user.
Github issues API - https://developer.github.com/v3/issues/#list-issues: For listing all the issues by a particular user.
Other Github APIs which we need in the project: 
Events API:  https://developer.github.com/v3/activity/events/
Activity API: https://developer.github.com/v3/activity/ etc.

Technologies: I am thinking to do this project using ReactJS library. I am choosing this library because React is very good for state managements and complex UIs, as we have different graphs on the screen, the UI will be pretty much complex. 
I have done some projects on ReactJs, So I can easily pick the ReactJS library.
For graphs/charts I think D3 will be great. 
I have found a react implementation of D3 react-calendar-heatmap here https://www.npmjs.com/package/react-calendar-heatmap 

Project and Beyond: I am also interested in working with the other parts of this project, like backend, designing and brainstorming the whole system and other UI/UX stuff which are beyond the scope of GSoC. I want to learn as much as I can and this project will give me a chance to learn and grow myself to become a better engineer.

Schedule of Deliverables and Timeline 
This week-by-week timeline provides a rough guideline of how the project will be done.

May 5 - May 30, 2017 -- Community Bonding Period
Further discuss the activity ideas with the mentor.
Discuss all the design, flow diagrams, working and mockups of the tool. 
Discuss what technologies, frameworks, testing library and APIs to use for this project.
Discuss all the types of visualizations to use like calendar-heatmap, pie charts etc.
Discuss how to manage the different activities and their visualization on the screen.
Setting up the development environment.
Study and make all the system design related brainstorming.

May 30, 2017 - June 30, 2017 -- Start Working on the Project
Start coding.
Designing the high fidelity UI/UX designs for implementation.
Divide the project into several components as given below:
User search sidebar component - projecting to do in 3 - 5 days before 5th of June. Using Github user search API.
Write unit test cases for the user search component - projecting to do it before 10th of June.
Different visualization components - like calendar-heatmap, pie charts, line charts etc. Projecting to do it before 15th of June.
Unit test cases for visualization components - projecting to do it before 20th June.
Integration and testing of the above components and document the work - projecting before 25th June.

June 26, 2017 - June 30, 2017 -- First Evaluations
Submit the user search component and visualization components with their unit tests and documentation.

July 1 - July 24, 2017 -- Continue Coding
Individual user repositories component and its unit testing - projecting before 7th of July.
Other components and features that will come on that time - projecting before 20th July.
Integration and document the code.

July 24, 2017 - July 28, 2017 -- Second Evaluations
Submit the whole integrated app for evolution.

July 28, 2017 - August 21, 2017 -- Final Coding Period
User level rigorous testing.
Reporting the bugs and solve them.
Code refactor and documentation.
Brainstorming the upcoming features and challenges in the tool.
Improving the UI/UX and performance of the tool.
Discussion of other related work beyond GSoC.

August 21 - 29, 2017 -- Final Submission and Evaluations
Final release.
Final debugging, documentation.

The timeline is a tentative timeline of the project. The timeline can be modified according to the project features and requirement changes. I can devote 6 - 8 hours daily at the time of working. I don’t have any other commitments other than this.
Work/Internship Experience
Software Engineer, Intern @ Advanced Structures India, Bangalore, India 
(Dec 2016 - March 2017) : 
Designed and implemented the front-end part of an app called teardown. 
App is used to save all the details of each part of the car. 
and maintains the hierarchy of the parts with a logical nomenclature of parts according to the hierarchy. 
Technologies: AngularJS, Django, AWS.
Implemented a noise/vibration/effort comparison tool. 
This tool uses line charts for visualization of the millions of points.
and compare noise, vibration and effort data of a car and multiple cars.
Technologies: AngularJS, D3.js, Django, AWS, Dygraphs.

Software Engineering Intern @ CauseCode Technologies Pvt Ltd, Pune, India
(May 2016 - July 2016) :
Designed and Implemented job board plugin for company's corporate site https://causecode.com. The plugin can be used to create, read, update and delete job posts. The server side of the plugin is built using groovy on grails. And the front end is built using Angular. The plugin follows REST API architecture. In this project, I got to learn insights of Grails and AngularJS.
Ported homepage and blog page of company's corporate site from AngularJS to ReactJS. Here the front end is ported following the react-redux architecture. In this project, I learned about design patterns used to build the react-redux app.
Implemented social share buttons for company's blog and Google ReCaptcha API for CRM plugin.

Open Source Development and Project Experience
Cmeue (Project Campus Meetup) - https://github.com/cmeue/cmeue: 
Project campus meetup or “Cmeue” aims at developing a web application which will help to connect different year students. 
The main objective of this application is to connect junior students with seniors and alumni.
Junior students can search the seniors and alumni based on linkedIn skills and request them for help/advice. 
ECB SAC - https://github.com/ECB-Bikaner/ecb-sac: 
Built a web app for student's affairs council of my college. 
This app connects students to the events in the college. 
Society/club coordinators can post an event. 
Students can participate in the events and can discuss it on the event info page. 
You can find it running here -- https://ecbsac.org.
Technologies: AngularJS (front-end), Firebase (backend), Auth0 API (authentication), Discuss API (Discussion thread).
Academic Experience
I am a final year student pursuing my bachelor of technology (B-Tech) in Computer Science and Engineering at Govt. Engineering college Bikaner, Rajasthan Technical University, India. I have chosen this field of computer science because I like to build things and in this field there are endless possibilities to build something special.

I am enjoying this field (Computer Science) a lot. I have built a lot small and medium sized projects some of you can have a look here https://github.com/razat249. I have a good understanding of the front end languages and frameworks like ReactJS, AngularJS, Jasmine etc. Recently I am developing an app called “Coddraw”. This web app solves the problem of phone screen interview by providing a rich multi user text editor and a multi user drawing screen. The tool is free to use and there is no signin/signup required. An interviewer can use this tool to pair program with the interviewee with code and draw screen side by side. I am building this app using the ReactJs, Firebase and Node.js.  

I am open source enthusiast and working with the open source for about 2 years from now. I have working knowledge of languages like Python, JavaScript and frameworks like ReactJS, AngularJS, Jasmine etc.  I have contributed to the GSoC organization oppia and solved some of their issues. Also I have developed a course on python in a 2 man team on the oppia platform. These are the top rated courses on the oppia. You can find them here https://www.oppia.org/profile/razat249. 

Why Me
I will be right for this project because I have already started working on the dummy version of this project using the github APIs so that I can learn all the nuts of this project before we will start working on this project officially. You can find my dummy version of this tool here: https://github.com/razat249/Campus-Program/tree/dummy-github-view-tool. Also I have all the important characteristics to pull up this project bug free before time. I work on a time bound fashion which is very important on a hard deadline based projects. I create time logs for analysing myself for better performance and higher productivity.

You can have a look at the above sections on open source experience, academic experience and work/internship experience to know more about me. In my college, I have my own team. We try to work in a fashion such that we can learn as much as possible. In our recent ongoing project CampusMeetup I got to lead my team. I like to work in a process oriented manner so that I plan ahead.

Why Mozilla
There are several reasons I have chosen the Mozilla:
This Project is interesting and will give me a chance to learn a lot.
You guys are doing great work and I want to be a part of this good deed.
Working with mozilla is honourable for me.







Measuring the Development of an Open Source Contributor
Open Innovation (Open Source Student Clubs)

Personal Details
Name: Rajat Patwa
Email: razat249@gmail.com
Github: https://github.com/razat249
LinkedIn: https://www.linkedin.com/in/rajatpatwa/ 
Telephone: +917597305718
Country of residence: India
Timezone: GMT/UTC +05:30
Primary language: English, Hindi

Project Proposal
Overview: I am applying to the project “Measuring the development of an open source contributor”. This project aims at developing a tool which will help in measuring both the impact of an individual in open source projects and also, how being involved in open source, impacts a contributors life. Goals of this project are:
A user is visiting the tool/website where he/she is able to track activities (commits, pull requests, issues) between a set of users.
The user can also track the repositories, these users have been contributing at over time. 
The tool will have to fetch the user's' repositories on its own using the github APIs.
The username will be the input to the tool and different visualizations related to the user will be the output.
Flow Diagram: The flow diagram of how the tool will work is given below. 
Mock Ups: I have created some mock ups below for the tool.
In the below mockup a user can search other users in the search sidebar (here we will use the github search API).
After searching a user, we can analyse all his activities in the right window.
Dropdown, just above the chart in the right side, will be used for visualizing all contributions, commits, pull requests or issues opened/closed by particular user (here we will use the github commits, pull requests and issues APIs for visualizing charts).
Dropdown just above chart in the left will be used to for changing visualization.
I think we can also use a pi chart to show different activities related to student.
We should also brainstorm about what other visualizations we can use.



APIs to Use: I have researched, what all github APIs we need, to pull up this project. I am listing some APIs below.
Github search API - https://developer.github.com/v3/search/: For implementing search feature for searching different users.
Github users API - https://developer.github.com/v3/users/: For fetching user’s data.
Github commits API - https://developer.github.com/v3/repos/commits/: For implementing the chart/board of commits.
Github pull requests API - https://developer.github.com/v3/pulls/#list-pull-requests: For implementing the charts/boards of pull requests made by a user.
Github issues API - https://developer.github.com/v3/issues/#list-issues: For listing all the issues by a particular user.
Other Github APIs which we need in the project: 
Events API:  https://developer.github.com/v3/activity/events/
Activity API: https://developer.github.com/v3/activity/ etc.

Technologies: I am thinking to do this project using ReactJS library. I am choosing this library because React is very good for state managements and complex UIs, as we have different graphs on the screen, the UI will be pretty much complex. 
I have done some projects on ReactJs, So I can easily pick the ReactJS library.
For graphs/charts I think D3 will be great. 
I have found a react implementation of D3 react-calendar-heatmap here https://www.npmjs.com/package/react-calendar-heatmap 

Project and Beyond: I am also interested in working with the other parts of this project, like backend, designing and brainstorming the whole system and other UI/UX stuff which are beyond the scope of GSoC. I want to learn as much as I can and this project will give me a chance to learn and grow myself to become a better engineer.

Schedule of Deliverables and Timeline 
This week-by-week timeline provides a rough guideline of how the project will be done.

May 5 - May 30, 2017 -- Community Bonding Period
Further discuss the activity ideas with the mentor.
Discuss all the design, flow diagrams, working and mockups of the tool. 
Discuss what technologies, frameworks, testing library and APIs to use for this project.
Discuss all the types of visualizations to use like calendar-heatmap, pie charts etc.
Discuss how to manage the different activities and their visualization on the screen.
Setting up the development environment.
Study and make all the system design related brainstorming.

May 30, 2017 - June 30, 2017 -- Start Working on the Project
Start coding.
Designing the high fidelity UI/UX designs for implementation.
Divide the project into several components as given below:
User search sidebar component - projecting to do in 3 - 5 days before 5th of June. Using Github user search API.
Write unit test cases for the user search component - projecting to do it before 10th of June.
Different visualization components - like calendar-heatmap, pie charts, line charts etc. Projecting to do it before 15th of June.
Unit test cases for visualization components - projecting to do it before 20th June.
Integration and testing of the above components and document the work - projecting before 25th June.

June 26, 2017 - June 30, 2017 -- First Evaluations
Submit the user search component and visualization components with their unit tests and documentation.

July 1 - July 24, 2017 -- Continue Coding
Individual user repositories component and its unit testing - projecting before 7th of July.
Other components and features that will come on that time - projecting before 20th July.
Integration and document the code.

July 24, 2017 - July 28, 2017 -- Second Evaluations
Submit the whole integrated app for evolution.

July 28, 2017 - August 21, 2017 -- Final Coding Period
User level rigorous testing.
Reporting the bugs and solve them.
Code refactor and documentation.
Brainstorming the upcoming features and challenges in the tool.
Improving the UI/UX and performance of the tool.
Discussion of other related work beyond GSoC.

August 21 - 29, 2017 -- Final Submission and Evaluations
Final release.
Final debugging, documentation.

The timeline is a tentative timeline of the project. The timeline can be modified according to the project features and requirement changes. I can devote 6 - 8 hours daily at the time of working. I don’t have any other commitments other than this.
Work/Internship Experience
Software Engineer, Intern @ Advanced Structures India, Bangalore, India 
(Dec 2016 - March 2017) : 
Designed and implemented the front-end part of an app called teardown. 
App is used to save all the details of each part of the car. 
and maintains the hierarchy of the parts with a logical nomenclature of parts according to the hierarchy. 
Technologies: AngularJS, Django, AWS.
Implemented a noise/vibration/effort comparison tool. 
This tool uses line charts for visualization of the millions of points.
and compare noise, vibration and effort data of a car and multiple cars.
Technologies: AngularJS, D3.js, Django, AWS, Dygraphs.

Software Engineering Intern @ CauseCode Technologies Pvt Ltd, Pune, India
(May 2016 - July 2016) :
Designed and Implemented job board plugin for company's corporate site https://causecode.com. The plugin can be used to create, read, update and delete job posts. The server side of the plugin is built using groovy on grails. And the front end is built using Angular. The plugin follows REST API architecture. In this project, I got to learn insights of Grails and AngularJS.
Ported homepage and blog page of company's corporate site from AngularJS to ReactJS. Here the front end is ported following the react-redux architecture. In this project, I learned about design patterns used to build the react-redux app.
Implemented social share buttons for company's blog and Google ReCaptcha API for CRM plugin.

Open Source Development and Project Experience
Cmeue (Project Campus Meetup) - https://github.com/cmeue/cmeue: 
Project campus meetup or “Cmeue” aims at developing a web application which will help to connect different year students. 
The main objective of this application is to connect junior students with seniors and alumni.
Junior students can search the seniors and alumni based on linkedIn skills and request them for help/advice. 
ECB SAC - https://github.com/ECB-Bikaner/ecb-sac: 
Built a web app for student's affairs council of my college. 
This app connects students to the events in the college. 
Society/club coordinators can post an event. 
Students can participate in the events and can discuss it on the event info page. 
You can find it running here -- https://ecbsac.org.
Technologies: AngularJS (front-end), Firebase (backend), Auth0 API (authentication), Discuss API (Discussion thread).
Academic Experience
I am a final year student pursuing my bachelor of technology (B-Tech) in Computer Science and Engineering at Govt. Engineering college Bikaner, Rajasthan Technical University, India. I have chosen this field of computer science because I like to build things and in this field there are endless possibilities to build something special.

I am enjoying this field (Computer Science) a lot. I have built a lot small and medium sized projects some of you can have a look here https://github.com/razat249. I have a good understanding of the front end languages and frameworks like ReactJS, AngularJS, Jasmine etc. Recently I am developing an app called “Coddraw”. This web app solves the problem of phone screen interview by providing a rich multi user text editor and a multi user drawing screen. The tool is free to use and there is no signin/signup required. An interviewer can use this tool to pair program with the interviewee with code and draw screen side by side. I am building this app using the ReactJs, Firebase and Node.js.  

I am open source enthusiast and working with the open source for about 2 years from now. I have working knowledge of languages like Python, JavaScript and frameworks like ReactJS, AngularJS, Jasmine etc.  I have contributed to the GSoC organization oppia and solved some of their issues. Also I have developed a course on python in a 2 man team on the oppia platform. These are the top rated courses on the oppia. You can find them here https://www.oppia.org/profile/razat249. 

Why Me
I will be right for this project because I have already started working on the dummy version of this project using the github APIs so that I can learn all the nuts of this project before we will start working on this project officially. You can find my dummy version of this tool here: https://github.com/razat249/Campus-Program/tree/dummy-github-view-tool. Also I have all the important characteristics to pull up this project bug free before time. I work on a time bound fashion which is very important on a hard deadline based projects. I create time logs for analysing myself for better performance and higher productivity.

You can have a look at the above sections on open source experience, academic experience and work/internship experience to know more about me. In my college, I have my own team. We try to work in a fashion such that we can learn as much as possible. In our recent ongoing project CampusMeetup I got to lead my team. I like to work in a process oriented manner so that I plan ahead.

Why Mozilla
There are several reasons I have chosen the Mozilla:
This Project is interesting and will give me a chance to learn a lot.
You guys are doing great work and I want to be a part of this good deed.
Working with mozilla is honourable for me.







Measuring the Development of an Open Source Contributor
Open Innovation (Open Source Student Clubs)

Personal Details
Name: Rajat Patwa
Email: razat249@gmail.com
Github: https://github.com/razat249
LinkedIn: https://www.linkedin.com/in/rajatpatwa/ 
Telephone: +917597305718
Country of residence: India
Timezone: GMT/UTC +05:30
Primary language: English, Hindi

Project Proposal
Overview: I am applying to the project “Measuring the development of an open source contributor”. This project aims at developing a tool which will help in measuring both the impact of an individual in open source projects and also, how being involved in open source, impacts a contributors life. Goals of this project are:
A user is visiting the tool/website where he/she is able to track activities (commits, pull requests, issues) between a set of users.
The user can also track the repositories, these users have been contributing at over time. 
The tool will have to fetch the user's' repositories on its own using the github APIs.
The username will be the input to the tool and different visualizations related to the user will be the output.
Flow Diagram: The flow diagram of how the tool will work is given below. 
Mock Ups: I have created some mock ups below for the tool.
In the below mockup a user can search other users in the search sidebar (here we will use the github search API).
After searching a user, we can analyse all his activities in the right window.
Dropdown, just above the chart in the right side, will be used for visualizing all contributions, commits, pull requests or issues opened/closed by particular user (here we will use the github commits, pull requests and issues APIs for visualizing charts).
Dropdown just above chart in the left will be used to for changing visualization.
I think we can also use a pi chart to show different activities related to student.
We should also brainstorm about what other visualizations we can use.



APIs to Use: I have researched, what all github APIs we need, to pull up this project. I am listing some APIs below.
Github search API - https://developer.github.com/v3/search/: For implementing search feature for searching different users.
Github users API - https://developer.github.com/v3/users/: For fetching user’s data.
Github commits API - https://developer.github.com/v3/repos/commits/: For implementing the chart/board of commits.
Github pull requests API - https://developer.github.com/v3/pulls/#list-pull-requests: For implementing the charts/boards of pull requests made by a user.
Github issues API - https://developer.github.com/v3/issues/#list-issues: For listing all the issues by a particular user.
Other Github APIs which we need in the project: 
Events API:  https://developer.github.com/v3/activity/events/
Activity API: https://developer.github.com/v3/activity/ etc.

Technologies: I am thinking to do this project using ReactJS library. I am choosing this library because React is very good for state managements and complex UIs, as we have different graphs on the screen, the UI will be pretty much complex. 
I have done some projects on ReactJs, So I can easily pick the ReactJS library.
For graphs/charts I think D3 will be great. 
I have found a react implementation of D3 react-calendar-heatmap here https://www.npmjs.com/package/react-calendar-heatmap 

Project and Beyond: I am also interested in working with the other parts of this project, like backend, designing and brainstorming the whole system and other UI/UX stuff which are beyond the scope of GSoC. I want to learn as much as I can and this project will give me a chance to learn and grow myself to become a better engineer.

Schedule of Deliverables and Timeline 
This week-by-week timeline provides a rough guideline of how the project will be done.

May 5 - May 30, 2017 -- Community Bonding Period
Further discuss the activity ideas with the mentor.
Discuss all the design, flow diagrams, working and mockups of the tool. 
Discuss what technologies, frameworks, testing library and APIs to use for this project.
Discuss all the types of visualizations to use like calendar-heatmap, pie charts etc.
Discuss how to manage the different activities and their visualization on the screen.
Setting up the development environment.
Study and make all the system design related brainstorming.

May 30, 2017 - June 30, 2017 -- Start Working on the Project
Start coding.
Designing the high fidelity UI/UX designs for implementation.
Divide the project into several components as given below:
User search sidebar component - projecting to do in 3 - 5 days before 5th of June. Using Github user search API.
Write unit test cases for the user search component - projecting to do it before 10th of June.
Different visualization components - like calendar-heatmap, pie charts, line charts etc. Projecting to do it before 15th of June.
Unit test cases for visualization components - projecting to do it before 20th June.
Integration and testing of the above components and document the work - projecting before 25th June.

June 26, 2017 - June 30, 2017 -- First Evaluations
Submit the user search component and visualization components with their unit tests and documentation.

July 1 - July 24, 2017 -- Continue Coding
Individual user repositories component and its unit testing - projecting before 7th of July.
Other components and features that will come on that time - projecting before 20th July.
Integration and document the code.

July 24, 2017 - July 28, 2017 -- Second Evaluations
Submit the whole integrated app for evolution.

July 28, 2017 - August 21, 2017 -- Final Coding Period
User level rigorous testing.
Reporting the bugs and solve them.
Code refactor and documentation.
Brainstorming the upcoming features and challenges in the tool.
Improving the UI/UX and performance of the tool.
Discussion of other related work beyond GSoC.

August 21 - 29, 2017 -- Final Submission and Evaluations
Final release.
Final debugging, documentation.

The timeline is a tentative timeline of the project. The timeline can be modified according to the project features and requirement changes. I can devote 6 - 8 hours daily at the time of working. I don’t have any other commitments other than this.
Work/Internship Experience
Software Engineer, Intern @ Advanced Structures India, Bangalore, India 
(Dec 2016 - March 2017) : 
Designed and implemented the front-end part of an app called teardown. 
App is used to save all the details of each part of the car. 
and maintains the hierarchy of the parts with a logical nomenclature of parts according to the hierarchy. 
Technologies: AngularJS, Django, AWS.
Implemented a noise/vibration/effort comparison tool. 
This tool uses line charts for visualization of the millions of points.
and compare noise, vibration and effort data of a car and multiple cars.
Technologies: AngularJS, D3.js, Django, AWS, Dygraphs.

Software Engineering Intern @ CauseCode Technologies Pvt Ltd, Pune, India
(May 2016 - July 2016) :
Designed and Implemented job board plugin for company's corporate site https://causecode.com. The plugin can be used to create, read, update and delete job posts. The server side of the plugin is built using groovy on grails. And the front end is built using Angular. The plugin follows REST API architecture. In this project, I got to learn insights of Grails and AngularJS.
Ported homepage and blog page of company's corporate site from AngularJS to ReactJS. Here the front end is ported following the react-redux architecture. In this project, I learned about design patterns used to build the react-redux app.
Implemented social share buttons for company's blog and Google ReCaptcha API for CRM plugin.

Open Source Development and Project Experience
Cmeue (Project Campus Meetup) - https://github.com/cmeue/cmeue: 
Project campus meetup or “Cmeue” aims at developing a web application which will help to connect different year students. 
The main objective of this application is to connect junior students with seniors and alumni.
Junior students can search the seniors and alumni based on linkedIn skills and request them for help/advice. 
ECB SAC - https://github.com/ECB-Bikaner/ecb-sac: 
Built a web app for student's affairs council of my college. 
This app connects students to the events in the college. 
Society/club coordinators can post an event. 
Students can participate in the events and can discuss it on the event info page. 
You can find it running here -- https://ecbsac.org.
Technologies: AngularJS (front-end), Firebase (backend), Auth0 API (authentication), Discuss API (Discussion thread).
Academic Experience
I am a final year student pursuing my bachelor of technology (B-Tech) in Computer Science and Engineering at Govt. Engineering college Bikaner, Rajasthan Technical University, India. I have chosen this field of computer science because I like to build things and in this field there are endless possibilities to build something special.

I am enjoying this field (Computer Science) a lot. I have built a lot small and medium sized projects some of you can have a look here https://github.com/razat249. I have a good understanding of the front end languages and frameworks like ReactJS, AngularJS, Jasmine etc. Recently I am developing an app called “Coddraw”. This web app solves the problem of phone screen interview by providing a rich multi user text editor and a multi user drawing screen. The tool is free to use and there is no signin/signup required. An interviewer can use this tool to pair program with the interviewee with code and draw screen side by side. I am building this app using the ReactJs, Firebase and Node.js.  

I am open source enthusiast and working with the open source for about 2 years from now. I have working knowledge of languages like Python, JavaScript and frameworks like ReactJS, AngularJS, Jasmine etc.  I have contributed to the GSoC organization oppia and solved some of their issues. Also I have developed a course on python in a 2 man team on the oppia platform. These are the top rated courses on the oppia. You can find them here https://www.oppia.org/profile/razat249. 

Why Me
I will be right for this project because I have already started working on the dummy version of this project using the github APIs so that I can learn all the nuts of this project before we will start working on this project officially. You can find my dummy version of this tool here: https://github.com/razat249/Campus-Program/tree/dummy-github-view-tool. Also I have all the important characteristics to pull up this project bug free before time. I work on a time bound fashion which is very important on a hard deadline based projects. I create time logs for analysing myself for better performance and higher productivity.

You can have a look at the above sections on open source experience, academic experience and work/internship experience to know more about me. In my college, I have my own team. We try to work in a fashion such that we can learn as much as possible. In our recent ongoing project CampusMeetup I got to lead my team. I like to work in a process oriented manner so that I plan ahead.

Why Mozilla
There are several reasons I have chosen the Mozilla:
This Project is interesting and will give me a chance to learn a lot.
You guys are doing great work and I want to be a part of this good deed.
Working with mozilla is honourable for me.







Measuring the Development of an Open Source Contributor
Open Innovation (Open Source Student Clubs)

Personal Details
Name: Rajat Patwa
Email: razat249@gmail.com
Github: https://github.com/razat249
LinkedIn: https://www.linkedin.com/in/rajatpatwa/ 
Telephone: +917597305718
Country of residence: India
Timezone: GMT/UTC +05:30
Primary language: English, Hindi

Project Proposal
Overview: I am applying to the project “Measuring the development of an open source contributor”. This project aims at developing a tool which will help in measuring both the impact of an individual in open source projects and also, how being involved in open source, impacts a contributors life. Goals of this project are:
A user is visiting the tool/website where he/she is able to track activities (commits, pull requests, issues) between a set of users.
The user can also track the repositories, these users have been contributing at over time. 
The tool will have to fetch the user's' repositories on its own using the github APIs.
The username will be the input to the tool and different visualizations related to the user will be the output.
Flow Diagram: The flow diagram of how the tool will work is given below. 
Mock Ups: I have created some mock ups below for the tool.
In the below mockup a user can search other users in the search sidebar (here we will use the github search API).
After searching a user, we can analyse all his activities in the right window.
Dropdown, just above the chart in the right side, will be used for visualizing all contributions, commits, pull requests or issues opened/closed by particular user (here we will use the github commits, pull requests and issues APIs for visualizing charts).
Dropdown just above chart in the left will be used to for changing visualization.
I think we can also use a pi chart to show different activities related to student.
We should also brainstorm about what other visualizations we can use.



APIs to Use: I have researched, what all github APIs we need, to pull up this project. I am listing some APIs below.
Github search API - https://developer.github.com/v3/search/: For implementing search feature for searching different users.
Github users API - https://developer.github.com/v3/users/: For fetching user’s data.
Github commits API - https://developer.github.com/v3/repos/commits/: For implementing the chart/board of commits.
Github pull requests API - https://developer.github.com/v3/pulls/#list-pull-requests: For implementing the charts/boards of pull requests made by a user.
Github issues API - https://developer.github.com/v3/issues/#list-issues: For listing all the issues by a particular user.
Other Github APIs which we need in the project: 
Events API:  https://developer.github.com/v3/activity/events/
Activity API: https://developer.github.com/v3/activity/ etc.

Technologies: I am thinking to do this project using ReactJS library. I am choosing this library because React is very good for state managements and complex UIs, as we have different graphs on the screen, the UI will be pretty much complex. 
I have done some projects on ReactJs, So I can easily pick the ReactJS library.
For graphs/charts I think D3 will be great. 
I have found a react implementation of D3 react-calendar-heatmap here https://www.npmjs.com/package/react-calendar-heatmap 

Project and Beyond: I am also interested in working with the other parts of this project, like backend, designing and brainstorming the whole system and other UI/UX stuff which are beyond the scope of GSoC. I want to learn as much as I can and this project will give me a chance to learn and grow myself to become a better engineer.

Schedule of Deliverables and Timeline 
This week-by-week timeline provides a rough guideline of how the project will be done.

May 5 - May 30, 2017 -- Community Bonding Period
Further discuss the activity ideas with the mentor.
Discuss all the design, flow diagrams, working and mockups of the tool. 
Discuss what technologies, frameworks, testing library and APIs to use for this project.
Discuss all the types of visualizations to use like calendar-heatmap, pie charts etc.
Discuss how to manage the different activities and their visualization on the screen.
Setting up the development environment.
Study and make all the system design related brainstorming.

May 30, 2017 - June 30, 2017 -- Start Working on the Project
Start coding.
Designing the high fidelity UI/UX designs for implementation.
Divide the project into several components as given below:
User search sidebar component - projecting to do in 3 - 5 days before 5th of June. Using Github user search API.
Write unit test cases for the user search component - projecting to do it before 10th of June.
Different visualization components - like calendar-heatmap, pie charts, line charts etc. Projecting to do it before 15th of June.
Unit test cases for visualization components - projecting to do it before 20th June.
Integration and testing of the above components and document the work - projecting before 25th June.

June 26, 2017 - June 30, 2017 -- First Evaluations
Submit the user search component and visualization components with their unit tests and documentation.

July 1 - July 24, 2017 -- Continue Coding
Individual user repositories component and its unit testing - projecting before 7th of July.
Other components and features that will come on that time - projecting before 20th July.
Integration and document the code.

July 24, 2017 - July 28, 2017 -- Second Evaluations
Submit the whole integrated app for evolution.

July 28, 2017 - August 21, 2017 -- Final Coding Period
User level rigorous testing.
Reporting the bugs and solve them.
Code refactor and documentation.
Brainstorming the upcoming features and challenges in the tool.
Improving the UI/UX and performance of the tool.
Discussion of other related work beyond GSoC.

August 21 - 29, 2017 -- Final Submission and Evaluations
Final release.
Final debugging, documentation.

The timeline is a tentative timeline of the project. The timeline can be modified according to the project features and requirement changes. I can devote 6 - 8 hours daily at the time of working. I don’t have any other commitments other than this.
Work/Internship Experience
Software Engineer, Intern @ Advanced Structures India, Bangalore, India 
(Dec 2016 - March 2017) : 
Designed and implemented the front-end part of an app called teardown. 
App is used to save all the details of each part of the car. 
and maintains the hierarchy of the parts with a logical nomenclature of parts according to the hierarchy. 
Technologies: AngularJS, Django, AWS.
Implemented a noise/vibration/effort comparison tool. 
This tool uses line charts for visualization of the millions of points.
and compare noise, vibration and effort data of a car and multiple cars.
Technologies: AngularJS, D3.js, Django, AWS, Dygraphs.

Software Engineering Intern @ CauseCode Technologies Pvt Ltd, Pune, India
(May 2016 - July 2016) :
Designed and Implemented job board plugin for company's corporate site https://causecode.com. The plugin can be used to create, read, update and delete job posts. The server side of the plugin is built using groovy on grails. And the front end is built using Angular. The plugin follows REST API architecture. In this project, I got to learn insights of Grails and AngularJS.
Ported homepage and blog page of company's corporate site from AngularJS to ReactJS. Here the front end is ported following the react-redux architecture. In this project, I learned about design patterns used to build the react-redux app.
Implemented social share buttons for company's blog and Google ReCaptcha API for CRM plugin.

Open Source Development and Project Experience
Cmeue (Project Campus Meetup) - https://github.com/cmeue/cmeue: 
Project campus meetup or “Cmeue” aims at developing a web application which will help to connect different year students. 
The main objective of this application is to connect junior students with seniors and alumni.
Junior students can search the seniors and alumni based on linkedIn skills and request them for help/advice. 
ECB SAC - https://github.com/ECB-Bikaner/ecb-sac: 
Built a web app for student's affairs council of my college. 
This app connects students to the events in the college. 
Society/club coordinators can post an event. 
Students can participate in the events and can discuss it on the event info page. 
You can find it running here -- https://ecbsac.org.
Technologies: AngularJS (front-end), Firebase (backend), Auth0 API (authentication), Discuss API (Discussion thread).
Academic Experience
I am a final year student pursuing my bachelor of technology (B-Tech) in Computer Science and Engineering at Govt. Engineering college Bikaner, Rajasthan Technical University, India. I have chosen this field of computer science because I like to build things and in this field there are endless possibilities to build something special.

I am enjoying this field (Computer Science) a lot. I have built a lot small and medium sized projects some of you can have a look here https://github.com/razat249. I have a good understanding of the front end languages and frameworks like ReactJS, AngularJS, Jasmine etc. Recently I am developing an app called “Coddraw”. This web app solves the problem of phone screen interview by providing a rich multi user text editor and a multi user drawing screen. The tool is free to use and there is no signin/signup required. An interviewer can use this tool to pair program with the interviewee with code and draw screen side by side. I am building this app using the ReactJs, Firebase and Node.js.  

I am open source enthusiast and working with the open source for about 2 years from now. I have working knowledge of languages like Python, JavaScript and frameworks like ReactJS, AngularJS, Jasmine etc.  I have contributed to the GSoC organization oppia and solved some of their issues. Also I have developed a course on python in a 2 man team on the oppia platform. These are the top rated courses on the oppia. You can find them here https://www.oppia.org/profile/razat249. 

Why Me
I will be right for this project because I have already started working on the dummy version of this project using the github APIs so that I can learn all the nuts of this project before we will start working on this project officially. You can find my dummy version of this tool here: https://github.com/razat249/Campus-Program/tree/dummy-github-view-tool. Also I have all the important characteristics to pull up this project bug free before time. I work on a time bound fashion which is very important on a hard deadline based projects. I create time logs for analysing myself for better performance and higher productivity.

You can have a look at the above sections on open source experience, academic experience and work/internship experience to know more about me. In my college, I have my own team. We try to work in a fashion such that we can learn as much as possible. In our recent ongoing project CampusMeetup I got to lead my team. I like to work in a process oriented manner so that I plan ahead.

Why Mozilla
There are several reasons I have chosen the Mozilla:
This Project is interesting and will give me a chance to learn a lot.
You guys are doing great work and I want to be a part of this good deed.
Working with mozilla is honourable for me.







