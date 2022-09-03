# The Complete Story

The Complete Story is a story telling website where a user posts the begginining of a story and other users are able to leave a contribution that can be added to the original story. 

Users are also able to upvote/downvote and/or report the contributions. The story host then has the option to add the contribution which resets the contribution list. If the host decides to end the story with a contribution then the Story is ended and the host and contributors are mention in the story credits.

## Final Product 
### Landing Page
![Landing Page](https://github.com/Jbridges1119/TheCompleteStory/blob/master/planning/gif/landingPage.gif?raw=true)
### Create A Story
![](https://github.com/Jbridges1119/TheCompleteStory/blob/master/planning/gif/createStory.gif?raw=true)
### Adding A Contribution
![](https://github.com/Jbridges1119/TheCompleteStory/blob/master/planning/gif/addContribution.gif?raw=true)
### Select A Contribution
![](https://github.com/Jbridges1119/TheCompleteStory/blob/master/planning/gif/continueContribution.gif?raw=true)
### Ending A Story
![](https://github.com/Jbridges1119/TheCompleteStory/blob/master/planning/gif/endStory.gif?raw=true)

## Built With
- Node.js
- Express
- EJS
- Postgres
- SASS

## Getting Started

1. Create the `.env` by using `.env.example` as a reference.
2. Update the .env file with your relavent local information 
3. Install dependencies: `npm i`
5. Reset database: `npm run db:reset` 
7. Run the server: `npm start`
8. Visit `http://localhost:8080/login/1`

## Dependencies

- "chalk": "^2.4.2",
- "cookie-session": "^2.0.0",
- "dotenv": "^2.0.0",
- "ejs": "^3.1.8",
- "express": "^4.17.1",
- "morgan": "^1.9.1",
- "pg": "^8.7.3",
- "sass": "^1.35.1"
