# Docker-ECR-Demo
Steps for pushing a Docker Image to ECR

## 1. Create Repo in ECR with AWS CLI
aws ecr create-repository --repository-name predict-weather --region us-east-1

## 2. List repos to validate
aws ecr describe repositories --region us-east-1

## 3. Build Docker Image
docker build -t my-first-repo .

## 4. Run Image to Validate
docker run

## 5. Push Docker Image to Repo
Push Commands can be found for specific region in "Push Commands" within ECR Repo


## Other Resources
https://www.youtube.com/watch?v=Yy9AGt4m0_I
