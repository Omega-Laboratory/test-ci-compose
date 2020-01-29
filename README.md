# test-ci-compose

# Connect to aws
$(aws ecr get-login --no-include-email --region us-east-2)

# Docker pull
docker pull <image uri>
  
  for examle: docker pull 951264400542.dkr.ecr.us-east-2.amazonaws.com/app2:latest
 
