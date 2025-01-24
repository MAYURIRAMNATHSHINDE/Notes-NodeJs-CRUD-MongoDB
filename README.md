# NotesApp

## Features
User Authentication: Users can log in securely using their email.
Logout Functionality: Users can log out from their accounts for security and privacy.
CRUD Operations: Users can create, read, update, and delete their notes.
Responsive Design: The app is designed to be responsive and user-friendly across all devices.
MongoDB Integration: All user data and notes are stored in MongoDB for seamless access and management.
Session Management: The application keeps track of user sessions for personalized note management.


## You need:
- Database : MongoDB
- Google Console Account to create the API Authentication Key's

## Create .env file
Create a .env file to store your credentials. Example below:
```
MONGODB_URI = mongodb+srv://<username>:<password>@mongodburlhere
GOOGLE_CLIENT_ID= YOUR_GOOGLE_ID_HERE
GOOGLE_CLIENT_SECRET= YOUR_GOOGLE_CLIENT_SECRET_HERE
GOOGLE_CALLBACK_URL=http://localhost:5000/google/callback
```






