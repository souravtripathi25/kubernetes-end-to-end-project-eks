# IAM notes

No keys or secrets are stored in this repo.

The AWS Load Balancer Controller policy is downloaded from the official project:

```bash
curl -O https://raw.githubusercontent.com/kubernetes-sigs/aws-load-balancer-controller/v2.11.0/docs/install/iam_policy.json
```

Use the policy version that matches your controller version, otherwise you will hit `AccessDenied` errors (see the troubleshooting section in the main README).
