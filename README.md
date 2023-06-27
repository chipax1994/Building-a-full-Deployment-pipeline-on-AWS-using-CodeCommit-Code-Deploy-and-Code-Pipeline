# Building-a-full-Deployment-pipeline-on-AWS-using-CodeCommit-Code-Deploy-and-Code-Pipeline
*-  Configure Security and creating an SSH connection between code-commit and your laptop &&
    Create a CodeCommit Repository

*- Create an ECR-Repository,,, Configure CodeBuild to clone the repository, create a container image and store on ECR

*-  Configure a CodePipeline using a buildspec.yml file with commit and build steps to automate build on commit

*-  Create an ECS Cluster, Target-Group's , Application Load Balancer (ALB) and configure the code pipeline for deployment to ECS Fargate 
    using the imagedefinitions.json file

*- clean up the environment by deleting all the AWS resourses used
