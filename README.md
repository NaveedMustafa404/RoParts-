# RoParts-
RoParts - (Single vendor Ecommerce web application built on MERN Stack)

1	Introduction
1.1	Purpose
The core purpose of this report is to summarizing my critical reflection, my experience with the semester long project for Application Development course. Reflective essays are a great platform from a developer’s point of view where he can portray his work, involvements, learnings and experience. As I have worked on building Ro-Part an e-commerce platform to sell and provide robotics accessories, along with my team mates, here in this report I will try my best to portray all the sprits works and my contributions.
Below on this report I will talk about my team, my experience working with them, work ethics our overall experience, our system and all the ups and down I’ve been throughout project.
   
1.2	Group and my role
Our team name is Fortitude. We are 5 members all and over. We know each other very well from the very beginning but it was first time we formed a team. As a team we were always confident with our plans and implementations. Every member was always eager to learn and try on new things. Our team meetings were more than a meeting as we gelled way easily, it was more interactive and fun session of learning. 

Team Members Role and Responsibilities:

1	Mostafa Musab Naveed	Backend Developer 
-  Primary responsibilities 
-	Backend Developer
-	Building API’s
-	Server handling
-	Resources findings

2	Abu Sayed Khudri Roman 	Frontend Developer 
-  Primary responsibilities  
-  Frontend development 
-  Page layout making

3	Amit Hasan Sadhin	Project Manager 	
-  Primary responsibilities 
-  Planning for the project, analyzing the group mate’s suggestion, 
-  Resource Findings,

4	Hamzeh Wahed Bajbouj	UI/UX Designer 
-  Primary responsibilities 
-  Designing the User interfaces
-  User Experience

5	Almuhannad Darwesh	Database manager 
-  Primary responsibilities  

My role for my team is backend developer. And throughout this project I worked highly on this part of development. But as it is a team project, majority of the time I need to work on other’s role as well. Basically, it was totally a team game, where we shifted our roles several times for our own benefit and efficiency. Throughout the entire development phase, we did peer programming. Whenever We assigned any topic to be developed I tried to be there as a driver to help him if I’m assigned to that role. I’ve directly work on several parts of development. Which are:

1. Building APIS for Sign-up, Sign-in.
2. API development and manage Auth and Middleware.
3. Building Category model and Controllers (API)
4. Building Product Model, Controllers and Validation (API)
5. Building API for product management (ADD, DELETE, UPDATE)
6. Building APIs for Search and Sort to get product from database.
7. API testing using Postman.
8. API for Uploading Product photo.
9. User profile (APIs & Frontend)
10. Order Management (APIs & Frontend)

These are the parts where I had worked directly. I have used NODEJS and EXPRESSJS as our main backend tool and for database we chose NoSQL which is MongoDB. For Frontend we chose ReactJS which is a popular JS library. I started to learn and explore from the very first day. On others topic I was with my team to support any time if they need or to solve any kind of bug.
Working on any project as a team is always amazing. Same for me in this. As I never need to work alone. I always got a partner to develop with. Though after all of this, we as a team went through a lot of ups and downs. Sometime it was regarding developing, sometime on execution or sometimes it was time difference. As we are from different country time management was a huge problem for us. Also, during the discussion and design phase we were hackling, as the total paradigm was oven fresh and I didn’t have any idea rather than vanilla JavaScript and some experience on watching tutorials. But we as a team helped each other a lot during that phase by sharing tons of effecting resources and ideas. Whenever someone stuck on anything we immediate tried to fix a meeting on google meet and tried our best to provide a proper solve for that. We explore, we sit, we think, we try and we solve. 

1.3	System/Apps Description
Because of the numerous advantages and benefits, an increasing number of consumers now choose online buying to traditional shopping. In recent years, the buyer's decision-making process has shifted substantially. Buyers are conducting extensive research online before ever speaking to a sales person. That is why we came up with this e-commerce application which we named RoParts. 
Our system's primary target audience is students who are eager to conduct practical experiments and expand their technical skills. And robotics enthusiasts. 
So basically, what RoParts does is, it’s an application which provide its targeted customers high quality robotics parts (ex: Arduino, Raspberry Pi etc.). There are very few applications who provide technical parts. So, we wanted to take the opportunity.

Some of the functionalities of RoParts are:

Robotic Products: This application has various kinds of products to offer. Not only this we have presented our application to our customers with a minimal interface. Which is easy to understand and efficient. 

