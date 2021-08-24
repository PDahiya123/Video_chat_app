# Teams-clone

It is a Web Application through which one can do video meetings with multiple participants.


## Built With

* [Node Js](https://nodejs.org/en/) - For Backend
* [Peer JS](https://peerjs.com/) - PeerJS simplifies WebRTC peer-to-peer data, video, and audio calls.
* [SocketIo](https://socket.io/) - For realtime communications
* [NPM](https://www.npmjs.com/) - Dependency Management
* [Heroku](https://heroku.com) - Used to Deploy Node.js applications


## Dependencies Used:
   * [Peerjs](https://peerjs.com/)
   * [Express](http://expressjs.com/)
   * [Passport](http://www.passportjs.org/docs/)
   * [Mongoose](https://mongoosejs.com/docs/)

## Key Features Include:
Video Conversation between multiple participants(more than 2)
   * Video toggle 
   * Audio toggle
   * Share meet link (Enables user to copy the link)
   * Present screen
   * Recording the meet
   * Chat feature(live chat)
   * Number of attendees
   * Waiting room(user joins the meet only after clicking join call button else stays in the waiting room)
   * Responsive website
   * Expand and contract screen feature for user video 
   * Cross platform (works on mobile and pc)
   * Enables cam change feature on mobile 


### Prerequisites

You have to install [Node.js](https://nodejs.org/en/) in your machine.



### Installing and running the app

After installing node clone the repo by using git

```
git clone https://github.com/PDahiya123/Video_chat_app
                     
```

Or you can download the zip file.

Then open cmd or git bash on the project folder to install some modules that I used to build this project

Install Once

```
npm install
```



* The above command will install all the required packages and dependencies required for the project 
* The final step is to run the following command

`npm run dev`

 After doing the above steps go to your browser and type localhost:3000.
 
 Before that you have to make a keys.js file in config folder which contain your database details like this:
 `module.exports = {
    MongoURI : 'mongodb+srv://<user>:password@cluster08451.am7f4.mongodb.net/<name of database>?retryWrites=true&w=majority'
}`


## Live Demo

For deploying the project I used [heroku](https://heroku.com)

https://teams-2.herokuapp.com

### This Web App was developed by Pranshu Dahiya


