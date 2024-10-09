# JetSweep Cost Optimzation Scan

## About
The JetSweep Cost Optimzation Scan will deploy the needed connections to allow our tooling to review your AWS Workloads and billing information. JetSweep will then be able to provide an AWS Cost Optimzation Report and Recommendations. 

This solution will utilize an AWS CloudFormation Template to configure the reqirements in your AWS Account and to connect to our tooling.  

## Deployment
Sign into your AWS Management Console within the same web browser. Click on the button below to launch the `jetsweep-cc.yaml` AWS CloudFormation Template. To open a new Tab, right click on `Launch Stack` and select "Open in new Tab".  
[![Stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=JetSweepCostOptimzation&templateURL=https://jetsweep-cc.s3.amazonaws.com/jetsweep-cc.yaml)

You can also [download the template](https://github.com/bmacdonald-jetsweep/jetsweep-cost-optimization/blob/main/jetsweep-cc.yaml) if you would like to run manually.  

1.  Click Next on the AWS CloudFormation Create Stack page.  
![Alt text](https://github.com/bmacdonald-jetsweep/jetsweep-cost-optimization/blob/main/images/cf-create-stack.png)  

2.  Use the default settings unless you would like to change the name of the CloudFormation Template.    
![Alt text](https://github.com/bmacdonald-jetsweep/jetsweep-cost-optimization/blob/main/images/cf-stack-details.png)

3.  On the Configure stack options page you can use the default settings and then click Next.  
![Alt text](https://github.com/bmacdonald-jetsweep/jetsweep-cost-optimization/blob/main/images/cf-stack-options.png)

4.  Select "I acknowledge the AWS CloudFormation might create IAM resources with custom names". Click on Finish on the Review page to launch the template.  
![Alt text](https://github.com/bmacdonald-jetsweep/jetsweep-cost-optimization/blob/main/images/cf-create-review.png)  

If you recieve an error in AWS CloudFormation please contact your JetSweep contact who provided you access to this solution.

## Cost Optimization Report and Recommendations
Once you have deployed the solution, please contact your JetSweep Contact.  They will confirm our tool's access to your AWS Account and will start the report process.  
