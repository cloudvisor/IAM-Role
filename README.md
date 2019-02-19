# Cloudvisor integration IAM Role

Connecting your AWS account will enable Cloudvisor to automate cost optimization tasks on your behalf.

Cloudvisor does not store any private keys, passwords, or authentication tokens.
The authentication is made based on the [IAM Cross Account Role](https://docs.aws.amazon.com/IAM/latest/UserGuide/tutorial_cross-account-with-roles.html) alog with External ID that provides two-factor authentication.

Our integration IAM-Role gives us read-only access to your billing and the metadata about the running resources in your AWS account.
We never access any of your company or customer’s data.

For more information regarding our security policies and complience, please visit https://www.cloudvisor.io/security-overview

