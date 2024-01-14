This is a webapp project I created which is a chatroom talking about the current weather in ottawa. It uses mutliple technologies such as NodeJS for the backend and expressjs for creating the server. I programmed everything in javascript and styled using html/css.

There is a guest sign in aswell as for admin.

The website has a SQLite database that stores all user info and their roles (guest/admim)

the weather comes from open weather API.

INSTALL INSTRUCTIONS: open a command prompt in directory and run `npm install`

LAUNCH INSTRUCTIONS: on the same terminal, run `node server.js`

TESTING INSTRUCTIONS: the command prompt will print the following links to visit:


    either create your own user, or use the deafult guest user: 
        username: `GUEST2023`
        password: `GUEST2023`
    
    for an admin user; you can manually make any suer admin in the database or use the following admin user:
        username: `a`
        password: `a`

    visit the following links as a signed in user. 

    ***TO SIGN OUT, PLEASE CLOSE TAB, SHUT DOWN SERVER, AND VISIT THE FIRST LINK!!

    `http://localhost:3000/`
    `http://localhost:3000/protected`
    `http://localhost:3000/admin`

    
YouTube VIDEO LINK: https://youtu.be/XxUzgyNfssQ