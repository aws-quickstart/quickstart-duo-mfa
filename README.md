# quickstart-duo-mfa
## Duo MFA for AWS Directory Service on AWS

This Quick Start automatically deploys Duo multi-factor authentication (MFA) for AWS Directory Service on the Amazon Web Services (AWS) Cloud in about 10 minutes. The Quick Start uses the Duo [Authentication Proxy](https://duo.com/docs/authproxy-reference) for AWS Directory Service to gain MFA functionality.

This Quick Start is for those who currently use or intend to use AWS Directory Service directory types such as AWS Directory Service for Microsoft Active Directory (also known as AWS Managed Microsoft AD) or Active Directory Connector (AD Connector), and who want to apply MFA in a highly available, secure implementation.

Duo MFA mitigates the threat of compromised credentials caused by phishing, malware, and other security threats, reducing risk while meeting compliance requirements for access security.

If you use a federation mechanism like AWS Single Sign-On (AWS SSO) or Active Directory Federation Services (AD FS) with a Directory Service option, you configure your own MFA. Using Duo MFA, you log in to the AWS Management Console, and then use Duo authentication methods including Duo Push through [Duo Mobile](https://duo.com/product/trusted-users/two-factor-authentication/duo-mobile), and your Active Directory credentials to authenticate to AWS.

![Quick Start architecture for Duo MFA for AWS Directory Service on AWS](https://d1.awsstatic.com/partner-network/QuickStart/datasheets/duo-mfa-architecture-on-aws.ab5438682f2f9d902f882159bc590063df81c98a.png)

For architectural details, best practices, step-by-step instructions, and customization options, see the [deployment guide](https://fwd.aws/n7wKB).

To post feedback, submit feature ideas, or report bugs, use the **Issues** section of this GitHub repo.

If you'd like to submit code for this Quick Start, please review the [AWS Quick Start Contributor's Kit](https://aws-quickstart.github.io/).
