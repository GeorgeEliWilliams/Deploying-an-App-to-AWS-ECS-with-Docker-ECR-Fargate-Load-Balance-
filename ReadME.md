## RESOURCES
1. EC2
2. Docker : To build the image
3. ECR : Tostore the image
4. ECS :The image will be deployed here
5. Fargate
6. Application Load Balancer : Balanceraffic accross the tasks that willbe running in the ECS service

## FLOW OF EXECUTION

# Step 1
1. Launch EC2 Instance
2. Install docker
3. Build docker Image

# Step 2
1. Create ECR
2. Login to ECR
3. Tag image 
4. Push image into ECR

# Step 3
1. Create application load balancer

# Step 4
1. Create task definition 
2. Create ECS cluster
3. Create service

# Step 5
1. Validation