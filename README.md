# Terraform - Provision - EKS Cluster

# Deploying container insight for eks monitoring

aws iam attach-role-policy \
--role-name my-worker-node-role \
--policy-arn arn:aws:iam::aws:policy/CloudWatchAgentServerPolicy 


aws eks create-addon --cluster-name dominion-cluster --addon-name amazon-cloudwatch-observability



