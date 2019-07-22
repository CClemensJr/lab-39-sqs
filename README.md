# Lab 39: SQS with Lambda
> For this assignment, we will be wiring up our Queues with live running cloud based code, creating a distributed, event driven architecture.

## Feature Tasks
### Using Queues and Notifications ...
- [ ] Send an email to an administrator when a task is completed
- [ ] Send a text to the person to whom a task is assigned (when it gets assigned)
- [ ] When a task is deleted from Dynamo, trigger a message that will fire a lambda to remove any images associated to it from S3
- [ ] Instead of having S3 run the resizer automatically on upload, evaluate the size of the image in your Java code and then send a message to a Q, that will in turn trigger the lambda resizer -- only when the image > 350k

## Setup
> To be added

## To Run The App
> To be added

