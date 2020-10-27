ReadMe
Original App Design Project - README Template
TechText
Table of Contents
Overview
Product Spec
Wireframes
Schema
Overview
SMS Texting app called TechText for any business group to stay connected.

Description
With this TechText app co-workers can communicate with each other without having to use regular text messaging on their phones or having to use other unsecure group messaging apps,to discuss strictly business.

App Evaluation
[Evaluation of your app across the following attributes]

Category: Social Networking/Texting
Mobile: This app would be developed for mobile devices intially, but could also can be compatable on a computer. Although using a computer would limit its functionality, the mobile device would have more functionality and features.
Story:Once the user signs up the user would be connected to other users within the same company or department. The user then can decide who they would like to collabrate with.
Market: Only those that work for the company or business can use this app. It will make it easier to discuss enclosed information.
Habit: This app could be used all the time depending on the individual and what needs to be discussed.
Scope: First, the user would have to signup/ register for an account. This app would be widely used because certain company would want their employees to coversate through this app.
Product Spec
1. User Stories (Required and Optional)
Required Must-have Stories

User can register for an account
User can sign in after account registration
User can send a text message consisting of a 500-word limit
User can create and view recipient’s contact information via phonebook
User can create and view their contact information via phonebook
User can update contact information via phonebook
User can send pictures via gallery or camera
User can view and scroll through text messages from different contacts
Optional Nice-to-have Stories

User can send gifs via gallery or camera
User can send videos via gallery or camera
User can send voice messages
User can send contact information via phonebook
User can send location
User can reset password if forgotten
User can search through text messages
2. Screen Archetypes
Registration Screen
User can register for an account
Login Screen
User can sign in after account registration
Creation
User can send pictures via gallery or camera
User can send a text message consisting of a 500-word limit
Profile
User can create and view recipient’s contact information via phonebook
User can create and view their contact information via phonebook
User can update contact information via phonebook
Stream
User can view and scroll through text messages from different contacts
3. Navigation
Tab Navigation (Tab to Screen)

Messages
Contacts
Flow Navigation (Screen to Screen)

Registration Screen
Stream Screen (After account is made)
Login Screen
Stream Screen (Can create a new message)
Registration Screen (If account cannot be found or account has not been created)
Creation
Stream (After message has been sent)
Profile
Stream
Contacts
Stream
Contacts
Profile
Wireframes
[Add picture of your hand sketched wireframes in this section]


[Bonus] Digital Wireframes & Mockups [Complete]
[BONUS] Interactive Prototype [Complete]
Schema
[This section will be completed in Unit 9]

Models
[Object Model #1: Users]

-------------------------------------------------------
|Property    |	Type	| Description                    |
|------------|--------|--------------------------------|
|userName    |	String|	Unique username for the account|
|passWord    |	String|	Unique password for the account|
|emailAddress|	String|	email address linked to account|
|avatar      |	File	| An image for the users’ profile|
|phoneNumber |	Number| Unique phone number for account|
|userFullName|	String|	Full name of user              |
|------------------------------------------------------|

[Object Model #2: Messages]

----------------------------------------------------------------------|
|Property	  |Type	            |Description                            |
|-----------|-----------------|---------------------------------------|
|objectId	  |String	          |Unique for the users’ messages         |
|author	    |Pointer to User	|Identifies message’s origin            |
|image	    |file	            |Image that users’ send                 |
|text	      |string	          |Text users’ send in message            |
|textLength	|number	          |Limits number of characters in messages|
|createdAt	|DateTime	        |Date when message was created          |
|sentAt	    |DateTime	        |Date when message was sent             |
|---------------------------------------------------------------------|

[Object Model #3: Contacts]

---------------------------------------------------------------------------|
|Property	              |Type	            |Description                     |
|-----------------------|-----------------|--------------------------------|
|contactName	          |Pointer to User	|username as contact name        |
|contactPhoneNumber     |number	          |Unique number for contact number|
|contactOfficeNumber    |string	          |Identifies the contact’s office |
|ContactOrganizationName|string	          |Identifies user organization    |
|-----------------------|-----------------|--------------------------------|

Networking
User Profile Screen
*(Read/GET) Query logged in user object
*(Update/PUT) Update user profile image
*(Create/POST) Create contact and post in via phome book.
*(Update/PUT) Update any contact

Home Feed Screen
*(Read/GET) Query all messages where the user is author
*(Delete) Delete existing messaging threads

Create thread screen
*(Create/POST) Create a new thread. Choose a deaored user to send the message and post/ send message in the thread.
*(Create/POST) Create a message where the user can send pictures

Evaluating App Ideas Protocol
When evaluating ideas, you can consider the following:

Mobile: How uniquely mobile is the product experience?
What makes your app more than a glorified website?
Try for 2 or more of these: maps, camera, location, audio, sensors, push, real-time, etc
Story: How compelling is the story around this app once completed?
How clear is the value of this app to your audience?
How well would your friends or peers respond to this product idea?
Market: How large or unique is the market for this app?
What’s the size and scale of your potential user base?
Does this app provide huge value to a niche group of people?
Do you have a well-defined audience of people for this app?
Habit: How habit-forming or addictive is this app?
How frequently would an average user open and use this app?
Does an average user just consume your app or do they create?
Scope: How well-formed is the scope for this app?
How technically challenging will it be to complete this app by the end of the program?
Is a stripped-down version of this app still interesting to build?
How clearly defined is the product you want to build?
