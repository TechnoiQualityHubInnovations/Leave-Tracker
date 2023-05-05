# PTO Manager Application
![image](https://user-images.githubusercontent.com/48203727/236288415-68e0746b-b53d-4b9d-9b9a-dd17cda95a7e.png)



# Introduction 
The PowerApp-based Leave Tracker application is a comprehensive and user-friendly solution designed to simplify the process of managing employee leave requests and company holidays. Built using Microsoft's PowerApps platform, the application provides an easy-to-use interface that allows employees to submit their leave requests, while also giving managers and HR teams the ability to approve or reject requests quickly and efficiently.

# Why our Leave Tracker

✔️ PowerApps is built on top of existing Microsoft subscriptions makes it easy to integrate with other Microsoft services and tools. This allowed us to seamlessly        integrate the Leave Tracker application with other Microsoft applications such as SharePoint and Teams, and to leverage existing subscriptions and licenses for        these services.

 ✔️ Application own amazing UI Components from which we can create rich interactive dashboards and materialistic UI screens.
   
 ✔️ Plug and Play components.

# Pre-requisite
Subscription: 
          Any Microsoft subscription service included with PowerPlatform service 

# Technology Stack
  - Power Apps Version-23044
  - Power Automate Version-2301.4
          
 # Application Frontend Development Overview - PowerApps
 ## Landing Page 
 
 The frontend of the Leave Tracker application is designed with a user-centric approach, providing a simple and intuitive interface for employees to manage their leave     requests, view company holidays, and track their leave balances. 
  
- The landing page for the Leave Tracker application presents users with two options: to login as a regular user or to login as a privileged user. Regular users can access the application to manage their own leave requests, view company holidays, and track their leave balances. Privileged users, on the other hand, have additional access and permissions to manage leave requests for their team members, view team member availability, and generate reports on employee leave and attendance.

- Both options are easily accessible on the landing page, with clear and concise labels to guide users to the appropriate login page. Users can simply click on the option that corresponds to their role to access the relevant login page and begin using the application.

![image](https://user-images.githubusercontent.com/48203727/236295416-48dacf3b-59bd-4246-b940-1ea36c0dfafb.png)

- Upon logging in to the Leave Tracker application, users are presented with a personalized dashboard that includes three main components: My Requests, My Leave Balance, and Company Holidays and option for users to Logout 

  ![image](https://user-images.githubusercontent.com/48203727/236299074-dd88f873-72a8-46fe-91fe-9d1e3c5c5f0e.png)

 -  The My Requests component provides users with an overview of their leave requests, displaying the status of each request and allowing users to view details and         history for each request. Users can also submit new leave requests directly from this component.
    ![image](https://user-images.githubusercontent.com/48203727/236304553-34993c17-6721-4c33-b78b-6fd1f0bceda0.png)

 -  The My Leave Balance component shows users their current leave balance, including the number of days taken and remaining, and any adjustments or accruals. This        information helps users plan their leave requests more effectively and avoid overbooking or exceeding their allotted leave.
 
 -  The Company Holidays component displays a calendar of company holidays and other important dates, providing users with a clear overview of when the company is         closed and when they can plan their leave around these dates.

     ![image](https://user-images.githubusercontent.com/48203727/236303966-01530341-dcab-47eb-83e4-f8ec99b68ce9.png)

The Leave Tracker application also features a "New Request" button on the dashboard, which is enabled by default upon login. This button allows users to quickly and easily submit a new leave request, without having to navigate to a separate page or menu.

![image](https://user-images.githubusercontent.com/48203727/236296542-b785883c-3f68-4c9b-b2d6-a40264bf0603.png)

Clicking on the "New Request" button brings up a form where users can select the type of leave they want to request, specify the start and end dates, and provide any additional details or comments. Once the request is submitted, it is automatically added to the user's list of requests in the My Requests component

 ##  Privilege User - Dashboard for Approving the Leave
![image](https://user-images.githubusercontent.com/48203727/236310144-59b6b94a-3065-4bd4-8f96-2b0aa961d6bf.png)

#  Backend - Power Automate Flow & Sharepoint 

Power Automate allowed us to create the workflows necessary for the application, such as the workflow for submitting, reviewing, and approving leave requests. We were able to create decision points in the workflow to allow managers to review and approve or reject leave requests based on various factors such as the employee's leave balance, workload, and team requirements.
  ![image](https://user-images.githubusercontent.com/48203727/236312570-2d27294c-5b15-46b3-abe4-76f803e1d037.png)
  
SharePoint provided the data storage and management capabilities for the Leave Tracker application. We used SharePoint lists to store the user information, leave requests, and other data relevant to the application. This allowed us to easily manage and retrieve the data, as well as provide access control and security features to ensure that the data was only accessible to authorized personnel.


  
# Security and Privacy 
  - Security and privacy are crucial considerations for any application, and the Leave Tracker application is no exception. In the development of this application, we     have implemented various security measures to ensure the confidentiality and integrity of the data and user information.

  - In the Leave Tracker application, we have implemented RBAC by defining different user roles and assigning specific permissions to each role. Regular users are         given access to the leave request submission and tracking features, while managers and privileged users are given access to additional features such as the             approval and rejection of leave requests and the management of user data.

  - Furthermore, we have implemented access controls based on the individual user's role and permissions. This ensures that regular users cannot access or modify data     or workflows that they are not authorized to, and that managers and privileged users can only access the data and workflows that are relevant to their roles.
  
  - All user data and application data are stored in a secure, cloud-based database (Sharepoint) that is protected by advanced encryption and access controls. This         ensures that user information and leave requests are kept confidential and are only accessible to authorized personnel.







