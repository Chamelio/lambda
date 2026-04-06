1) Terraform Templates – Reusable Skeleton
1.1. Base module pattern (per lab)

Instructions

“Each lab = one Terraform root with a modules/serverless_app module.
Fork this skeleton and wire the specific resources for each lab.”

Root main.tf:
Root variables.tf:
Root outputs.tf:


1.2. Example module for a typical lab (Lab 1 / Lab 2 structure)

Sample:
modules/serverless_app/sample_main.tf:

You can add/remove S3/SQS/SNS/EventBridge rules per lab but reuse this structure.
Remember: “clone Lab 1’s TF, then modify resources per lab design.”

