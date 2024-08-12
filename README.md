# sonar-qube-email-alert
SonarQube email alerts are designed to keep you informed about important developments in your code quality management process. These notifications are sent directly to your email, ensuring that you stay updated on critical issues and changes without needing to constantly monitor the SonarQube dashboard.


Admin Level Configuration:
1. Login as Admin
2. Click on Administration > under Configuration > in General > scroll down for the Email section 
3. Configure with gmail:
  A. SMTP host: smtp.gmail.com
  B. SMTP port: 465
  C. Secure connection: ssl
  D. SMTP username: sample@highradius.com
  E. SMTP password: Need to create an app password.( Go to Google Account → Security → configure a app password)
  F. From address: sample@highradius.com
  G. From name : SonarQube
  H. Email prefix : [SONARQUBE]

Note: If you have configured mail correctly, you can test your connection with Test Configuration by providing your mail ID. If configured right it will send a test email on the provided mail and notify you else it will prompt an error message.

User Level Configuration
=========================

5. Now log out with admin and log in with the newly created/pre-existed user and click on My Account from your account section top right corner → Click on Notification

6. For Overall notification you can opt as per requirement and for project-specific you can  search your project and configure 

7. In the Notifications per project section → Click on Add a project → Search for Respective      Project with Sonar Project Name → Click on Add

8. Give a tick mark to all options under the project.

9. Repeat the above process to add multiple projects.
    
10. Scan your project with Sonar Scanner, You will get emails on subscribed user mail.

11. SonarQube notifies the user whenever any quality gate parameters fail in the New Code.




