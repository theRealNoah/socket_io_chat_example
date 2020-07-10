# Socket.IO Chat

Testing Socket.io on my own.

This is a project based on the [Get Started](https://socket.io/get-started/chat/) page of Socket.IO

NOTE: This is a good starter project. Not including install time: I was able to have a functioning local chat server within 45 minutes.

## To Run

Make sure you have Node.Js installed. 
Run `npm i` to install the latest dependencies and then run `node .\index.js` to start the server.
Open `localhost:3000` in multiple browser tabs and chat between separate clients. 

## Ideas for expansion from socket.io

- Broadcast a message to connected users when someone connects or disconnects.
- Add support for nicknames.
- Don’t send the same message to the user that sent it himself. Instead, append the message directly as soon as he presses enter.
- Add “{user} is typing” functionality.
- Show who’s online.
- Add private messaging.
- Share your improvements!


