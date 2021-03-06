# Enable Access to AWS Applications and Services<a name="simple_ad_manage_apps_services"></a>

AWS Directory Service can give other AWS applications and services, such as Amazon WorkSpaces, access to your directory users\. The following AWS applications and services can be enabled or disabled to work with AWS Directory Service:

Amazon WorkSpaces  
You can create a Simple AD, AWS Managed Microsoft AD, or AD Connector directly from Amazon WorkSpaces\. Simply launch **Advanced Setup** when creating your Workspace\.  
For more information, see the [Amazon WorkSpaces Administration Guide](http://docs.aws.amazon.com/workspaces/latest/adminguide/)\.

Amazon WorkSpaces Application Manager  
For more information, see the [Amazon WAM Administration Guide](http://docs.aws.amazon.com/wam/latest/adminguide/)\.

Amazon WorkDocs  
For more information, see the [Amazon WorkDocs Administration Guide](http://docs.aws.amazon.com/workdocs/latest/adminguide/)\.

Amazon WorkMail  
For more information, see the [Amazon WorkMail Administrator Guide](http://docs.aws.amazon.com/workmail/latest/adminguide/)\.

Amazon Relational Database Service  
For more information, see the [Amazon Relational Database Service User Guide](http://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/)\.

AWS Management Console  
For more information, see [Enable Access to the AWS Management Console with AD Credentials](ms_ad_management_console_access.md)\.

Once enabled, you manage access to your directories in the console of the application or service that you want to give access to your directory\. To find the AWS applications and services links described above in the AWS Directory Service console, perform the following steps\.

**To display the applications and services for a directory**

1. In the [AWS Directory Service console](https://console.aws.amazon.com/directoryservice/) navigation pane, choose **Directories**\.

1. Choose the directory ID link for your directory\.

1. Choose the **Apps & Services** tab\. 

**Topics**
+ [Creating an Access URL](simple_ad_create_access_url.md)
+ [Single Sign\-On](simple_ad_single_sign_on.md)