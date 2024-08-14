Installation
git clone 
Open 2 terminals in separate windows/tabs.

Terminal 1: Setting Up Backend

cd backend
npm install
npm start
Create a file called .env in the backend folder. Inside it write this :

MONGO_URL = mongodb://127.0.0.1/school

If you are using MongoDB Compass you can use this database link but if you are using MongoDB Atlas then instead of this link write your own database link.

Terminal 2: Setting Up Frontend

cd frontend
npm install
npm start
Now, navigate to localhost:3000 in your browser. The Backend API will be running at localhost:5000.