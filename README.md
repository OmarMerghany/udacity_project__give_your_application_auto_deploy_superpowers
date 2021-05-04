## Give your Application Auto-Deploy Superpowers

In this project, you will prove your mastery of the following learning objectives:

- Explain the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.
- Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.
- Utilize a configuration management tool to accomplish deployment to cloud-based servers.
- Surface critical server errors for diagnosis using centralized structured logging.


### Project Submission

Submission:

- A text file named `urls.txt` including:
  1. Public Url to GitHub repository (not private) [https://github.com/OmarMerghany/udacity_project__give_your_application_auto_deploy_superpowers]
  1. Public URL for S3 Bucket (aka, green candidate front-end) [https://udapeople-prod-8d416ce7-d0f4-455e-ae2a-3579f2f0f8fc.s3-us-west-2.amazonaws.com/index.html#/employees]
  1. Public URL for CloudFront distribution (aka, blue production front-end) [https://d2kuk4xcvuooy6.cloudfront.net/]
  1. Public URLs to deployed application back-end in EC2 [http://ec2-34-213-50-237.us-west-2.compute.amazonaws.com:3030/]
  1. Public URL to Prometheus Server [http://34.221.181.186:9090/graph]
- These screenshots is included in the code repository in the root folder.
  1. Job failed because of compile errors. [SCREENSHOT01.PNG]
  1. Job failed because of unit tests. [SCREENSHOT02.PNG]
  1. Job that failed because of vulnerable packages. [SCREENSHOT03.PNG]
  1. An alert from one of failed builds. [SCREENSHOT04.PNG]
  1. Appropriate job failure for infrastructure creation. [SCREENSHOT05.PNG]
  1. Appropriate job failure for the smoke test job. [SCREENSHOT06.PNG]
  1. Successful rollback after a failed smoke test. [SCREENSHOT07.PNG]  
  1. Successful promotion job. [SCREENSHOT08.PNG]
  1. Successful cleanup job. [SCREENSHOT09.PNG]
  1. Only deploy on pushed to `master` branch. [SCREENSHOT10.PNG]
  1. Provide a screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage. [SCREENSHOT11.PNG]
  1. Provide a screenshot of an alert that was sent by Prometheus. [SCREENSHOT12.PNG]

- Presentation is in PDF format named "presentation.pdf" and is included in the code repository root folder. 

### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool

### License

[License](LICENSE.md)
