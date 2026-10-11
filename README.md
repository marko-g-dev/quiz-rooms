# quiz-rooms

Real-time quiz game. Players join a room, questions are pushed over Socket.IO
with a timer, and the first correct answer in chat scores points.

React, Express, Socket.IO, MongoDB.

Questions are read from the `questions` collection, matched to rooms by id.

    cd back-end && npm install && npm start     # needs back-end/.env, see .env.example
    cd front-end && npm install && npm start
