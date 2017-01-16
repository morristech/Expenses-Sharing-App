#Expenses Sharing App (work in progress)

##Project Goal
The app will enable users to create events and share their expenses. It will provide participants 
with notifications of any changes, and enables them to communicate on the events level. 

##App Specifications - Functionality Description (Under development)
```
1. The app is intended for use in Android devices only. 
2. App users will register in the app using Gmail only. This will ensure that each user is unique. 
   Phone numbers and other emails won't be used as users can have more than one.
3. A user can create an event to share expenses. 
   a. An event will state the issuer as the owner and will contain event name, description, and a 
      list of participant members. 
   b. Events should have a date stamp and be searchable by date, name or members.
4. To add participants, the user will be able to select from a list containing his mobile contacts 
   who should also be registered members in the app. 
5. After selecting members for the event, the user will then be able to set transactions with the amount 
   of money each member has lent or borrowed. 
6. The owner of the event is the only one able to delete the event. 
7. The event will log changes made on each request. 
8. Once the event is created, the other members will be notified and the event will show up in their apps. 
9. Each user can add/delete/edit their own transactions or leave the the event. 
   status of each request will be registered and visible on both the owner's and the member's events.  
10. All Actions made on the event and its transactions should be logged in text in the event and 
    participants notified.
11. Text messages between the participants in an event is also possible to add to the event. 
```

##Project current status
```
1. Developed wire-frames of GUI on paper.
2. Created an app to access data on a WampServer. Wrote the server-side APIs in php for test purposes. 
   The app uses the Retrofit REST client and can currently post user-entries with pictures. 
3. Completed the conceptual design for the relational database on the server.
4. Created the normalised tables.
5. Created some of the needed REST php apis onthe server side.
6. Created relevant data models in the app.
7. Implemented  OrmLite for providing a local database in the app. The purpose is to store events information so they 
   can be viewed offline.
8. Implemented Jackson for objects json parsing. 
9. Implemented permissions checking.
10. Implemented fetching mobile contacts. 
```

##Next
```
1. Develop GUI.
2. Develop more REST php apis as needed.
3. Use Retrofit for communicating with the server.
4. Develop syncing mechanism.
3. Testing.
```


## Expenses Sharing Database Table Relationsships 

<img src="https://github.com/Jagerfield/Expenses-Sharing-App/blob/master/msc/Expenses%20Sharing%20DB.PNG" width="700"/> &#160;




