# EventBridge + Lambda Auto-Remediation

**Real-time security actions. Triggered. Enforced. Resolved.**

This Terraform module sets up a CloudTrail-integrated EventBridge rule and connects it to a Lambda function that remediates public S3 bucket exposure instantly.

---

## ✅ Features

- Detects public ACL or policy changes on S3  
- Auto-triggers remediation Lambda  
- Prevents human-error-based misconfigurations  
- CloudTrail event-based security logic  
- Plug-and-play remediation pattern

---

## ☁️ Tech Stack

- **Cloud**: AWS  
- **IaC**: Terraform  
- **Security Services**: Lambda, EventBridge, CloudTrail, S3

---

## 🚀 Usage Example

```hcl
module "auto_remediation" {
  source = "./modules/eventbridge_lambda_auto_remediation"
}
```

🧠 **Note**: Upload your zipped Lambda function to `lambda/remediate_s3.zip` (Python script that removes public ACLs or blocks policies).

---

### [Deploy Real-Time Remediation →](https://opscontractordev.super.site)

> Want access to the full Terraform deployment code?  
> Request private access at [your email] or through [your Super site].


*Generated on 2025-05-22 by The Contractor.*
