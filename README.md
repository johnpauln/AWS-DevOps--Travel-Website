# AWS- DevOps--Travel-Website
In this project I used devops tools and best practices to deploy a travel website to AWS. Most importantly I bult 3 pipelines that:
 Automate deployment through CI/CD pipelines. 
1. The CI pipeline into production builds the website on the fly and runs unit tests before every pull request enters review. 
2. The CD pipeline automates deployment of the website artifacts into AWS via terraform.
3. Then a separate pipeline runs daily to merge the master branches from each development team into an integration environment that runs integration tests and reports failure to appropriate team members. 



# Tools And Resources Used:
1. AWS
2. Docker 
3. Docker Compose
4. Jenkins
5. Selenium, Rspecy and Capybara.
6. Terraform
