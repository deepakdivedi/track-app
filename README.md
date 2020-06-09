# track-app
Application Overview
- Application is built using ReactNative with Expo.
- Please check track-server repository for middleware API which use to communicate between DataBase and Mobile App.
-	MongoDB is use to store data of user and tracks.
-	ExpressApi is used for middleware.
- This application can be use to track route while Hiking, Cycling, Riding, Driving, Walking.
- If user dosen't want to follow standard route shown by standard Map application and keep a track of custom route which they follow, this app is very useful.
- I have not put much effort on UI just wanted to represent working functionality.

Functionality
- Registration
- Login
- Account View
- Track List View
- Track Creation

To run application
- Download this repository
- Download track-server repository
- Use ngrok for running track-server
- Register on cloud.mongodb.com and create your key which will be used for mongodb access.
- Create two collections on mongo for user and locations.
- After setting up track-server successfully install dependices for tracks app.
- Use command npm start to run application.
  

