This ZIP file contains the solution submission by INFOSYS 300/SOFTENG 762 Group 1. 
The solution includes a UiPath Automation Programme that log into iPayroll (the payroll system for company: NZ TRT Ltd), extract leave data for its employees in the following 30 days, and update the leave data as appointments in the outlook calendar. 
The leave data manipulation includes adding new generated leaves, deleting leaves that has been cancelled and color coding appointments for employees from different departments. 
The main components of this ZIP file are {project.json} that holds the uiPath project dependencies, a {Main.xaml} file that serves as the entrance to run the programme, and {workflows} folder that contains the sequence files to build up the entire automation process.

This solution is designed to only be operable on an authenticated machine from our client NZ TRT Ltd, this is because the login process into their ipayroll account requires 2FA code authentication, which can only be generated from the verfied machine locally in real time. 
To run this solution requires connecting to the verified machine through TeamViewer. Then, unzip this folder locally and start uiPath Studio, open the project with the directory of {project.json}. And click "Run" button on the top left options bar. 
Note: the first time running the solution on the machine, the initial user may be required to enter appropriate outlook account info.

Several steps above require privileged account details of NZ TRT, to get full access please contact our proeject sponsor John James
Contact Infomation shows below:

Email: Johnj@trt.co.nz
Contact Number: 07 849 4839

The required credentials are:

Teamviewer TV ID and TV Password;
NZ TRT Machine name and password;
Outlook account and password;
