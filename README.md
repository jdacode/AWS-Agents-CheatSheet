
# AWS-Agents-CheatSheet

<br><br>

## AWS Agents


| Agents | Description | Area |
|-|-|-|
| **Amazon Inspector agent** | The Amazon Inspector agent is an entity that collects installed package information and software configuration for an Amazon EC2 instance. Though not required in all cases, you should install the Amazon Inspector agent on each of your target Amazon EC2 instances in order to fully assess their security. | Security |
| **Amazon CloudWatch agent** | <br> Collect internal system-level metrics from Amazon EC2 instances across operating systems. The metrics can include in-guest metrics, in addition to the metrics for EC2 instances. The additional metrics that can be collected are listed in Metrics Collected by the CloudWatch Agent. <br> Collect system-level metrics from on-premises servers. These can include servers in a hybrid environment as well as servers not managed by AWS. <br> Retrieve custom metrics from your applications or services using the StatsD and collectd protocols. StatsD is supported on both Linux servers and servers running Windows Server. collectd is supported only on Linux servers. <br> Collect logs from Amazon EC2 instances and on-premises servers, running either Linux or Windows Server.  | EC2 |
| **AWS Systems Manager Agent** | AWS Systems Manager Agent (SSM Agent) is Amazon software that can be installed and configured on an EC2 instance, an on-premises server, or a virtual machine (VM). SSM Agent makes it possible for Systems Manager to update, manage, and configure these resources. The agent processes requests from the Systems Manager service in the AWS Cloud, and then runs them as specified in the request. SSM Agent then sends status and execution information back to the Systems Manager service by using the Amazon Message Delivery Service (service prefix: ec2messages). | Systems |
| **CodeDeploy agent** | The CodeDeploy agent is a software package that, when installed and configured on an instance, makes it possible for that instance to be used in CodeDeploy deployments. | Code | 
| **AWS DataSync agent** | AWS DataSync is an online data transfer service that simplifies, automates, and accelerates moving data between on-premises storage systems and AWS storage services, and also between AWS storage services. DataSync can copy data between Network File System (NFS), Server Message Block (SMB) file servers, self-managed object storage, AWS Snowcone, Amazon Simple Storage Service (Amazon S3) buckets, Amazon EFS file systems, and Amazon FSx for Windows File Server file systems. <br>   | Data |
| **Amazon Kinesis Agent** | Kinesis Agent is a stand-alone Java software application that offers an easy way to collect and send data to Kinesis Data Streams. The agent continuously monitors a set of files and sends new data to your stream. The agent handles file rotation, checkpointing, and retry upon failures. It delivers all of your data in a reliable, timely, and simple manner. It also emits Amazon CloudWatch metrics to help you better monitor and troubleshoot the streaming process. | Kinesis Stream |


<br><br>

## License

> Licensed under the [MIT](license) license.