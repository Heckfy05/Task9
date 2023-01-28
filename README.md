### Task 9 Jenkins/-CI pipelines/Groovy

For [hometask 9](https://docs.google.com/presentation/d/1v2O3_MNAStNx_guK_Ci9LrDgJ4037eTg/edit#slide=id.p15), we need to deploy the Jenkins server and configure the multi-branch pipeline for the GitHub repository.
    
1. On AWS machine was launched EC2 instance with Ubuntu 22.04 LTE on in. Folowing [official documentation](https://www.jenkins.io/doc/book/installing/linux/#debianubuntu) was deployed Jenkins server ![Jenkins](https://github.com/Heckfy05/Task9/blob/main/img/Jenkins.png?raw=true).
2. In Jenkins was configured Multibranch pipline and connected with GitHub [project](https://github.com/Heckfy05/Task9) repository with the [Jencinsfile](https://github.com/Heckfy05/Task9/blob/main/Jenkinsfile). Jenkins file had a few stages and used branch conditions and systems vars.
   ![main](https://github.com/Heckfy05/Task9/blob/main/img/MainPipline.png?raw=true)
   ![Develop](https://github.com/Heckfy05/Task9/blob/main/img/DevelopPipline.png?raw=true)
   Logs could be found [here](https://github.com/Heckfy05/Task9/tree/main/Logs)
3. Was implemented telegram notification![Telgram notification](https://github.com/Heckfy05/Task9/blob/main/img/Telegram%20notice.png?raw=true)
