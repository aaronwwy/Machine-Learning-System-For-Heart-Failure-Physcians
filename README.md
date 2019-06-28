# MACHINE-LEARNING-SYSTEM-FOR-HEART-FAILURE-PHYSICIANS
A PREDICTIVE TOOL AND USER-FRIENDLY INTERFACE - MACHINE LEARNING 

* This is project I did in Spring 2013 when I was graudate student in Computing and Information Science of University of Pittsburgh


Steps to deploy our project
1. Put  under D:\
2. Put  under D:\ (If you do not have Microsoft Access 2010, please ignore this step)
3. Configure TomCat (You can ignore this step if you already have TomCat on your computer)
•	Down load TomCat 6 in website below, choose 32-bit or 64-bit the same as your windows system
http://tomcat.apache.org/download-60.cgi
 
•	Unzip it and put this folder   at somewhere on your computer (e.g. D:\)
4. If you have Microsoft Access 2010 in your computer, put this folder test14 which under folder haveAccess2010 to D:\apache-tomcat-6.0.36\webapps. Otherwise, put the folder test14 which under folder don’tHaveAccess2010 to D:\apache-tomcat-6.0.36\webapps.
5. Open D:\apache-tomcat-6.0.36\bin\startup.bat, leave it there, don’t close the window.
 
6. Open your browser, input “localhost:8080/test14” in your address bar. (Firefox recommended, other browsers may have slightly non-perfect layout). There will show our input page.

7. Please at least input Age, Gender, TBILI, PLT, PA diastolic, Diuretic
(To test function “similar patients”, please input age:22, gender: male, TBILI:2.5, PLT: 380, PA diastolic: 33, Diuretic: YES; you can also input other values, these specific value make sure there are similar patients)
8. Click “submit”, there will be output page. (Please maximize the window. There is still a little bug that everything will be squeezed together when you zoom out the window.)
(If you do not have Microsoft Access 2010, then this page cannot show the results of the similar patients.)
 
IMPORTANT
Every time you try to see the project, you need to open D:\apache-tomcat-6.0.36\bin\startup.bat, then input “localhost:8080/test14” in the address bar of the browser. When you finished, you can open D:\apache-tomcat-6.0.36\bin\shutdown.bat to close the window below.
 
