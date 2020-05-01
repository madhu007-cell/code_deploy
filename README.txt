Welcome to the Exercise files for the Pluralsight course "DevOps on AWS: Getting Started", module "Deploying Apps with CodeDeploy".

In the "codedeploy-agent-install-scripts" directory, you'll find codedeploy-agent installation scripts for RedHat, Debian, and Windows systems. 

If you'd like to deploy the sample application that was used in the course, you'll find it in the "globomantics-web" directory. You can add these files to GitHub or to a ZIP file stored in s3, and then target it as a revision. Remember that the directory where the "appspec.yml" file lives should be the root of the repository or zip file. 

The "codedeploy_autoscale_classic_elb.yml" file is a CloudFormation script that you can use to spin up an autoscaling group of ec2 instances running Amazon Linux 2 with the codedeploy-agent installed, and ready to be targeted by the CodeDeploy service. It supports the regions "us-east-1" and "us-east-2" and the instance types "t3.nano, t3.micro, and t3.small".

If you have any questions, or feedback on the course, please let me know! You can reach me in the course Discussion tab or via Twitter @WesleyTech

Happy Learning!
- Wes Novack
