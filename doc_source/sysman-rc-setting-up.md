# Setting Up Run Command<a name="sysman-rc-setting-up"></a>

Before you can manage instances by using Run Command, you must configure an AWS Identity and Access Management \(IAM\) user policy for any user who will run commands, and an IAM instance profile role for any instance that will process commands\. For more information, see [Setting Up AWS Systems Manager](systems-manager-setting-up.md)\. 

This section also includes recommended tasks for monitoring command executions and restricting command access to tagged instances\. The tasks in this section are not required, but they can help minimize the security posture and day\-to\-day management of your instances\. For this reason, we highly recommend you complete the tasks in this section\.

**Topics**
+ [Configuring Amazon CloudWatch Logs for Run Command](sysman-rc-setting-up-cwlogs.md)
+ [Configuring CloudWatch Events for Run Command](rc-cwe.md)
+ [Restricting Run Command Access Based on Instance Tags](sysman-rc-setting-up-cmdsec.md)