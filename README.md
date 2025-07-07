A full-stack resume builder application built with **React (frontend)** and **Express.js + MongoDB (backend)**. Create, edit, and download beautiful resumes effortlessly.

![Alt Text](https://github.com/vvr10223/Resume_Builder/blob/main/frontend/resume-builder/src/assets/resumehome.png)
![Alt Text](https://github.com/vvr10223/Resume_Builder/blob/main/frontend/resume-builder/src/assets/dashboard1.png)


Running the Resume Builder App Project
Backend (Express.js)
1. Navigate to the `backend` folder in your terminal.
2. Run the following command to install the required dependencies:
npm install
3. Once the dependencies are installed, Let's connect MongoDB
4. create .env file
   add below things
   MONGO_URI="your mongo_db connection string"
   JWT_SECRET= "your JWT_SECRET"
   PORT=8000
   to generate jwt_secret you can run the following command in the terminal.
   node -e "console.log(require('crypto').randomBytes(64).toString('hex'))"
5.Now, start the server by running
  npm run dev

Frontend(Reactjs)
1. Navigate to the `frontend/resume-builder` folder.
2. Run the following command to install the required dependencies:
npm install
3. After the installation is complete, start the React development server by
running:
npm run dev
This will start the frontend server and open the app in your default web
browser.
