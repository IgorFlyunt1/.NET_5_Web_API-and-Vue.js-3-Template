# ASP.NET 5 and Vue.js-3 - Template

The structure of the project looks like the image below, having the following items:


ClientApp folder
ClientApp folder with the Vue JS 3.0 application, including:

Counter, Fetch Data, Nav Menu and Home components
2. Vue Router and Axios installed (Vue JS 3.0 version)

3. Router folder

Asp.Net Core 5.0 Web API
API Controller with Forecast API presented on the standard underlying project.

![image](https://user-images.githubusercontent.com/67701529/177553356-9855a4ec-66ca-4021-97c9-3638373042f8.png)


All the extra needed settings on Asp.Net Core Startup file were already made as well on Startup.cs, including the mandatory packages for Vue JS SPA Middleware:

![image](https://user-images.githubusercontent.com/67701529/177553485-f0553254-af33-4adc-96b8-09d278677c2b.png)
ConfigureServices method

![image](https://user-images.githubusercontent.com/67701529/177553536-ba62b54c-84a3-4328-a834-3657efd315d9.png)
Configure method


Run the project
After creating the project, the only thing that you need to do is running it. If the node packages are not installed yet, the application will run npm install under the folder “ClientApp”, as seen in the following image:
![image](https://user-images.githubusercontent.com/67701529/177553943-fecc9377-4af0-46ea-b974-fbde94e6c320.png)



After the installation of all npm packages, the application will start as it follows:
![image](https://user-images.githubusercontent.com/67701529/177553663-f66de626-ab08-42fe-834a-c42f01f63f03.png)
![image](https://user-images.githubusercontent.com/67701529/177553703-083b6259-fbbe-4487-bf1e-0a425809240d.png)



Conclusion
I hope that helps you in your daily routine as a software developer, being important stuff to save your time every time you have to create Vue JS 3.0 + Asp.Net Core 5.0 application.
