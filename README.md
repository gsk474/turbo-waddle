# turbo-waddle
connecting front end to backend using React and Restful APIS
 

Step 1:
I had created a folder todo-list-app and in that folder again I created two folders which are front end and backend
Step 2: Frontend
In the front end , I created a new React app using npx create-react-app my-app.
With this we can setup a basic react project with all the required dependencies
Step 3:
App.js file located in the src  of frontend is the main component in which  we will implement the app's functionality.
Step 4:
We defined state variables using ‘usestate’ for tasks and a new input task
Step 5:
I fetched the tasks from the backend using ‘useEffect’ when the component mounts.
I Implemented the functions to handle adding and deleting tasks by making API requests to the backend.
Step 6: Backend
I Initialized a new Node.js project by running npm init and created the package.json file.
Step 7:
I installed the necessary packages using npm install express cors node-persist.
Step 8:
Created a new file called server.js inside the backend folder and I had impoted the required modules such as express , cors,node-persist
Step 9:
Make sure that the Express app is set up, define a port and initialize NodePersist.
Step 10:
Add a new task to your storage by implementing the POST /apiTasks route. 
Step 11:
The route to retrieve all tasks from this storage will be implemented with GET/api_tasks. 
Step 12:
Implement the DELETE /api/tasks/:taskId route to delete a task by its ID.
Step 13: connecting front end to backend
In the frontend, I updated the API URLs to match the backend routes (/api/tasks for fetching and adding tasks, /api/tasks/:taskId for deleting tasks). We did this because to Ensure that both front and back end are running  on separate ports, such as port 3000 or port 5000.
Step 14: Testing phase (Running the servers)
In the backend  terminal type- node server.js
In the front end type – npm start 
 

The data is stored in the backend 
 

Thank you

