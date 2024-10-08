# Docker Compose with AWS

1. Login to your AWS account:
   - Go to [AWS Console](https://aws.amazon.com/console/).
   - Enter your **Account ID**, **IAM User**, and **Password**.

2. Open the **EC2 Dashboard**:
   - Navigate to **Services** and select **EC2** under the **Compute** section.

3. Click on **Launch Instance**.

4. Configure your instance:
   - **Name**: Set the instance name to `nimap`.
   - **Amazon Machine Image (AMI)**: Select **Ubuntu** as the operating system.
   - **Instance Type**: Choose **t2.micro** (this is eligible for the free tier).
   
5. Under **Key Pair (login)**, create or select a key pair for SSH access (if needed).

6. In the **Network settings**:
   - Select the **default security group**, which typically allows SSH (port 22) access from any IP.

7. Click **Launch Instance** to create the instance.

8. Once the instance is created, you’ll see the new EC2 instance named `nimap` in your dashboard.

   ![image](https://github.com/user-attachments/assets/5a33441a-4fcd-451a-bce9-980c896c499f)
