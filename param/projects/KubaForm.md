# KubaForm

### Problem Statement:
- EKS is pricy
- EKS is overwhelming
- EKS PRICING IS OVERWHELMING

To manage simple kubernetes workflow we just need with 3-4 nodes to be created in which our cluster could run!

Presenting... a templatized kubernetes deployment which auto-configures EC2 instances as master and worker nodes where kubeadm and other tools are automatically installed!!

Need to run a quick workflow? Just `terraform apply` and you're ready to go.

Done with your learning for the day? Want to save AWS costs? `terraform destroy` and it will de-provision everything.

No need to setup your own rig, or learn EKS... Just simply work with pre-configured tools (available as part of User Data Scripts) you need to explore the world of kubernetes.

> It also helps you **SAVE MONEY**. See a detailed comparison of how Kubaform helps you save operational costs over standard EKS clusters in [Pricing Estimates](https://github.com/akaparam/kubaform/blob/main/docs/pricing-estimates.md).

The current configuration deploys the following architecture in AWS:

![KubaForm: Minified](https://github.com/akaparam/kubaform/blob/main/docs/assets/kf-lab.svg)

Now to provision these components the following terraform resources were defined in each module (generated with `terraform graph` rendered by `eraser.io`):

![KubaForm: Resource Map](https://github.com/akaparam/kubaform/blob/main/docs/assets/kf-lab-graph.svg)

## Documentation

Find detailed documentation visit the repository.

**GitHub URL**: https://github.com/akaparam/kubaform.git