# LiveScript - A web based real-time code editor

# Demonstration

<div>
    <a href="https://www.loom.com/share/6df5beef9eb747eaa63195aa369152cb">
      <p>LiveScript - 19 May 2025 - Watch Video</p>
    </a>
    <a href="https://www.loom.com/share/6df5beef9eb747eaa63195aa369152cb">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/6df5beef9eb747eaa63195aa369152cb-eae1204bec2d6176-full-play.gif">
    </a>
</div>

# v1

[![YouTube](https://img.youtube.com/vi/vz3yFS3xPM8/0.jpg)](https://www.youtube.com/watch?v=vz3yFS3xPM8)

### How to use ?

User onboarding is simple. Create an account to navigate to the dashboard. In the dashboard, create a room to open your code editor, copy the roomId, and send it to other collaborators. Voilà! Now you are all connected, able to see their edits and work together.

### Dummy Test Users

1. email : asdfgh@gmail.com
   password : Asdfghj@13

2. email : qwerty@gmail.com
   password : Qwertyu@13

## Setup

1. Clone the project in your local machine run

```
git clone "https://gitlab.com/nishant19072003-group/livescript.git"
```

### Frontend

2. Execute the commands below

```
cd client
```

```
npm install
```

3. Create a .env file and copy the contents of .env.example in it.

4. Go to appwrite create an account and create an new organization.

5. Create a new project and go to it's setting get the API ENDPOINT and PROJECT ID and paste it in REACT_APP_API_ENDPOINT and REACT_APP_PROJECT_ID in .env file respectively.

6. In the database section create a new database and paste the database id in REACT_APP_DATABASE_ID in .env.

7. Create a new collection as Rooms and paste the collection id in REACT_APP_COLLECTION_ID in .env 

8. Then create it's attribute in the Attribute tab xml, css, js with size 20000 respectively and userId with size 500 all of type string.

9. In the same Settings tab scroll down to the permissions section and add permission Users and select all the CRUD operations.

10. You are good to go

```
npm run start
```


### Backend

11. Start by executing these commands

```
cd server
```

```
npm install
```

```
npm start
```

12. Copy and paste your localhost url in REACT_APP_BACKEND_URL

## FEATURES

1. Multiple people can type and edit code simultaneously in the editor while seeing the live preview. Great for long-distance pair programming and conducting interviews.

2. It includes user authentication elements, such as a secure logout mechanism and a smooth sign-up and login process.

3. Code written in the editor is automatically saved in the database.

4. Exceptionally crafted user interface with code highlighting, toggleable sidebars, and a dynamic view panel.

5. Users have the option to save the code on their local machines.

6. The system incorporates a robust notification system, form validation, and tooltips.

## TECH STACK

### The code sample is written entirely in JavaScript and utilizes the following frameworks:

1. React.js (Frontend)
2. Express.js (Backend)
3. Socket.io (Real-time high-speed data transfer between collaborators)
4. Appwrite

### Libraries Used 

1. react-router-dom 
2. CodeMirror 
3. react-toastify 
4. react-tooltip 
5. react-icons 
6. nodemon
7. formik
8. yup


# LiveScript
