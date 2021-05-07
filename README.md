## Give your Application Auto-Deploy Superpowers
[![CircleCI](https://circleci.com/gh/OmarMerghany/udacity_project__give_your_application_auto_deploy_superpowers.svg?style=svg)](https://circleci.com/gh/OmarMerghany/udacity_project__give_your_application_auto_deploy_superpowers)

Project objectives:

- Explain the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.
- Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.
- Utilize a configuration management tool to accomplish deployment to cloud-based servers.
- Surface critical server errors for diagnosis using centralized structured logging.


### Project Submission

Submission:

- These screenshots is included in the code repository in the root folder.
  1. Job failed because of compile errors. [SCREENSHOT01.PNG]
  2. Job failed because of unit tests. [SCREENSHOT02.PNG]
  3. Job that failed because of vulnerable packages. [SCREENSHOT03.PNG]
  4. An alert from one of failed builds. [SCREENSHOT04.PNG]
  5. Appropriate job failure for infrastructure creation. [SCREENSHOT05.PNG]
  6. Appropriate job failure for the smoke test job. [SCREENSHOT06.PNG]
  7. Successful rollback after a failed smoke test. [SCREENSHOT07.PNG]  
  8. Successful promotion job. [SCREENSHOT08.PNG]
  9. Successful cleanup job. [SCREENSHOT09.PNG]
  10. Only deploy on pushed to `master` branch. [SCREENSHOT10.PNG]
  11. Provide a screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage. [SCREENSHOT11.PNG]
  12. Provide a screenshot of an alert that was sent by Prometheus. [SCREENSHOT12.PNG]

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
