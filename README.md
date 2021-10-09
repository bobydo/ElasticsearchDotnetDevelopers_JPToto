# DotnetCoreAWSDynamodb_DanielDonbavand
-  https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/authentication-and-access-control.html Use role 


-  SQL VS No SQL
![image](https://user-images.githubusercontent.com/64368109/132951396-9101d53f-7192-4b58-a240-05e588315b39.png)

![image](https://user-images.githubusercontent.com/64368109/132951516-3456c3f0-ba47-4909-9160-c37a74adf095.png)

-  No SQL Type<br>
https://phoenixnap.com/kb/nosql-database-types

-  Concepts: Primary Key, Sort Key, Combined Primary + Sort Key, Secondary index for search data column
![image](https://user-images.githubusercontent.com/64368109/136462717-e2433307-2750-47c0-9f4a-89e3d9ae3df7.png)

-  Read and Write capacity related to cost
![image](https://user-images.githubusercontent.com/64368109/136463910-a7d3742c-b337-4d02-8290-1f13189a96ce.png)

-  .NET Core coding <br>
![image](https://user-images.githubusercontent.com/64368109/136465587-0e82996e-8b5d-45b8-a802-ab7d8a2e295f.png)

-  Install AWS CLI msiexec.exe /i https://awscli.amazonaws.com/AWSCLIV2.msi
-  aws configure
![image](https://user-images.githubusercontent.com/64368109/136471604-c7673ae0-0609-4db7-88a3-b91ad505d4ef.png)

```
Hi Daniel, thank you for providing us this course.
After I worked on retrieving all movies, I got "ResourceNotFoundException: Requested resource not found: Table: MovieRank not found" error. As my understanding, you used "aws configure" CLI to save credential to "C:\Users\[username]\.aws\" But in "credentials.txt", I could see Table name "MovieRank" where do you define the table name in code? or some guide for troubleshooting?

I have "MovieRank" table with 1 record.

here is my repository with .net 5 core upgrade.https://github.com/bobydo/DotnetCoreAWSDynamodb_DanielDonbavand/tree/main/04

I am making a prototype, could you please let me know ASAP?

Thanks lots!

Shenyi

[default]
aws_access_key_id = xxx
aws_secret_access_key = xxx
region = us-west-2
toolkit_artifact_guid=xxx
```

-  Object persistent vs document model <br>
https://docs.aws.amazon.com/en_us/sdk-for-net/v3/ndg/web-dynamodb-programming-models.html
