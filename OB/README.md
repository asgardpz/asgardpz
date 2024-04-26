IBASE OBSERVER CONNECT 

System Design Specification 

1  Home 

The main screen briefly explains the purpose of the system. The menu at the top allows you to choose to login or password reset. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/1.jpg)

1.1 Login 

   After entering your account and password, you can log in to the system. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/1.1.jpg)

1.2. Password reset 

   If you forget your password, you can reset it through your authentication mailbox. 

1.2.1 Enter the authentication email and click Password Reset. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/1.2.1.jpg)

1.2.2 After receiving the letter in the authentication mailbox, click Reset Password. This password reset link will expire in 60 minutes. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/1.2.2.jpg)

1.2.3 Enter the new password and new password confirmation to reset your password. If you suddenly remember your old password, you can log in again before confirming it. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/1.2.3.jpg)

2  Dashboard 

The system page after successful login, the upper part displays the permissions/subscription identity and logout function, the left side is the system function menu, and the right side is the current function page. 

Click  【View On IBASE】  to link to the official website of IBASE. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/2.1.jpg)

2.1  Administrator 

The highest authority, and the new user is Power. Administrator is added by the system administrator. 

||Create |Edit |Delete |View |
| :- | - | - | - | - |
|User |O |O |O |O |
|Company |O |O |O |O |
|Action |O |O |O |O |
|Subscription |O |O |O |O |



||Create |Edit |Delete |View |Download |
| :- | - | - | - | - | - |
|Group Element |O |O |O |O |O |



||View |Sensor |Mail Slot |
| :- | - | - | - |
|Hardware Information |O |O |O |



||View |Command For Groups |Command For Systems |
| :- | - | :-: | :-: |
|Mail Slot |O |O |O |

![](https://github.com/asgardpz/asgardpz/blob/main/OB/2.1.jpg)

2.2 Power 

Secondary permissions can be added, deleted and modified, and the new user is User. 

||Create |Edit |Delete |View |
| :- | - | - | - | - |
|User |O |O |O |O |
|Company |X |X |X |X |
|Action |X |X |X |X |
|Subscription |X |X |X |X |



||Create |Edit |Delete |View |Download |
| :- | - | - | - | - | - |
|Group Element |O |O |O |O |O |



||View |Sensor |Mail Slot |
| :- | - | - | - |
|Hardware Information |O |O |O |



||View |Command For Groups |Command For Systems |
| :- | - | :-: | :-: |
|Mail Slot |O |O |O |

![](https://github.com/asgardpz/asgardpz/blob/main/OB/2.2.jpg)

2.3 User 

General permissions can only view and edit your own password. 

||Create |Edit |Delete |View |
| :- | - | - | - | - |
|User |X |X |X |O |
|Company |X |X |X |O |
|Action |X |X |X |O |
|Subscription |X |X |X |O |



||Create |Edit |Delete |View |Download |
| :- | - | - | - | - | - |
|Group Element |X |X |X |O |X |



||View |Sensor |Mail Slot |
| :- | - | - | - |
|Hardware Information |O |O |X |



||View |Command For Groups |Command For Systems |
| :- | - | :-: | :-: |
|Mail Slot |O |X |X |

![](https://github.com/asgardpz/asgardpz/blob/main/OB/2.3.jpg)

3.1 User 

The main functions have been Create, Reset, Delete, View and are controlled according to permissions. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.1.jpg)

User permissions can only view their own Profile and Reset their own  Password. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.1.U.jpg)


3.1.1 Create 

   Select Company, enter E-mail and Password to add a new User. Administrator adds a User with Power permissions, and Power adds a User with User permissions. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.1.1.jpg)

3.1.2 Reset 

   Reset Password, Administrator can modify the User Password of all Companies, Power can modify the User Password of its own Company, and User can only modify its own User Password. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.1.2.jpg)

3.1.3 Delete 

   Administrator can delete all Users other than the own Company, and Power can delete Users other than the own Company. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.1.3.jpg)

3.2 Group Element 

   The main functions have been Create, Reset, Delete, View, Download and are controlled according to permissions. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.2.jpg)

3.2.1 Create 

   Enter the Group Name and Description to add a new one. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.2.1.jpg)

3.2.2 Edit 

   Group Name and Description can be modified. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.2.2.jpg)

3.2.3 Delete 

   Delete Group Element. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.2.2.jpg)

3.2.4 Download 

   Download Vendor Key File. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.2.4.jpg)

3.3 Hardware Information 

   Can view Hardware Information and use Sensor and Mail Slot functions. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.3.jpg)

3.3.1 Sensor 

   You can view the statistical chart of Hardware’s Temperature CPU Chart, Temperature System Chart, CPU Fan Speed Chart, System Fan Speed Chart, and CPU Usage Chart within 8 hours. This statistical chart is updated every minute and can be zoomed in, zoomed out, and panned. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.3.1.jpg)

3.3.2 Mail Slot 

   The Command For Hardware function can be used. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.3.2.jpg)

3.4 Mail Slot 

   Can view Mail Slot, Administrator and Power permissions can use Command for Groups, Command for Systems. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.4.jpg)

3.4.1 Command For Groups 

   You can select all or specified Group Element commands. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.4.1.jpg)

3.4.2 Command For Systems 

   You can select all or specified Hardware-Group Element commands. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.4.2.jpg)

3.5 Company 

   You can Create, Edit, Delete and View Company information. This function is limited to Administrator. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.5.jpg)

3.5.1 Create 

Enter the Company Name to add it. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.5.1.jpg)

3.5.2  Edit 

Company Name can be modified. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.5.2.jpg)

3.5.3 Delete 

Delete Company. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.5.3.jpg)

3.6 Action 

   You can Create, Edit, Delete and View Action information. This function is limited to Administrator. The default cannot be Edit or Delete. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.6.jpg)

3.6.1 Create 

After entering the Action Name, you can add Action data. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.6.1.jpg)

3.6.2  Edit 

Action Name can be modified. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.6.2.jpg)

3.6.3 Delete 

Delete Action. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.6.3.jpg)

3.7 Subscription 

   You can Create and Edit the Subscription of the specified User. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.7.jpg)

3.7.1 Create 

You can select unsubscribed Users to perform the subscription function. The subscription function is divided into Month and Year. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.7.1.jpg)

3.7.2.  Edit 

Subscribed User can be modified to Month or Year. 

![](https://github.com/asgardpz/asgardpz/blob/main/OB/3.7.2.jpg)

----