Order Product: User can order their desired product from our application. They can browse various products and add them to their cart. After that they can increase and decrease the quantity they want to order. They can simply browse through and select. All the selected product would be stored in their cart. From their they can finally purchase their goods. Also our system will show the user if the product they wanted already in stock or not.

Searching Option: User can search their desired products by searching their names. After entering product’s name system will search through the product database and will retrieve the product and will display that. If the product is not available the system will let user know that the searching product is not available. 

Filtering: Our application provide user an advance filtering system. By which user can search their product by sorting them by their category. User can filter or sort the products by their price as well. System will also show the related products beside the searching separately.  

Secure Payment: Our application accepts a variety of payment methods, including credit cards and PayPal. We acquired SSL from Cloudflare to make our payment method safe.

24/7 Customer Service: Customers with difficulties or concerns regarding the purchase process can contact the customer service department for assistance. This assistance may be necessary before, during, or after a transaction, as shown in the following scenarios: For this type of service, we included a live chat feature to our website, 24/7. 
 
Sample Screen Shots of our system:  
 ![landingpage](https://user-images.githubusercontent.com/77004868/168717739-4d78b97f-37f9-4f11-bd5b-8438c5fea847.png) 
Figure 1: LandingPage

![signin](https://user-images.githubusercontent.com/77004868/168717852-c64d2319-e2b7-48ba-a69a-3437e3f47d66.png) 
Figure 2: SignIn
 
![signup](https://user-images.githubusercontent.com/77004868/168717887-2e090f73-2309-443c-ac52-d6b21d9e70f2.png) 
Figure 3: SignUp
 
![store](https://user-images.githubusercontent.com/77004868/168717932-235078cb-1eda-4596-b04c-57ec048aed31.png)

Figure 4: Store

![userdash](https://user-images.githubusercontent.com/77004868/168718041-b5b49df4-3bc5-43fe-976e-2b89571a6103.png)

Figure 5: UserPurchasHistory

![adminmanageorder](https://user-images.githubusercontent.com/77004868/168718113-ff634e86-75f4-4d90-85f7-b5aaf6706f40.png)

Figure 6: OrderManagement

 ![manageproduct](https://user-images.githubusercontent.com/77004868/168718176-3decb37b-d5e5-455e-8ec9-0ea00e3efc3a.png)

Figure 7: ManageProduct

![createproduct](https://user-images.githubusercontent.com/77004868/168718243-1e84da54-6c51-4757-946d-2aa5644c216c.png)

Figure 8: Create/Upload Product

2	Implementation of software development tools
This project required us to implement some interesting tools during development …

2.1	Clockify
Basically, we use Clockify to keep track of our working hours. And in my opinion, this is the best tool ever on tracking. It is the easiest to use. What I liked most about Clockify is how easy and intuitive it is to use. Plus, the variety and quality of reporting options is awesome. I am seeing easily how I'm spending my time. The data in the various reports is so helpful. I can see what projects in general are taking the bulk of my time, and then being able to see the top 10 tasks gives an even deeper insight. I have spent almost 140 hours which includes learning session, exploring and development part.

![Screenshot](https://user-images.githubusercontent.com/77004868/168718407-d3a9d48f-ec49-4665-9422-c873e83cc993.png)

Figure 8: Clockify
 

2.2	Git & Github
We have used Git & Github for version controlling. I had a difficult time working my way through it because I was new to git and the platform GitHub. One may work locally and push to the remote git repository using Github's features, such as a repository that is my git project. I thought I was doing okay with git until I learned about features like branching, pull requests, commit messages, and merging, as well as their many correct standards. Then it seemed to me that I still had a lot to learn in order to fully utilize this instrument. After learning the fundamentals of the git and GitHub workflows, I found that my work was more structured and that I could easily keep track of my files and project progress.


2.3	IDE tools(VS CODE)
Visual Studio Code features a lightning fast source code editor, perfect for day-to-day use. I personally prefer this IDE because it offers plenty of amazing features like, syntax highlighting, bracket-matching, auto-indentation, box-selection, snippets, and more. Intuitive keyboard shortcuts, easy customization and many more. It is probably the best IDE for Javascript, because it has, terminal, so anyone can use it for Node. js, there are so many extensions to play with as well. 

![image](https://user-images.githubusercontent.com/77004868/168718549-9708407f-fa4e-41fe-a831-6e6459af06de.png)
 
Figure 11: VS Code

2.4	PostMan	
Postman is basically HTTP Client based software application which is used to perform API testing. Postman provides inbuilt monitoring services that help us be in sync with the API development and performance. As we started developing backend first, then as a backend developer I used postman to test my APIs as there was no particular view available at that time. 

![image](https://user-images.githubusercontent.com/77004868/168718802-884488e2-4f5f-4f5a-8ba3-a6e9aaf12fd8.png)

Figure 12: Postman


2.5   JIRA

From my personal experience JIRA is an amazing project management tool. It really helped us in terms of: team collaboration, Agile methodology adoption, manage our time and checking the deadlines. We maintained our project progress where we divided our development cycle in 4 sprints. We updated our works at the end of each sprints. Besides it helps us to keep our flow and prioritize our tasks till the last. 

![image](https://user-images.githubusercontent.com/77004868/168718876-b4e21382-a459-45f6-b98b-78a605ed7242.png)

Figure 13: BurnupReport
 
![image](https://user-images.githubusercontent.com/77004868/168718925-d9177f33-dcbb-4481-bc7a-5780a99884b2.png)

Figure 15: CumulativeFlowDiagram
 
3	Soft Skill set enhancement

Soft skills are an important aspect of increasing one's capacity to collaborate with people and can help you advance in your profession. The process of earning or improving soft skills is not a visual thing. It’s a personal trait which develop with one’s activity. This kind of skills are important because one can extends their inner potential. Throughout this project life cycle interactions with my team members, reaching out my seniors for solutions or by negotiating with my lecturer I think from this course I have earned a lot. I have improved a lot. Because of proper leadership, time management, communication, team working, adaptability and problem-solving skills we able to accelerate our project till the last and built our application successfully.   
Soft skills I think I have improved throughout this project phase:

3.1	Project management/Organization
Whatever the work is, if it is not organized or planned then it is impossible to pull out the ultimate result. As we are five members in our team, it is very much possible to create a chaotic environment. Without a plan or shift it is hard to jump on any decision and implementations. For this, we have used some amazing tools to keep our work and commitments organized. By which five of us were clear about our responsibilities and committed to the execution of our plans. We use Clockify to keep track our working hours. Not only as a group we have used it personally on our individual learning session or works. We used this to keep our effort transparent to the team members. Then we use JIRA for our project development phases. We have five sprints and we divided out works using JIRA based on priority. This helped us to keep track on our works which are done and which not. And we use GitHub for version controlling of our project. By using all these efficient tools  I can say from now, I am more organized than before.     

3.2	Problem Solving/Creativity/Critical Thinking
I have gone through a lot during development stages. Building APIs was not easy at all. I became impatience sometimes. It was a great challenge to build perfect APIs for the out system. Lot of bugs, server issues, database problems and what not. As I was new it was not that easy to build all by one chance. During that phase, I have read a lot of resources read them patiently, analysis them and using resources creatively. We have lot of solutions on stack-overflow for our problem. But it is a skill to implement those by adapting the project environment. And beside all these, thinking capability! I have spent hours and hours for only one problem to get solved. This is the part I have improved a lot. Analyzing and logical reasoning are the crats I have earned which ultimately boosted my problem-solving skills. 

3.3	Teamwork/Communication
As we are 5 members in our team it was never easy to negotiate. We come from various cultures and speak different languages, and we've collaborated on project. Everyone has their own opinions and reasons. As I mentioned before we have worked on pair. Our quality of work improves when we use our individual strengths and skills together in collaborations. Majority of the time we were in google meet and from my part on making decisions or sharing any ideas I was clear and always tried to stay transparent. And the results are less conflicts and our work-time became more attractive and interesting.
We use Google meet and for conferences and meetings and used WhatsApp and Telegram for continuous interactions. 

3.4	Adaptability
As we working on a project following a new stack, quick learning and adapting the JS paradigm and dynamic programming was a new thing for me. I have improved a lot on learning under pressure. My level of curiosity increased during the phase of learning and implementation. 

3.5 Leadership 
As I lead the backend part, I need to manage my team mates with all the resources and always tried to stay empathetic to my team members. The biggest thing I learned is to take positive decisions no matter what the situation is and stick with it. 

3.6 Time Management
Before I was the kind of person who wants to do everything at once. But during the project lifetime I tried to improve my time management skills and also, I have used Clockify to keep track of time and JIRA which helped me to prioritize my works one by one. Not at once but one by one stares are the goal to success.
 
4	Hard Skill set enhancement

Hard skills are an important component of our studies, and during the course of this project, I learnt new technologies to work on development field. This is the kind of skills which would make a person or developer unique than others. I have gained some serious technical skills such as prototyping, workflow development developing APIs Payment processing and many more. My typing speed has increased and besides I am now a guy who understand database. If I merge majority of my hard skill falls under web development, server management and wireframing. 

4.1	Wireframing and UI/UX
Wireframing is one of the most critical tasks we must perform prior to beginning development. We wanted to do everything we could to understand the individuals for whom we were developing, so we worked closely with them to thoroughly grasp their requirements and desires. It was critical to think about how this website might add value to the relationships and communities we intended to help our customers build. Wireframing was done in Adobe XD and Photoshop. Before development it helps to justify whether the design would be suitable for consumer or client.

![image](https://user-images.githubusercontent.com/77004868/168718974-48fcc509-17b7-40ad-a034-af1274d79f54.png)
Figure 16: Prototype



4.2	Server setup/configuration
I was involved during development. We have used DigitalOcean which is a robust tool for managing virtual servers in the cloud. We purchased a droplet from DigitalOcean to host our website. We bought domain name from NameCheap. Our application link: http://roparts.xyz/
4.3	Web development
RoParts is a web-based application. And to be honest it is kind of my point of interest too. Throughout this project I have learned how to handle development problems and the big thing is now I know what is the approach to build or develop a web applications. We were determined to use the latest market leading technologies for developing our application so we chose MERN stack which is basically comprises of 4 technologies, MondoDB, ExpressJS, ReactJS and NodeJS. This Stack is a Javascript Stack that is used for easier and faster deployment of full-stack web applications

 ![image](https://user-images.githubusercontent.com/77004868/168719004-ed4be2fd-6d7b-4ef8-b00e-7a9dce5956e3.png)

MongoDB: This is a NoSQL database where data are stored in form of JASON.

ExpressJS: A Node.js framework is Express. Express makes building back-end code simpler and easier than writing it in Node.js and creating dozens of new Node modules. Designing excellent web applications and APIs is easier with Express.

ReactJs: The React library is a JavaScript library for creating user interfaces. Because of its capacity to manage rapidly changing data, React is commonly used in the building of single-page applications. React allows us to code in JavaScript and construct reusable UI components.

NodeJS: Node.js provides a JavaScript Environment which allows the user to run our code on the server. Basically, NodeJS provided the environment for building backend of our application.

My personal experience on this web development is kind of mist. As I heavily worked on backend I have plenty of things to learn on frontend which is basically react in our case. But overall, I have sharpened my knowledge through the implementations and my problem-solving capability regarding this kind of project has increased immensely. 


5	Conclusions

Throughout this project, this 4months journey was way more exciting, thrilling and enjoyable. Personally, I had this kind of feeling that whatever we were learning the chance we get for implementation is too small. But at the very beginning of this course I was confident enough that yes! This is the time to learn the latest market leading tech and implement them for achieving a goal side by side. This course is so flexible that it helped us to pick our desired technologies and work with that. For me the thing I feel that I did well is, the learning phase and proper execution of whatever I learn. Before it was only learning but this time I got a chance to implement my knowledge to build a real-life application. Building real life application is not easy! And that I have learned as well. Most difficult thing I found was to implement my imagination and design to a workable application. Prototyping is easy but make it alive as a real-life application is tough and challenging. But by this how journey starts. Its always rough at first, then it leads us toward success. 
After all this now I am pretty confident to present myself as a fresher who knows how to work on backend of any application which is a motivation to learn more and more to apply for companies as a backend developer. This application is my outcome. It is a prove that I worked hard to establish myself as a backend developer. I know how to work on backend of any application using NodeJs. I know how to work on APIs of a system. I know how to connect servers for a system. I know the difference between SQL and NOSQL. I can work with MongoDB. I know how payment gateway works. I know version controlling using Github, deploying a system and an amazing experience to work as team guy to pull out imagination to a workable application. And this entire journey makes me feel proud of that. 
I believe it is just a start. Whatever we have submitted its not enough to compete at highest level. From now on it will be my regular practice as I am still concern about my knowledge regarding APIs because there are plenty of techniques and methods to explore. And also, if I talk about our project we need some serious work on Frontend design for better user experience. 
Finally, I want to show my gratitude to our dr. for letting us explore and prioritizing our point of interests. I'd want to emphasize how fascinating this project is because it allows me to study and implement at the same time. I was able to collaborate with others and expand my understanding on variety of market leading technologies.
 

