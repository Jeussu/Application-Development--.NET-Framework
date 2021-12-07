# Application-Development--.NET-Framework
I. 	Introduction: 
FPT Corporation would like to develop an ongoing learning atmosphere in the organization. So they need a system that handles the running of the company's internal training program's online training program. This method can be used for the management of trainee accounts, instructor management, course list management, course management, topic management, course subject assignment, assignment of lecturers to topic participants, assignment of trainees. This is a method that the department of human resources uses. In this system, we have three roles: administrator, training staff, and coaches. You will find a comprehensive overview of those positions in the attached text. 
	II. 	Requirement 
1.	User Documentation 
This document contains guidance about how to use the website for users, and it directs all the functions of each object, such as creating new users, editing, removing, etc. Users and administrators or courses for inserting or editing. Update feature, users will receive new instructions. 
2.	Overall Description 
FPT Company is planning to create a student to search for and learn as technology is rapidly evolving. Therefore, to handle the operation of the internal training program, the FPT Organization requires a website system. In this ASM, there are comprehensive explanations of system management specifications. Company want to create a quality website; the analysis of specifications is very relevant in the process of software development. Requirements for applications would mean anything. 
A.	Product Overview 
As a web-based application, this internal training program was developed. This system will be used by the department of human resources for trainee account management, lecturer management, course list management, course management, topic management, course subject assignment, topic coach assignment. Admin, training personnel, and coach positions are the three key functions related to this system. 
B.	Product Functionality 
The key tasks must be carried out as follows: 
-	Login into the system via the application's first page 
-	Create / edit / delete new user accounts for coaches / trainers / trainers and allocate / change username and password (if present user) 
-	Store records in a database 
-	Users Search and Control 
-	Can handle categories of the course 
-	Display profile information 
3. System requirements 
a. External Interface requirements 
• User interface 
-	Front-end software: HTML, CSS, JavaScript, Bootstrap 
-	Software support: C # 
-	Database: ASP.net • Hardware interface - Windows. 
-	The browser supports CSS, HTML & PHP 
![image](https://user-images.githubusercontent.com/94780400/144968115-8c26987f-76b7-4615-a436-9f9da4c7d7f1.png)
b.	Function Requirement Administrator: 
•	The administrator can log into the system via the login page of the website. 
•	The administrator will create / edit / delete an account for training personnel. 
•	The administrator will create / edit / delete an account for the trainer. 
Trainer: 
•	The website can be accessed by the trainer via the login page • The trainer will edit his own profile. 
•	The Trainer will see his / her subject assigned. 
Trainee: 
•	The website can be accessed by the trainee via the login page • The trainee will edit his own profile. • The Trainer will see his / her course assigned Training Staff: 
•	The website can be accessed by training staff via the login tab. 
•	Training staff can create / edit/delete categories, classes, topics, trainers, trainees. 
•	Training staff may assign a subject to a course, assign a teacher to a subject, trainee to a course. 
c.	Other Non-function Requirement 
Performance requirements 
•	In 2s, site load time 
•	If the request cannot be processed, an error is shown on the screen immediately. 
Requirements for safety and confidentiality 
Here are some points that are recommended: 
•	Daily maintenance and inspection of the system are necessary. 
•	It is important to classify the User Object 
•	It is important to periodically backup databases 
•	After entering their username and password, users can access the profile and this data needs to be kept confidential. 
•	To secure the system and prevent attacks from outside, users should have at least a firewall inside the computer. 
•	Kit for encryption: Encryption leaves data unreadable. Decoding transforms data that is unreadable into regular data. In the case of robbery, this is very necessary and avoids unauthorized access. 
•	Install an antivirus application: malicious code can be bundled with the files you download and the applications you install on your mobile device. When released, this code will submit your data to hackers, thereby rendering you unsafe and stealing your privacy. To prevent that, your security will be assured by downloading a trustworthy anti-virus program. Identify other fields of risk involved in completing the creation of the application. 
•	Risk schedule: When a project task is not handled promptly, a project schedule will fail. Because of the following factors, the plan frequently fails: wrong time estimate, failure to define the complexity of functions and time needed to establish certain functions and suddenly extend the project scope 
•	Operational risk: due to the following factors, this form of danger will occur: the ineffective resolution of duties and disputes, no team contact, no planning resources 
Software quality attributes 
-	Reliability 
For this application, what we want to accomplish is reliability. To attain it, we must try to complete the elements: 
•	For a given number of input tests, the system responds to a feature (defined by specifications) under specified input conditions for a specified time period (assuming hardware and no error input). This allows us to provide full system functions with minimal errors so that users can use and trust the user in essence. 
•	User databases and details should be kept private. 
•	All designed functions are intended to meet user requirements 
-	Availability 
We built an easy and smooth interface to help users have a better experience. Furthermore, we also have a complete guide, but with a straightforward interface, functionality, basic processes, easy access, and experience for users. 
4. Other requirements 
Project database requirements: The wrong database will waste time and cash on the project. We should, therefore, ask the following questions in order to have the required database: 
•	What kind of data do we want to store and why do we want that data to be stored? 
•	How significant is the relationship to each dataset that we try to store? 
•	What data do we want to organize and how are we going to access it? 
•	How much and how do we safeguard data? 
•	Who's going to access this data? 
	III. 	UML Diagram 
1. Activity diagram 
![image](https://user-images.githubusercontent.com/94780400/144968158-f3461509-13d1-42d5-89d3-24c4b2080005.png)
Figure 1:Activity diagram for system 
![image](https://user-images.githubusercontent.com/94780400/144968175-3219adff-1693-4abb-a666-b71d6419e89b.png)
Figure 2:Activity diagram for trainer 
![image](https://user-images.githubusercontent.com/94780400/144968196-437a6886-3179-4482-b878-56c14f225f9d.png)
Figure 3:Activity diagram for Admin 
![image](https://user-images.githubusercontent.com/94780400/144968217-eaca469e-5abd-4820-aacf-4e83bd512248.png)
![image](https://user-images.githubusercontent.com/94780400/144968223-549efd92-6f54-4c4c-bb36-ade089e900cf.png)
![image](https://user-images.githubusercontent.com/94780400/144968229-e57ffa4d-f59a-45b0-bf43-97018d317e3f.png)
![image](https://user-images.githubusercontent.com/94780400/144968235-5cb79caa-2197-4314-b755-6861fb771f4a.png)
Figure 6:Sequence diagram for Training staff 
![image](https://user-images.githubusercontent.com/94780400/144968251-ad3855a0-854f-4fd4-ab53-37d9886b354f.png)
Figure 7:Sequence diagram for Trainer 
![image](https://user-images.githubusercontent.com/94780400/144968272-313e4c82-6b89-4143-b79e-0756d1d8a5ba.png)
Figure 8:Sequence diagram for trainee 
![image](https://user-images.githubusercontent.com/94780400/144968284-b8c4e7de-f9f5-4238-b845-b10c536173b4.png)
Figure 9:Sequence diagram for admin 
![image](https://user-images.githubusercontent.com/94780400/144968304-3bb2dde1-8489-4308-9c40-b6fa8b53ea8f.png)
Figure 10:Use case model of System 
![image](https://user-images.githubusercontent.com/94780400/144968325-ba2e1858-b85e-460a-a5bd-aa2ee9cd4c92.png)
Figure 11:Use case model of Admin 
![image](https://user-images.githubusercontent.com/94780400/144968339-ff9cc01f-edd3-42a8-835d-88d817cdcfd4.png)
![image](https://user-images.githubusercontent.com/94780400/144968349-a3b2f06e-4da1-417c-80b4-57974aaa8cd9.png)
![image](https://user-images.githubusercontent.com/94780400/144968352-d5f889d0-5b60-4aa5-9c43-52306ed18f0f.png)
IV. 	ERD 
![image](https://user-images.githubusercontent.com/94780400/144968365-da865b87-cfcb-4c55-97c3-44ac3ffa7223.png)
![image](https://user-images.githubusercontent.com/94780400/144968370-f7f1211a-09ef-4e72-bb32-662841193030.png)
Homepage 
![image](https://user-images.githubusercontent.com/94780400/144968405-975b679f-ad22-4cbe-9494-a9bd2dc3c4e0.png)
Trainer 
![image](https://user-images.githubusercontent.com/94780400/144968431-e4d7f9e7-a3b4-4272-a60e-8fa3b7772e81.png)
Training Staff 
VI. Determine any areas of risk related to the successful completion of your application. 
1. Lack of resources 
If the application is built for too short or too long a period of time , it can lead to negative effects for a while. If the time is too limited, the application may be incomplete which may cause usage errors. It can break the business plan if the time is too long. For each stage of application growth, it is necessary to decide the correct time and obey it. 
This is the most important factor in a successful project for humans. I used to play an online game released on CH Play, for instance. The player's first experience was very good, but the game has a lot of errors when it's played for a long time. Within the required time, their developer team was unable to process or was even unable to manage the error which made further errors occur. There were so many players left. This is a lack of the Dev team's technological abilities. 
Understanding the value of preparation is the solution to these problems. Create a full plan from there, and determine the viability of that plan. If the plan's feasibility is not high, then the project should be stopped. 
2.	Misunderstanding requirements 
Normally, the person receiving customer requests would not be the one who creates the application directly. Therefore, when it is transmitted by several intermediaries, information may be misleading. According to customer specifications, this leads to the end result of inappropriate application. 
There are the following ways to solve this issue. The dev team should make a prototype of the application in the testing phase and request the client to come and try it. The most accurate suggestion to help the dev team complete the product would be the comments received after this. 
3.	Gold plating 
Sometimes, certain unwanted features are applied to the application, but the real effect is not brought about. It can make it difficult to use the application or give rise to unnecessary errors. It is also time-consuming to add and add these functions. The project leader should perform a followup and ongoing research to solve this problem. 
4.	Sudden growth in requirements 
It's very important even to identify the risks now. Because the risks are small, the deadline at the end may be missed. The solution recognizes the risk as a must from the outset, but during the application development process, it should also be constantly modified. 
5.	Unforeseen risks 
These include changes in government policies, obsolescence of software, or other risks that are unmanageable or estimated. The only thing that can be accomplished is to reduce the project's effects as soon as possible. 
VII. Research the use of software development tools and technique and identify any that have been selected for the development of this application. 
Development techniques 
The life cycle of software development (SDLC) is a structure that describes tasks performed at each stage in the process of software development. It is a framework followed within the software organization by a production team. 
Waterfall Model 
A linear, sequential approach to the life cycle of software development (SDLC) that is commonly used in software engineering and product development is the waterfall model. Software development activities are divided into several stages. A stage's output becomes the next stage's data. This model has four stages: planning, research, design, and implementation. We can see the image below. 
![image](https://user-images.githubusercontent.com/94780400/144968462-a1ed7001-ef42-47bd-b1db-681277e1f317.png)
The advantages of the V-model: It is easy and simple to understand. It improves the system's effectiveness. In addition, the fact that tests are being planned soon will help us save time in the process of software creation. However, it also has drawbacks compared to the waterfall model since it was derived from the waterfall model. 
Here are some of the Waterfall Model 's benefits: 
-	Simple and simple to comprehend and to use 
-	Due to the rigidity of the model, it is simple to handle. Each stage has unique deliverables and a process of review. 
-	Phases are processed one at a time and completed. 
-	For smaller projects where specifications are known very well, it works well. 
There are some disadvantages besides that: 
-	No working software is produced until late during the life cycle. 
-	Elevated levels of risk and uncertainty. 
-	For dynamic and object-oriented projects, this is not a successful model. 
-	Not acceptable for projects where there is a moderate to high risk of change in specifications. So, with this process model, risk and uncertainty are high. 
V-Model 
The V-model is an SDLC model where method execution takes place in a V-shape in a sequential manner. It is also known as the model of Verification and Validation. The V-Model is an extension of the waterfall model and is based on a testing process association for each subsequent stage of growth. This means that there is a specifically related testing process for any single phase in the development cycle. This is a highly-disciplined model and only after the completion of the previous phase does the next phase begin. (Anon, 2008) 
![image](https://user-images.githubusercontent.com/94780400/144968484-1ffbdae4-ea76-48b6-8a17-c24ba84434eb.png)
The advantages of the V-model: It is easy and quick to understand. It increases the system's effectiveness. In addition, the fact that tests are being planned soon will help us save time in the process of software creation. 
However, it also has drawbacks compared to the waterfall model since it was derived from the waterfall model. 
1. Web MVC Model 
The Model-View-Controller (MVC) is an architectural pattern dividing an application into three main logical components: the model, the view, and the controller. Each of these components is designed to manage specific aspects of an application's growth. To build scalable and extensible projects, MVC is one of the most commonly used industry-standard web development frameworks. 
•	Model: All the data-related logic that the user works with corresponds to the Model component. This can represent either the data that is being transmitted between the components of the View and Controller or some other data relevant to business logic. 
•	View: For all of the application's UI logic, the View component is used. 
•	Controller: In order to process all business logic and incoming requests, controllers serve as an interface between the Model and View components, manipulate data using the Model component, and communicate with the Views to make the final output. 
![image](https://user-images.githubusercontent.com/94780400/144968498-248a143b-eb5d-45f8-822c-480fd573c078.png)
2. Web development languages 
There are several language forms that we can use to do your project. Here are some examples I'll be showing you. 
-	PHP: 
• This is an open-source programming language, easily incorporated into HTML and integrated with the internet. Easy syntax, fast processing speed, and high community are the advantages of the PHP programming language. This language was also used by Facebook to build its entire back-end infrastructure. 
-	Some advantage: 
•	Open Source: PHP is open-source and cost-free, which allows developers to quickly and easily install it for use. There are several PHP frameworks, and any of the frameworks to be used can be selected by the developer. 
•	Platform Independent: All operating systems, such as Windows , Unix, Linux, etc., support PHP primarily. You can easily run PHP-based built web applications on any platform. 
•	Simple and Easy: This PHP advantage is fast and easy to read and write. It's mostly structured and clean code, which also helps the new developers. 
•	Fast: Compared to others, PHP is regarded as the quickest programming language. Over the slow Internet and data speed, PHP applications can easily be loaded. 
-	JAVA: Java, first published by Sun Microsystems in 1995, is a programming language and computing platform. 
•	For Android smartphone apps, it is the most popular programming language. 
-	Some advantage: 
•	Simple: Java is straightforward to use, write, compile, debug, and learn than alternative programming languages. 
•	Object-Oriented: It makes it possible for you to build standard programs and reusable code. 
•	Platform-Independent: Java code runs on any computer that does not require installation of any special software, but the JVM needs to be present on the computer. 
-	C#: The language C # is pronounced as the language C sharp. It is a modern, general-purpose, objectoriented programming language developed by Microsoft as part of its .Net and Andres Hejlsbergled initiative. A really simple language to learn is the C # programming language. It is entirely founded upon the languages of C and C++. 
-	Some advantage of C#: 
•	Cross-Platform: The NET framework is the most significant prerequisite for C # programming. To run your application well, your computer has to install the NET Framework. 
•	Automatic Garbage Collection: A very powerful system built in C # programming that automatically collects and erases garbage present on the system. 
•	Easy-to-Development: Language C # has a rich library class that makes it easy to implement several functions. Most of the world's programmers are inspired by the C # programming language and have a background in the programming world. 
-	We decided to choose C # for our project after referencing programming languages because: 
•	C # is a pure object-oriented programming language that enables you to build modular programs and reusable codes that can be maintained. 
•	The cost of using this language is not as costly as other languages are. 
•	It has a good backup memory. The programming language of C # requires high memory backup so that there is no memory leakage problem and other such kinds of problems as in the case of C+++ 
•	Language C # has a rich library class that makes it easy to implement several functions. Most of the world's programmers are inspired by the C # programming language and have a background in the programming world. 
•	The most powerful programming language for the .NET Framework is the C # language. 
 
 
 
References 
Anon. (2008). SDLC - V-Model. Retrieved from tutorialspoint: 
https://www.tutorialspoint.com/sdlc/sdlc_v_model.htm 

