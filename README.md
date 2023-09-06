# Influencer-Management-System
A MERN web application that allows users to manage a list of influencers
# Features
## List view:
A list view that displays all of the influencers in the system, including their name, social media handle, and number of followers.
![Screenshot (193)](https://github.com/imyky1/Influencer-Management-System/assets/109689075/b4dfa9b8-916e-419a-b984-17ac32283eee)
## Add influencer:
A form that allows users to add new influencers to the system.
![Screenshot (194)](https://github.com/imyky1/Influencer-Management-System/assets/109689075/58416dda-042c-4444-b545-47ae19bf395f)

## Edit influencer:
A form that allows users to edit the details of an existing influencer in the system.
![Screenshot (195)](https://github.com/imyky1/Influencer-Management-System/assets/109689075/149b6957-0418-4361-82e2-32e9b2e9cf42)

## Delete influencer: 
A button that allows users to delete an influencer from the system.
![Screenshot (196)](https://github.com/imyky1/Influencer-Management-System/assets/109689075/bf3ae99a-d868-4c91-b4e7-ed7f456d0fce)

## Search:
A search bar that allows users to search for influencers by name or social media handle.
## Sort:
A dropdown menu that allows users to sort the influencer list by name, social media handle, or number of followers.

## Error handling:
The application should handle errors and display appropriate error messages to the user. 

# Run it Locally
1. Clone the repository
2. create a dev.js file in /server/config folder
   ```
   module.exports = {
    DB_URL : <Your Database URL>
   }  
   ```
3. Copy the above code in dev.js file replacing your database URL
4. cd to /server folder in terminal
5. Run this command
   ```
   npm install
   ```
6. start the server
    ```
    node app.js
   ```
7. cd to "/client/user management" folder in other terminal
8. start the react app
   ```
   npm install
   npm run dev
   ```
# Run the application live
https://hemp-influencer-manager.netlify.app/
