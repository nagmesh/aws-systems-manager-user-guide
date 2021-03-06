# AWS\-StopEC2Instance<a name="automation-aws-stopec2instance"></a>

**Description**

Stop one or more Amazon EC2 instances\.

**Document Type**

Automation

**Owner**

Amazon

**Platforms**

Windows, Linux

**Parameters**
+ AutomationAssumeRole

  Type: String

  Description: \(Optional\) The ARN of the role that allows Automation to perform the actions on your behalf\.
+ InstanceId

  Type: StringList

  Description: \(Required\) IDs of one or more Amazon EC2 instances to stop

**Examples**

Start the automation

```
aws ssm start-automation-execution --document-name AWS-StopEC2Instance --parameters parameters
```

Retrieve the execution output

```
aws ssm get-automation-execution --automation-execution-id EXECUTIONID --output text --query 'AutomationExecution.Output'
```

**Document Steps**

aws:changeInstanceState

aws:changeInstanceState

**Outputs**

None