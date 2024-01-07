# AWS_EC2_Incident_Response
Notes Related to AWS_Incident_Response

[AWS Incident Response](https://docs.aws.amazon.com/whitepapers/latest/aws-security-incident-response-guide/aws-security-incident-response-guide.html)

# Cloud Computing Essentials

| Topic                                     | Description                               |
|-------------------------------------------|-------------------------------------------|
| Introduction to Cloud Computing           | Overview of cloud computing principles.   |
| Shared Security Responsibility model      | Understanding the shared security model in cloud environments. |
| Cloud Computing Basics                    | Fundamentals of cloud computing.          |
| Creating AWS Account                      | Steps to create an AWS account.           |
| Incident Response in Cloud                | Strategies for incident response in cloud computing. |

These topics provide foundational knowledge for understanding and working with cloud computing services, specifically in the context of AWS.

Feel free to explore each topic to gain a comprehensive understanding of cloud computing essentials.

 ### Types of EC2
 # Amazon EC2 Instance Types Overview

| Instance Type               | Description                                              | Use Cases                                                    | Sources                                                                                                                                               |
|-----------------------------|----------------------------------------------------------|--------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **General Purpose Instances** | Balanced compute, memory, and networking resources.       | Web servers, app servers, and small to medium databases.      | [AWS - General Purpose Instances](https://aws.amazon.com/ec2/instance-types/general-purpose/) [[1](https://aws.amazon.com/ec2/instance-types/)]                        |
| **Compute Optimized Instances**| High-performance processors, ideal for compute-bound applications. | Compute-bound applications, gaming servers, and scientific modeling. | [AWS - Compute Optimized Instances](https://aws.amazon.com/ec2/instance-types/compute-optimized/) [[1](https://aws.amazon.com/ec2/instance-types/)]          |
| **Memory Optimized Instances** | High memory-to-CPU ratio, suitable for memory-intensive applications. | In-memory databases, real-time big data analytics, and large-scale SAP HANA. | [AWS - Memory Optimized Instances](https://aws.amazon.com/ec2/instance-types/memory-optimized/) [[1](https://aws.amazon.com/ec2/instance-types/)]            |
| **Accelerated Computing Instances** | Hardware accelerators or co-processors for tasks like GPU or FPGA. | Machine learning, graphics processing, and data compression.  | [AWS - Accelerated Computing Instances](https://aws.amazon.com/ec2/instance-types/accelerated-computing/) [[1](https://aws.amazon.com/ec2/instance-types/)] |
| **Storage Optimized Instances** | High, low-latency storage capacity.                        | NoSQL databases, data warehousing, and distributed file systems. | [AWS - Storage Optimized Instances](https://aws.amazon.com/ec2/instance-types/storage-optimized/) [[1](https://aws.amazon.com/ec2/instance-types/)]     |

This classification allows users to choose instances tailored to their specific workload requirements, ensuring optimal performance and cost-effectiveness.

## 🌐 Sources
1. [Amazon EC2 Instance Types - AWS](https://aws.amazon.com/ec2/instance-types/)
2. [Amazon EC2 Instance Types - Documentation](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-types.html)
3. [AWS EC2 Instance Types Explained](https://cloudacademy.com/blog/aws-ec2-instance-types-explained/)
4. [Choosing the Right EC2 Instance Type for Your Application](https://aws.amazon.com/blogs/aws/choosing-the-right-ec2-instance-type-for-your-application/)
5. [AWS EC2 Instance Types: Comparison and Use Cases](https://www.msp360.com/resources/blog/ec2-instance-types/)
6. [Amazon EC2 Instance Types (AWS China)](https://www.amazonaws.cn/en/ec2/instance-types/)


Amazon EC2 provides a diverse range of instance types, each optimized to meet specific use cases. Here's an overview of the main EC2 instance types:

1. **General Purpose Instances:**
   - *Description:* Balanced compute, memory, and networking resources.
   - *Use Cases:* Web servers, app servers, and small to medium databases.
   - *Sources:* [AWS - General Purpose Instances](https://aws.amazon.com/ec2/instance-types/general-purpose/)

2. **Compute Optimized Instances:**
   - *Description:* High-performance processors, ideal for compute-bound applications.
   - *Use Cases:* Compute-bound applications, gaming servers, and scientific modeling.
   - *Sources:* [AWS - Compute Optimized Instances](https://aws.amazon.com/ec2/instance-types/compute-optimized/)

3. **Memory Optimized Instances:**
   - *Description:* High memory-to-CPU ratio, suitable for memory-intensive applications.
   - *Use Cases:* In-memory databases, real-time big data analytics, and large-scale SAP HANA.
   - *Sources:* [AWS - Memory Optimized Instances](https://aws.amazon.com/ec2/instance-types/memory-optimized/)

4. **Accelerated Computing Instances:**
   - *Description:* Hardware accelerators or co-processors to perform functions such as graphics processing (GPU) or floating-point number calculations (FPGA).
   - *Use Cases:* Machine learning, graphics processing, and data compression.
   - *Sources:* [AWS - Accelerated Computing Instances](https://aws.amazon.com/ec2/instance-types/accelerated-computing/)

5. **Storage Optimized Instances:**
   - *Description:* High, low-latency storage capacity.
   - *Use Cases:* NoSQL databases, data warehousing, and distributed file systems.
   - *Sources:* [AWS - Storage Optimized Instances](https://aws.amazon.com/ec2/instance-types/storage-optimized/)

This classification allows users to choose instances tailored to their specific workload requirements, ensuring optimal performance and cost-effectiveness.

## 🌐 Sources
1. [Amazon EC2 Instance Types - AWS](https://aws.amazon.com/ec2/instance-types/)
2. [Amazon EC2 Instance Types - Documentation](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-types.html)
3. [AWS EC2 Instance Types Explained](https://cloudacademy.com/blog/aws-ec2-instance-types-explained/)
4. [Choosing the Right EC2 Instance Type for Your Application](https://aws.amazon.com/blogs/aws/choosing-the-right-ec2-instance-type-for-your-application/)
5. [AWS EC2 Instance Types: Comparison and Use Cases](https://www.msp360.com/resources/blog/ec2-instance-types/)
6. [Amazon EC2 Instance Types (AWS China)](https://www.amazonaws.cn/en/ec2/instance-types/)
