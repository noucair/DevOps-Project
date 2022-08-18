In this Project I have used the Git/GitHub, Jenkins and Docker and integrated all these technologies to create an automated system for AutoDeployment
![1_5KrnYBdcwr5hpi8N4KKOyQ](https://user-images.githubusercontent.com/59423217/185509090-5e46b390-e768-4413-a507-08158e10d004.png)

The Project which I have created is a very basic integration in DevOps Domain. In this Project, when the developer will commit the code, it will automatically push the code in backend to the respective GitHub Repository. Using the WebHooks from GitHub, as soon as the developer pushes the code, it will be send to Jenkins Workspace automatically and then Jenkins Jobs will be triggered automatically as per the Jobs queue. Also I have used the concept of Build Pipeline so that it will be easy to monitor the Jobs.<br><br>
For building this project I have used this project:<a href="https://github.com/noucair/my-portfolio">my portfolio</a>, where I practise DevOps tasks.

<b>Job-1</b> - This Job will copy the Code which GitHub send to Jenkins to the required WorkSpace/folder.<br>
![pic1](https://user-images.githubusercontent.com/59423217/185508362-a4ff8441-fe78-4738-b42c-fa73baee3342.PNG)
<hr>
<b>Job-2</b> - This Job will Launch the Docker Container having the specifications to deploy the website within it.<br>

![pic2](https://user-images.githubusercontent.com/59423217/185508419-af246854-efb7-4b14-8e1d-ae6a7f8a731a.PNG)
<hr>
<b>Job-3</b> - This Job will be used to test the website weather it is working properly or not.<br>

![pic3](https://user-images.githubusercontent.com/59423217/185508437-6fada4ac-4450-4776-bfd7-ba867120d6a2.PNG)
<hr>
And the best thing about all these Jobs is that it all will be automatically triggered as soon as the developer pushes the code to GitHub Repository.

![jenkins pic](https://user-images.githubusercontent.com/59423217/185508524-a6805da6-39c7-47aa-82c7-1e6e6acde493.PNG)
<hr>

