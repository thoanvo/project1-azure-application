# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.
1. VM:
- Costs: $13.19 - $14.60 (A0)
- Scalability: 
	Autoscaling: VM scale sets
	Load balancer: Azure Load Balancer
- Availability: SLA for VM at least 95% - 99.99% of the time . 


2. App services:
- Costs: $0.00 (F1)
- Scalability:
	Autoscaling: Built-in service
	Load balancer: Integrated
- Availability: SLA for VM (subscription will be available 99.95% of the time). No SLA is provided for Apps under either the Free or Shared tiers.

### Choose the appropriate solution (VM or App Service) for deploying the app

I would choose an App Service

### Justify your choice

- The lightweight app tends to be well-suited to App Services. 
- Just have to deploy the code without worrying about the infrastructure. 
- It has conform pricing tiers with scalability.


### Assess app changes that would change your decision.
- The Article CMS (Flask Web Project) app has the need for high-performance compute services.
- Need for custom monitoring strategy for app .