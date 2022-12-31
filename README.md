# SnackMatch
## Starting the frontend
From the root of the repository, you'll need to enter the client folder, install the necessary dependencies, and run the app. 
```bash
cd client
#If you don't already have yarn
npm install --global yarn
yarn install
yarn start
```
Navigate to localhost:3000 to see the running app. You'll notice that the Express status will state "Currently down." It will remain that way until you start the backend. 

## Starting the backend
From the root of the repository, you'll need to enter the api folder, install the necessary dependencies, and run the server. 
```bash
cd api
yarn install
yarn start
```
Navigate to localhost:9000/testAPI to see the results of the /testAPI route. If you refresh your localhost:3000 tab, your Express status should change.
