# scheduler
scheduler

# How to trigger email manually
```js
curl -i -H "Content-Type: application/json" -X POST \
-d '{"email":"to_emailaddress@gmail.com","subject":"Quartz Scheduler Testing","body":"Testing service","dateTime":"2019-02-27T02:48:00","timeZone":"Arab/Gulf"}' \
http://localhost:8080/scheduleEmail
```

Note : Time should always be more than current time (Future dated)

# Screenshot

![alt text](https://github.com/asingh85/emailSchedulerWithQuartz/tree/master/snapshots/AdminScreen.jpg "AdminScreen.jpg")
![alt text](https://github.com/asingh85/emailSchedulerWithQuartz/tree/master/snapshots/GmailSnapshot.jpg "GmailSnapshot.jpg")
![alt text](https://github.com/asingh85/emailSchedulerWithQuartz/tree/master/snapshots/H2Database.jpg "H2Database.jpg")
![alt text](https://github.com/asingh85/emailSchedulerWithQuartz/tree/master/snapshots/LoginScreen.jpg "LoginScreen.jpg")
![alt text](https://github.com/asingh85/emailSchedulerWithQuartz/tree/master/snapshots/Security.jpg "Security.jpg")
