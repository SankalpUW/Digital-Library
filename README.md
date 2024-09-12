# DigiLibrary

Digital online library where users can create books, share them with other users, borrow, return and give feedback on books! The backend of the project was built using SpringBoot, and the frontend was built with Angular. I used jwt tokens for securing the application, and used jsr and spring validation for data validation. For the email service, I used Java Mail Sender.

## Steps to run the app

I'm currently trying to setup a proxmox server on an old laptop that I can use as my server, since I couln't find any great ways to deploy backend for free. Here are the steps to run the app on your local machine:

1. Clone the repository on your local machine
2. In the root directory, run:  ``` docker compose up -d ```
3. In the frontend directory, run ```npm install```
4. In the root directory, run ```mvn clean install```
5. Now run the BookNetworkApiApplication.java file, which will get the spring boot backend running
6. Then run ```ng serve``` in the frontend directory
7. You can now access the login page at "localhost:4200/login", and the mail service will be at "localhost:1080"

![image](https://github.com/user-attachments/assets/bdac45df-7ce7-41f0-8b9f-218fb7626d65)


![image](https://github.com/user-attachments/assets/5d0e0754-d9ff-4b6a-bd85-2b283d046532)


![image](https://github.com/user-attachments/assets/bcbf362b-ea51-4965-8240-de80737e6218)


