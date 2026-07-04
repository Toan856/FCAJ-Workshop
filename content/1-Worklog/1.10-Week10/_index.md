---
title: "Week 10 Worklog"
date: 2026-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 Objectives:

* Continue deploying the ZeroBug Agent system on AWS.
* Complete AWS Lambda Functions for the Unit Test generation workflow.
* Integrate Amazon Bedrock Claude 3 Haiku into the system.
* Finalize the AWS Step Functions workflow and connect it with Amazon SQS.
* Test the complete Serverless processing workflow.

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
- Review the Serverless architecture of the ZeroBug Agent system.<br>
- Verify deployed Lambda Functions.<br>
- Standardize the project structure.<br>
- Configure Environment Variables and review IAM Roles and Policies.<br>
- Prepare sample data for workflow testing.
</td>
<td class="col-date">22/06/2026</td>
<td class="col-date">22/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">2</td>
<td class="col-task">
- Complete the Lambda Project Import Service.<br>
- Receive Git repositories or ZIP files.<br>
- Clone repositories or extract project files.<br>
- Upload source code to Amazon S3.<br>
- Validate metadata and uploaded data.
</td>
<td class="col-date">23/06/2026</td>
<td class="col-date">23/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">3</td>
<td class="col-task">
- Complete the Lambda Context Builder.<br>
- Analyze project structures.<br>
- Detect programming languages (Java, Python, .NET).<br>
- Collect metadata and standardize outputs.<br>
- Test with multiple sample projects.
</td>
<td class="col-date">24/06/2026</td>
<td class="col-date">24/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">4</td>
<td class="col-task">
- Complete the Lambda Source File Service.<br>
- Read source files from Amazon S3.<br>
- Filter unnecessary folders and files.<br>
- Prepare data for Amazon Bedrock.<br>
- Evaluate processing performance.
</td>
<td class="col-date">25/06/2026</td>
<td class="col-date">25/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">5</td>
<td class="col-task">
- Complete the Lambda AI Invoke Service.<br>
- Integrate Amazon Bedrock Runtime.<br>
- Configure Claude 3 Haiku.<br>
- Build Prompt Templates.<br>
- Evaluate generated Unit Test quality.
</td>
<td class="col-date">26/06/2026</td>
<td class="col-date">26/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">6</td>
<td class="col-task">
- Complete the Lambda Result Service.<br>
- Store generated Unit Tests in Amazon S3.<br>
- Complete the Lambda History Service.<br>
- Store execution history in Amazon RDS.<br>
- Monitor CloudWatch Logs and validate stored data.
</td>
<td class="col-date">27/06/2026</td>
<td class="col-date">27/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

<tr>
<td class="col-day">7</td>
<td class="col-task">
- Finalize the AWS Step Functions workflow.<br>
- Connect all Lambda Functions.<br>
- Configure Retry, Catch and Timeout policies.<br>
- Connect Amazon SQS with Lambda Trigger.<br>
- Perform End-to-End testing and update workshop documentation.
</td>
<td class="col-date">28/06/2026</td>
<td class="col-date">28/06/2026</td>
<td class="col-ref">AWS Documentation</td>
</tr>

</tbody>
</table>

### Week 10 Achievements:

* Completed all AWS Lambda Functions required for the Unit Test generation workflow.
* Successfully integrated Amazon Bedrock Claude 3 Haiku.
* Built a complete AWS Step Functions Serverless workflow.
* Successfully connected Amazon SQS with AWS Lambda and AWS Step Functions.
* Stored generated Unit Tests in Amazon S3 and execution history in Amazon RDS.
* Successfully completed End-to-End workflow testing.
* Monitored system execution using Amazon CloudWatch Logs and Step Functions Execution History.
* Completed most workshop materials, providing a solid foundation for system optimization in the following weeks.