You can document constants using the following two ways:
# Document with a Table

| Name | Description | Type | Value |
| ---- | ----------- | ---- | ----- |
| commMoveBackward | Command code to send to the robot to move it backward. | Number | 0x02 |
| commMoveBackward | Command code to send to the robot to move it forward.  | Number | 0x02 |
| commStop | Command code to send to the robot to stop it from moving. | Number | 0x00 |
| commTurnLeft | Command code to send to the robot to turn it left. | Number | 0x03 |
| commTurnRight | Command code to send to the robot to turn it right. | Number | 0x04 |
| errBadCommand | Error code that the robot sends back to indicate that it does not recognize the command you sent. | Number | 0xFF02 |
| errBadSignal | Error code that the robot sends back to indicate that it does not receive a good signal from the device. | Number | 0xFF01 |
| errBatteryLow | Error code that the robot sends back to indicate that its batteries are low. | Number | 0xFF03 |
| productName | Product name for the robotic ball. | String | RoboBall |
| versionNumber | SDK version number. | Number | 1.6

# Document with Code 
`const commMoveBackward = 0x02;`

Command code to send to the robot to move it backward.


`const commMoveForward` = 0x01;

Command code to send to the robot to move it forward.


`const commStop = 0x00;`

Command code to send to the robot to stop it from moving.


`const commTurnLeft = 0x03;`

Command code to send to the robot to turn it left.


`const commTurnRight = 0x04;`

Command code to send to the robot to turn it right.


`const errBadCommand = 0xFF02;`

Error code that the robot sends back to indicate that it does not recognize the command you sent.


`const errBadSignal = 0xFF01;`

Error code that the robot sends back to indicate that it does not receive a good signal from the device. 


`const errBatteryLow = 0xFF03;`

Error code that the robot sends back to indicate that its batteries are low.


`const productName = "RoboBall";`

Product name for the robotic ball.


`const versionNumber = 1.6;`

SDK version number.







