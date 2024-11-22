# Web-App-For-Startup-Business
This project is about building a simple website and deploy it on a web app on Azure , this website for a startup company which work in graphic desings .
the idea is based on that the employers can finish thier designs from home and upload this designs in this website .
so , we create a storage account and create a file share  which will be mounted on the HR pc , we connect this file share to the website 
now if any employer upload a designs the designs immediately will be on the file share which was mounted on the HR pc .
and to avoid any person not working in the company to enter the website ,then we enable SSO ( Single Sign ON )
so now the only users who are in the tenant of the company in azure can sign in for the website , so no one can enter the website except the users of the company 

- you can enter the web site from this link ” https://fileuploadapp-e2fshbdse0eaf9ag.westeurope-01.azurewebsites.net/ “
users on the Egypt University of Informatics tenant on azure only can login to this website 
