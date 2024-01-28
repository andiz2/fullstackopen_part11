This applications has been developed in a new programming language named Python.
To make our code more stylistic and for identifying bugs and errors in our code we will
use some analysis tools called 'linters'.
For Python the most popular linters are Pylint and Flake8.
- Pylint looks for errors, enforces a coding standard that is close to PEP8,
and even offers simple refactoring suggestions.
- Flake8 wrapper aroud PyFlakes, pycodestyle and McCabe; this will check Python
source code for errors and violations of some of the PEP8 style conventions.

In VSCode we can set our linter preference by opening that command palette 
with CTRL + SHIFT + P and clicking on Python: Select Linter. We can select 
the linter we want to use.

Regarging to CI we can use the following alternatives to Jenkins or Github Actions:
CircleCi, Azure Pipelines, GitLab CI, GitLab, Airflow.
One of Jenkins advantages is that is based on Java and in opensource.
AWS CodePipeline can be integrated with AWS CodeCommit, GitHub, Amazon ECR
and Amazon S3.
This service offers parallel execution to increase the speed of the workflow.
Status notifications can be send to team members via Amazon SNS.

Noticing that our service is built in Python best fit for it would be Jenkins.
Speaking to a hosting solution I would say a cloud-based one is the best fit.
You can use Amazon Elastic Compute Cloud(Amazon EC2) to deploy a Jenkins
application on AWS
