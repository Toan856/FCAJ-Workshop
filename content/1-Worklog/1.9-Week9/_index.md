---
title: "Week 9 Worklog"
date: 2026-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Week 9 Objectives:

* Begin deploying the AWS infrastructure for the ZeroBug Agent system.
* Learn and configure AWS Lambda, Amazon SQS, and AWS Step Functions.
* Build the Serverless processing workflow based on the designed architecture.
* Prepare the environment for the system implementation workshop.
* Verify connectivity between AWS services before integrating them into the project.

### Tasks to be carried out this week:

<table class="worklog-table">
<colgroup>
  <col class="col-day" style="width:5%">
  <col class="col-task" style="width:42%">
  <col class="col-start" style="width:13%">
  <col class="col-end" style="width:13%">
  <col class="col-ref" style="width:27%">
</colgroup>
<thead>
<tr>
<th>Day</th>
<th>Task</th>
<th>Start Date</th>
<th>Completion Date</th>
<th>Reference Material</th>
</tr>
</thead>

<tbody>

<tr>
<td class="col-day">1</td>
<td class="col-task">
- Review the Serverless architecture designed in the previous week.<br>
- Prepare AWS account and verify access to AWS Lambda, Amazon SQS, AWS Step Functions and Amazon Bedrock.<br>
- Create IAM Roles for Lambda Execution and Step Functions Execution.<br>
- Configure IAM Policies for S3, RDS, CloudWatch and Bedrock access.
</td>
<td class="col-date">15/06/2026</td>
<td class="col-date">15/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">2</td>
<td class="col-task">
- Study AWS Lambda and the Function as a Service (FaaS) model.<br>
- Prepare the development environment using Visual Studio Code and AWS Toolkit.<br>
- Create the first Lambda Function.<br>
- Deploy and test the Lambda Function through AWS Console and monitor execution using CloudWatch Logs.
</td>
<td class="col-date">16/06/2026</td>
<td class="col-date">16/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">3</td>
<td class="col-task">
- Learn Amazon Simple Queue Service (Amazon SQS).<br>
- Create a Standard Queue for Unit Test generation requests.<br>
- Send and receive test messages.<br>
- Review Queue properties including Visibility Timeout, Message Retention and Dead-Letter Queue.
</td>
<td class="col-date">17/06/2026</td>
<td class="col-date">17/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">4</td>
<td class="col-task">
- Learn AWS Step Functions.<br>
- Design the workflow including request processing, project import, source code analysis, Amazon Bedrock invocation, result storage and history recording.<br>
- Create the first State Machine.<br>
- Test the workflow using sample input.
</td>
<td class="col-date">18/06/2026</td>
<td class="col-date">18/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">5</td>
<td class="col-task">
- Develop Lambda Functions for each processing stage.<br>
- Create Context Builder, Source File Service, AI Invoke Service, Result Service and History Service.<br>
- Configure Runtime and Environment Variables.<br>
- Test each Lambda Function independently.
</td>
<td class="col-date">19/06/2026</td>
<td class="col-date">19/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">6</td>
<td class="col-task">
- Integrate AWS Step Functions with Lambda Functions.<br>
- Configure Task States, Input and Output parameters.<br>
- Add Retry and Catch mechanisms.<br>
- Monitor execution history and validate data flow.
</td>
<td class="col-date">20/06/2026</td>
<td class="col-date">20/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">7</td>
<td class="col-task">
- Test the complete Serverless workflow.<br>
- Send sample requests through Amazon SQS.<br>
- Verify Lambda execution and Step Functions workflow.<br>
- Monitor CloudWatch Logs and optimize the workflow.<br>
- Update the workshop documentation.
</td>
<td class="col-date">21/06/2026</td>
<td class="col-date">21/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

</tbody>
</table>

### Week 9 Achievements:

* Successfully prepared the AWS environment for the ZeroBug Agent project.
* Configured IAM Roles and IAM Policies for AWS Lambda and AWS Step Functions.
* Developed Lambda Functions for the processing workflow.
* Created and configured Amazon SQS for asynchronous processing.
* Designed and deployed the first Serverless workflow using AWS Step Functions.
* Successfully integrated Amazon SQS, AWS Lambda and AWS Step Functions.
* Validated the basic processing workflow and monitored execution using Amazon CloudWatch Logs.
* Completed the environment and documentation required for integrating Amazon Bedrock in the following stages.