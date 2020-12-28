# TestPushNotification
This app is for testing push(remote) notification which sending from remote server
1. Find the test.apns file which is the payload for your notification 
2. edit it to match your environment
3. run this command in your Terminal: xcrun simctl push <device ID> <app identifier> <payload file path. For example; /Users/YOU/Desktop/test.apns>
4. Or just drag the payload file into your simulator
