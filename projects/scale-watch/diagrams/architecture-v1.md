# Scale Watch Architecture v1
                 
                 
                 AWS Region
                     │
                   VPC
                     │
        ┌────────────┴────────────┐
        │                         │
   Availability Zone A      Availability Zone B
        │                         │
      EC2                     EC2
        ▲                         ▲
        └──── Application Load ───┘
              Balancer (ALB)
        │                         │
   RDS Primary            RDS Standby
