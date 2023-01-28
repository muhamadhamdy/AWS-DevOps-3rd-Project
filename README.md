## Give your Application Auto-Deploy Superpowers

![Diagram of CI/CD Pipeline we will be building.](udapeople.png)


CI/CD selling proposal [presentation.pdf] 


- A text file named `urls.txt` including:
  1. Public Url to GitHub repository (not private) [URL01] https://github.com/muhamadhamdy/AWS-DevOps-3nd-Project
  1. Public URL for your S3 Bucket (aka, your green candidate front-end) [URL02] http://udapeople-d71cab2.s3-website-us-east-1.amazonaws.com/
  1. Public URL for your CloudFront distribution (aka, your blue production front-end) [URL03] https://du1f6vp68fzdd.cloudfront.net/
  1. Public URLs to deployed application back-end in EC2 [URL04] http://ec2-52-204-47-48.compute-1.amazonaws.com:3030
  1. Public URL to your Prometheus Server [URL05] http://ec2-34-207-227-198.compute-1.amazonaws.com:9090


- Screenshots 
  1. Job failed because of compile errors. [SCREENSHOT01]
  1. Job failed because of unit tests. [SCREENSHOT02]
  1. Job that failed because of vulnerable packages. [SCREENSHOT03]
  1. An alert from one of your failed builds. [SCREENSHOT04]
  1. Appropriate job failure for infrastructure creation. [SCREENSHOT05]
  1. Appropriate job failure for the smoke test job. [SCREENSHOT06]
  1. Successful rollback after a failed smoke test. [SCREENSHOT07]  
  1. Successful promotion job. [SCREENSHOT08]
  1. Successful cleanup job. [SCREENSHOT09]
  1. Only deploy on pushed to `main` branch. [SCREENSHOT10]
  1. Provide a screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage. [SCREENSHOT11]
  1. Provide a screenshot of an alert that was sent by Prometheus. [SCREENSHOT12]

- Your presentation should be in PDF format named "presentation.pdf" and should be included in your code repository root folder. 

Before you submit your project, please check your work against the project rubric. If you haven’t satisfied each criterion in the rubric, then revise your work so that you have met all the requirements. 

### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool

### License

[License](LICENSE.md)

[presentation.pdf]: presentation.pdf
[SCREENSHOT01]: screenshot01.jpg
[SCREENSHOT02]: screenshot02.jpg
[SCREENSHOT03]: screenshot03.jpg
[SCREENSHOT04]: screenshot04.jpg
[SCREENSHOT05]: screenshot05.jpg
[SCREENSHOT06]: screenshot06.jpg
[SCREENSHOT07]: screenshot07.jpg
[SCREENSHOT08]: screenshot08.jpg
[SCREENSHOT09]: screenshot09.jpg
[SCREENSHOT10]: screenshot10.jpg
[SCREENSHOT11]: screenshot11.jpg
[SCREENSHOT12]: screenshot12.jpg

