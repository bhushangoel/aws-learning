# Storage

### Amazon EFS

A service for the scalable, elastic and cloud native network file systems is EFS. It lets you connect to the file systems via the network with your linux EC2 servers

* It is a fully managed service which provides NFS(Network File System) shared file system storage for the linux virtual machines in EC2.
* NFS is a protocol that allows you to access files and directories that aren’t on your system but connected your network.
* Because in case of large amount of data, it is not possible to analyze that data on s3, so in that case data must be stored on the machines doing the actual analysis.
* Multiple servers can access the EFS file system at the same time. Thousands of machines can connect to the same volume and process the data seamlessly.
* It can automatically grow or shrinks as you add or remove files.
* Encryption is also enabled by default in an EFS file system.

#### Different storage classes

1. Standard
2. Infrequent access

### Amazon FSx

A fully managed file storage built for windows server is Amazon FSx

### Amazon EBS (Block storage)

Easy to use, high performance block storage. This is used by Amazon EC2 to store all its files.

### Amazon S3 (Object storage)

It is an object storage service, so if you have the object ID, you can access the file.

It is very durable which means the service automatically stores copies of the same file in multiple systems across multiple data centers. It is protected against failures, errors and threats.

#### Storage classes in S3

* S3 standard
* S3 standard-infrequent
* S3 one zone-infrequent
*   S3 glacier and S3 glacier deep archive

    * Designed for Long term backup and archival. If there is a use case where we can wait for around 12 to 48 hours to get the files than this is the recommended option.
    * Around $1/TB/month


* S3 intelligent tiering\
  It tries to automatically save money by moving objects between the different access tiers when your usage patterns change
