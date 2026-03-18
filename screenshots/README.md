
## 🎯 Target Group & Auto Scaling Group (ASG)

⚠️ Note:

The Target Group and Auto Scaling Group (ASG) were successfully configured and tested during deployment.  
However, the resources were later terminated as part of cost optimization and environment cleanup.

### ✔ What was implemented:

- Target Group attached to Application Load Balancer
- Health checks configured and verified
- EC2 instances registered automatically via ASG
- Traffic successfully routed from ALB → Target Group → Instances

### ✔ Validation performed:

- Application was accessible through Load Balancer DNS
- Instances passed health checks
- Traffic distribution confirmed

### 🧠 Engineering Note:

This reflects real-world cloud practice where non-production environments are decommissioned after validation to control costs.
