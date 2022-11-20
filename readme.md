# Web Identity Federation

---
### Original Source
- [aws-cognito-web-identity-federation](https://github.com/acantril/learn-cantrill-io-labs/tree/master/aws-cognito-web-identity-federation)
---

In this advanced demo series you will be implementing a simple serverless application which uses Web Identity Federation.  
The application runs using the following technologies

- S3 for front-end application hosting
- Google API Project as an ID Provider
- Cognito and IAM Roles to swap Google Token for AWS credentials

The application runs from a browser, gets the user to login using a Google ID and then loads all images from a private S3 bucket into a browser using presignedURLs.

This advanced demo consists of 6 stages :-

- STAGE 1 : Provision the environment and review tasks 
- STAGE 2 : Create Google API Project & Client ID
- STAGE 3 : Create Cognito Identity Pool
- STAGE 4 : Update App Bucket & Test Application
- STAGE 5 : Cleanup the account

![Architecture](ArchitectureEvolution.png)

## Instructions

- [Stage1](02_LABINSTRUCTIONS/STAGE1%20-%20Provision%20and%20Discuss%20Architecture.md)
- [Stage2](02_LABINSTRUCTIONS/STAGE2%20-%20Create%20Google%20APIProject%20and%20Client%20ID.md)
- [Stage3](02_LABINSTRUCTIONS/STAGE3%20-%20Create%20Cognito%20Identity%20Pool.md)
- [Stage4](02_LABINSTRUCTIONS/STAGE4%20-%20Update%20App%20Bucket%20and%20Test%20Application.md)
- [Stage5](02_LABINSTRUCTIONS/STAGE5%20-%20Cleanup.md)



## 1-Click Installs
Make sure you are logged into AWS and in `us-east-1`  

- [WEBIDF](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/quickcreate?templateURL=https://learn-cantrill-labs.s3.amazonaws.com/aws-cognito-web-identity-federation/WEBIDF.yaml&stackName=WEBIDF)

## Video Guides

- [STAGE1](https://youtu.be/DyiJZz07g_E) - SETUP
- [STAGE2](https://youtu.be/wWQ8lgqa4fo) - Google API project
- [STAGE3](https://youtu.be/MXkqOgXkwRQ) - Cognito Identity Pool
- [STAGE4](https://youtu.be/YkDImYUcY3U) - Configure and Test Application
- [STAGE5](https://youtu.be/aJALTW-F24g) - Cleanup

## Architecture Diagrams

- [Overall - PNG](02_LABINSTRUCTIONS/ARCHITECTURE-ENDSTATE.png)
- [Overall - PDF](02_LABINSTRUCTIONS/ARCHITECTURE-ENDSTATE.pdf)

- [Stage1 - PNG](02_LABINSTRUCTIONS/ARCHITECTURE-STAGE1.png)
- [Stage1 - PDF](02_LABINSTRUCTIONS/ARCHITECTURE-STAGE1.pdf)
- [Stage2 - PNG](02_LABINSTRUCTIONS/ARCHITECTURE-STAGE2.png)
- [Stage2 - PDF](02_LABINSTRUCTIONS/ARCHITECTURE-STAGE2.pdf)
- [Stage3 - PNG](02_LABINSTRUCTIONS/ARCHITECTURE-STAGE3.png)
- [Stage3 - PDF](02_LABINSTRUCTIONS/ARCHITECTURE-STAGE3.pdf)
- [Stage4 - PNG](02_LABINSTRUCTIONS/ARCHITECTURE-STAGE4.png)
- [Stage4 - PDF](02_LABINSTRUCTIONS/ARCHITECTURE-STAGE4.pdf)







