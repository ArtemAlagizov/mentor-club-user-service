# mentor-club-user-service

user service for [mentor-club](https://github.com/ArtemAlagizov/mentor-club)

send email using ses:
```
https://docs.aws.amazon.com/ses/latest/DeveloperGuide/send-using-sdk-java.html
```
todo:
* apply for moving ses account out of sandbox => [aws guide](https://docs.aws.amazon.com/ses/latest/DeveloperGuide/request-production-access.html)
* implement this service
* deploy to ec2 
* create role for ec2 to be able to use ses(?)
* assign the role to the ec2(?)
