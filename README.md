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
| **General Purpose Instances** | Balanced compute, memory, and networking resources.       | Web servers, app servers, and small to medium databases.      | [AWS - General Purpose Instances](https://aws.amazon.com/ec2/instance-types/general-purpose/)                       |
| **Compute Optimized Instances**| High-performance processors, ideal for compute-bound applications. | Compute-bound applications, gaming servers, and scientific modeling. | [AWS - Compute Optimized Instances](https://aws.amazon.com/ec2/instance-types/compute-optimized/)         |
| **Memory Optimized Instances** | High memory-to-CPU ratio, suitable for memory-intensive applications. | In-memory databases, real-time big data analytics, and large-scale SAP HANA. | [AWS - Memory Optimized Instances](https://aws.amazon.com/ec2/instance-types/memory-optimized/)           |
| **Accelerated Computing Instances** | Hardware accelerators or co-processors for tasks like GPU or FPGA. | Machine learning, graphics processing, and data compression.  | [AWS - Accelerated Computing Instances](https://aws.amazon.com/ec2/instance-types/accelerated-computing/) |
| **Storage Optimized Instances** | High, low-latency storage capacity.                        | NoSQL databases, data warehousing, and distributed file systems. | [AWS - Storage Optimized Instances](https://aws.amazon.com/ec2/instance-types/storage-optimized/)   |

This classification allows users to choose instances tailored to their specific workload requirements, ensuring optimal performance and cost-effectiveness.

![ec2-instance-types-in-aws](https://github.com/mandikgoyal/AWS_Incident_Response/assets/37402196/516cd35d-3857-4292-9915-bbbe08a6f34a)


## 🌐 Sources
1. [Amazon EC2 Instance Types - AWS](https://aws.amazon.com/ec2/instance-types/)
2. [Amazon EC2 Instance Types - Documentation](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-types.html)
3. [AWS EC2 Instance Types Explained](https://cloudacademy.com/blog/aws-ec2-instance-types-explained/)
4. [Choosing the Right EC2 Instance Type for Your Application](https://aws.amazon.com/blogs/aws/choosing-the-right-ec2-instance-type-for-your-application/)
5. [AWS EC2 Instance Types: Comparison and Use Cases](https://www.msp360.com/resources/blog/ec2-instance-types/)
6. [Amazon EC2 Instance Types (AWS China)](https://www.amazonaws.cn/en/ec2/instance-types/)
