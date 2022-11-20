# Lab 8 - Starter

## Nikhil Dange

1) Automated tests would be within the GitHub Action, since we want these to run every time we commit code. We do not want this to manually be run (since they are to be automated), and we want to incrementally test, not only at the very end.

2) No, E2E is to test the functionality of how an app works on a larger scale.

3) I would not use a unit test for message functionality. Message functionality seems like a far bigger feature of an application, and a unit test might fail to test things such as whether the message was recieved, or the contents were kept intact; a function on our side would only verify that a message was sent.

4) I would use a unit test for this feature, since this is a smaller feature to test. A function can easily check a message before it is sent to verify whether it is 80 characters, since we are not concerned with what happens after the message is sent.