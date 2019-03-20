# Ad-hoc AWS IAM Policies

This repo is a collection of ad-hoc IAM policies for special use cases.

| Policy Name | Description |
|-------------|-------------|
| Tier1AdminsCreateNewUserOnlyPermissionsBoundary | Constrains what IAM user(s) can do when given IAMFullAccess managed policy. |
| s3-create-bucket-us-east-1-policy               | Prevents users (with exception of special users) the ability to create buckets in specified region. |
| s3-deny-bucket-creation-in-non-us-east-1 | Prevents principals from creating buckets outside of us-east-1. |
| autoscaling-policy | Allows the action autoscaling:CompleteLifecycleAction for dynamic non-persistent launch configuration names that contain spaces |

