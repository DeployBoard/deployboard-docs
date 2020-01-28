# Quick Start

The first time you log into DeployBoard you will be taken to your Dashboard which will be empty. You will need to send your first deployment event that will create an Application automatically.

When you send deployment data to DeployBoard, a few conditions could happen:  
```
1. If the application does not yet exist, it will create it for you with the data you sent.
2. If the application already exists:
  a. If the environment does not yet exist, it will create it for you within the application.  
  b. If the environment already exists, it will update that environment with the data you sent.
```
