 ![GIFT_Placement_Portal](./public/assets/images/github-mnit-placement-portal.png)
> An Online Placement & Internship automation web portal for MNIT Jaipur students using MEAN Stack (Node.js, AngularJs, Express.js & MongoDb)

Training & Placement Cell, GIFT Bhubaneswar aims at building a strong interface between industry and the University for training and placement of students. To make recruitment session smoother for students, Training & Placement Cell has a web portal for handling the placement registration for companies visiting our campus.



## Getting Started :

### Prerequisites -

1. Install Node.Js
```
$ sudo apt-get update
$ sudo apt-get install nodejs
```
2. Install npm
```
$ sudo apt-get install npm
```
3. Install MongoDB
```
https://docs.mongodb.com/v3.2/tutorial/install-mongodb-on-ubuntu/
```
### Run Software

1. Clone Repo
```
2. Change Directory
```
```
3. Install Dependencies 
```
$ npm install
```
4. Start server
```
$ PORT=8080 node server.js
```

Server would be running at port 8080. Open any browser. Access the project - http://localhost:8080/

> You need to set environment variables PTP_EMAIL, PTP_EMAIL_PASSWORD, SECRET, SMS_API_KEY,SMS_SENDERID & SMS_BASE_URI in .env file (root folder). For more info refer API files in router folder.


## Repository Structure 
   
    PlacementMNIT/
    ├── app/                    # Backend Folder
    │   ├── controllers/            # All business logic for routers
    │   ├── middlewares/            # ExpressJs Middlewares
    │   ├── models/                 # MongoDB database models
    │   ├── routes/                 # Backend API routes
    │   └── services/               # Server side services 
    ├── public/                 # Frontend Folder
    │   ├── app/                    # Frontend Application
    │   │   ├── controllers/            # AngularJs Controllers
    │   │   ├── directives/             # Custom AngularJs directives 
    │   │   ├── filters/                # Custom AngularJs filters
    │   │   ├── services/               # Services in AngularJs
    │   │   ├── views/                  # All HTML files
    │   │   ├── app.js                  # AngularJs App file
    │   │   └── routes.js               # All AngularJs Front end Routes 
    │   └── assets/                 # Project assets including CSS, Images, Icons, JavaScripts files
    ├── README.md               # README file
    ├── package.json            # Holds metadata relevent to project & project's dependencies 
    ├── .gitignore              # Git ignore files 
    └── server.js               # Node App start file



## Questions or need help?

We want to make it super-easy for Placement Portal users and contributors to talk to us and connect with each other, to share ideas, solve problems and help make Placement Portal awesome. Here are the main channels we're running currently, we'd love to hear from you on one of them:

#### Gitter
If you want to discuss already created issues, potential bugs, new features you would like to work on or any kind of developer chat, you can head over to our [Gitter room](https://gitter.im/PlacementMNIT/community).



#### Email 

[sauravsinghch@gmail.com](mailto:pankajtanwar510@gmail.com)

If you want to talk directly to me, email is the easiest way.

