---
title: "Week 11 Worklog"
date: 2026-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Week 11 Objectives

* Integrate all components of the ZeroBug Agent system.
* Test the Unit Test generation workflow on AWS.
* Complete the integration between the Backend and AWS Serverless services.
* Monitor, troubleshoot, and optimize system performance.
* Prepare documentation and implementation results for the Workshop report.

### Tasks to be carried out this week

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
<td>1</td>
<td>
- Review the overall ZeroBug Agent architecture after completing AWS Lambda Functions and AWS Step Functions.<br>
- Verify the connection between the Backend API and Amazon SQS.<br>
- Test the request flow from the user interface to the Backend.<br>
- Validate input data before sending it to Amazon SQS.<br>
- Verify the JSON payload format exchanged between system components.<br>
- Finalize the workflow documentation.
</td>
<td>06/29/2026</td>
<td>06/29/2026</td>
<td>Workshop Documents, AWS Documentation</td>
</tr>

<tr>
<td>2</td>
<td>
- Integrate the Backend with Amazon SQS.<br>
- Test sending Unit Test generation requests from the Web interface.<br>
- Monitor message processing within Amazon SQS.<br>
- Verify the Lambda Trigger for processing queue messages.<br>
- Verify the execution of AWS Step Functions after receiving requests.<br>
- Evaluate the stability of the asynchronous processing workflow.
</td>
<td>06/30/2026</td>
<td>06/30/2026</td>
<td>Workshop Documents, AWS Documentation</td>
</tr>

<tr>
<td>3</td>
<td>
- Test the AWS Step Functions workflow with multiple datasets.<br>
- Monitor Workflow Execution History.<br>
- Verify data transfer between Task States.<br>
- Test the following Lambda Functions:<br>
&nbsp;&nbsp;+ Project Import<br>
&nbsp;&nbsp;+ Context Builder<br>
&nbsp;&nbsp;+ Source File Service<br>
&nbsp;&nbsp;+ AI Invoke Service<br>
&nbsp;&nbsp;+ Result Service<br>
&nbsp;&nbsp;+ History Service<br>
- Record execution issues and apply necessary adjustments.
</td>
<td>07/01/2026</td>
<td>07/01/2026</td>
<td>Workshop Documents, AWS Documentation</td>
</tr>

<tr>
<td>4</td>
<td>
- Test Unit Test generation using Amazon Bedrock Claude 3 Haiku.<br>
- Evaluate Java, Python, and .NET project analysis capabilities.<br>
- Assess the quality of generated Unit Tests.<br>
- Refine Prompt Templates to improve output accuracy.<br>
- Compare results from multiple executions.<br>
- Record processing time for each request.
</td>
<td>07/02/2026</td>
<td>07/02/2026</td>
<td>Workshop Documents, AWS Documentation</td>
</tr>

<tr>
<td>5</td>
<td>
- Verify the storage of generated Unit Tests in Amazon S3.<br>
- Verify processing history stored in Amazon RDS.<br>
- Compare data consistency between Amazon S3, Amazon RDS, and the Backend.<br>
- Test history retrieval from the system.<br>
- Remove obsolete testing data.<br>
- Evaluate data integrity after storage.
</td>
<td>07/03/2026</td>
<td>07/03/2026</td>
<td>Workshop Documents, AWS Documentation</td>
</tr>

<tr>
<td>6</td>
<td>
- Monitor the entire system using Amazon CloudWatch.<br>
- Review CloudWatch Logs for each AWS Lambda Function.<br>
- Analyze Timeout, Exception, and Retry events.<br>
- Adjust Lambda Timeout and Memory Allocation to improve performance.<br>
- Review IAM Roles and permissions among AWS services.<br>
- Record optimization results.
</td>
<td>07/04/2026</td>
<td>07/04/2026</td>
<td>Workshop Documents, AWS Documentation</td>
</tr>

<tr>
<td>7</td>
<td>
- Perform end-to-end testing of the complete system.<br>
- Verify the complete workflow:<br>
&nbsp;&nbsp;+ User uploads a project.<br>
&nbsp;&nbsp;+ Backend sends a request to Amazon SQS.<br>
&nbsp;&nbsp;+ AWS Step Functions orchestrates the workflow.<br>
&nbsp;&nbsp;+ Amazon Bedrock generates Unit Tests.<br>
&nbsp;&nbsp;+ Amazon S3 stores the generated results.<br>
&nbsp;&nbsp;+ Amazon RDS stores processing history.<br>
&nbsp;&nbsp;+ Backend returns results to the user.<br>
- Evaluate overall system performance.<br>
- Summarize resolved issues and completed tasks.<br>
- Update technical documentation and finalize the Workshop materials.
</td>
<td>07/05/2026</td>
<td>07/05/2026</td>
<td>Workshop Documents, AWS Documentation</td>
</tr>

</tbody>
</table>

### Week 11 Achievements

* Successfully integrated the Backend API with AWS Serverless services for the ZeroBug Agent system.
* Completed end-to-end testing of the Unit Test generation workflow.
* Successfully integrated Amazon SQS, AWS Lambda, AWS Step Functions, Amazon Bedrock, Amazon S3, and Amazon RDS.
* Monitored and resolved system issues using Amazon CloudWatch Logs and AWS Step Functions Execution History.
* Optimized AWS Lambda configurations to improve performance and reduce execution time.
* Evaluated the quality of Unit Tests generated by Amazon Bedrock Claude 3 Haiku and refined Prompt Templates for better accuracy.
* Completed testing documentation and updated the Workshop implementation materials according to the project schedule.
* Prepared the environment and documentation for the final implementation, acceptance, and project presentation phase.