1. Project info: Project name, Group info (group no., students’ names, and SID)
   Project name: Digital-pet-sanctuary
   GroupNO: 41
   StudentName(SID): LO Ching (14103940)

                     
2. Project file intro:
- server.js: a brief summary of the functionalities it provided, …
- package.json: lists of dependencies, …
  
- public (folder, if you have): what static files are included, …
  -css/style.css:
  -images/: The photo of each pets
  -sounds/: feed, play, rest sounds, when the user on-click it
  
- views (folder, if you have): what EJS or UI files included, …
  -auth/
   -login.ejs: Provided for user login
   -register.ejs: Provided for register login
  -partials/
   -footer.ejs: 
   -haeder.ejs: 
   -header.ejs:
  -pets/
   -crate.ejs: 
   -detail.ejs:  Schema for virtual pets with fields like name (String), type (e.g., 'dog', 'cat'), hunger/happiness/health (Numbers, 0-100), level (Number for evolution), owner   (ObjectId ref to User), and timestamps.
   -list.ejs: List out all the pets
  -dashboard.ejs: Main interaction page showing pet stats (hunger, happiness, health bars) and action buttons (feed, play, rest).
  -error.ejs: 
  -index.ejs: Homepage with pet adoption form and overview of user's current pets.
  
- models (folder, if you have): what model files are included, …
  -User.js: Schema for users with username, email, password, and pets.
  -VirtualPet.js: 
  
3. The cloud-based server URL (your server host running on the cloud platform) for testing:
E.g. 

4. Operation guides (like a user flow) for your server
- Use of Login/Logout pages: a list of valid login information, sign-in steps? …
- Use of your CRUD web pages: which button or UI is used to implement create, read,
update, and delete?
- Use of your RESTful CRUD services: the lists of APIs? HTTP request types? Path URI?
How to test them? CURL testing commands?
