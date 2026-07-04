---
title: "Week 12 Worklog"
date: 2026-01-01
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

### Week 12 Objectives:

* Complete the ZeroBug Agent system deployment on AWS.
* Perform comprehensive system testing and evaluate overall performance.
* Optimize the Serverless architecture and resolve remaining issues.
* Finalize the Workshop documentation and internship report.
* Prepare presentation materials and project acceptance documentation.

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
<td>1</td>
<td>
• Review the entire ZeroBug Agent source code.<br>
• Verify the Backend project structure and all AWS Lambda Functions.<br>
• Review Environment Variables configured for each Lambda Function.<br>
• Evaluate IAM permissions among AWS Lambda, Amazon S3, Amazon RDS, AWS Step Functions, and Amazon Bedrock.<br>
• Standardize AWS resource naming conventions for easier management and maintenance.<br>
• Update the system architecture documentation according to the deployed implementation.
</td>
<td>06/07/2026</td>
<td>06/07/2026</td>
<td>AWS Documentation, Project Documents</td>
</tr>

<tr>
<td>2</td>
<td>
• Perform comprehensive System Testing.<br>
• Verify the complete workflow:<br>
&nbsp;&nbsp;+ User uploads a project.<br>
&nbsp;&nbsp;+ Backend receives the request.<br>
&nbsp;&nbsp;+ Amazon SQS receives the message.<br>
&nbsp;&nbsp;+ Lambda Trigger starts AWS Step Functions.<br>
&nbsp;&nbsp;+ Workflow executes Lambda Functions.<br>
&nbsp;&nbsp;+ Amazon Bedrock generates Unit Tests.<br>
&nbsp;&nbsp;+ Amazon S3 stores generated results.<br>
&nbsp;&nbsp;+ Amazon RDS stores execution history.<br>
&nbsp;&nbsp;+ Backend returns results to the user interface.<br>
• Validate data accuracy throughout every processing stage.<br>
• Record remaining issues for further improvement.
</td>
<td>07/07/2026</td>
<td>07/07/2026</td>
<td>AWS Documentation, ZeroBug Agent</td>
</tr>

<tr>
<td>3</td>
<td>
• Monitor the entire system using Amazon CloudWatch.<br>
• Review CloudWatch Logs for each Lambda Function.<br>
• Monitor Execution History in AWS Step Functions.<br>
• Analyze Retry, Timeout, and Exception events during execution.<br>
• Optimize Lambda Memory Size and Timeout settings to improve performance.<br>
• Verify the system's capability to process multiple consecutive requests.
</td>
<td>08/07/2026</td>
<td>08/07/2026</td>
<td>AWS CloudWatch Documentation</td>
</tr>

<tr>
<td>4</td>
<td>
• Evaluate system performance using multiple projects of different sizes.<br>
• Test Java, Python, and .NET projects.<br>
• Compare processing time for different project types.<br>
• Verify reading data from Amazon S3 and storing results in Amazon RDS.<br>
• Evaluate AWS resource utilization during processing.<br>
• Record performance metrics for future optimization.
</td>
<td>09/07/2026</td>
<td>09/07/2026</td>
<td>AWS Performance Monitoring</td>
</tr>

<tr>
<td>5</td>
<td>
• Finalize the project's technical documentation.<br>
• Update the deployed Serverless architecture diagram.<br>
• Complete the AWS Step Functions Workflow diagram.<br>
• Add detailed descriptions for each AWS Lambda Function.<br>
• Finalize the AWS deployment guide.<br>
• Verify consistency between documentation and the deployed system.
</td>
<td>10/07/2026</td>
<td>10/07/2026</td>
<td>Project Documentation</td>
</tr>

<tr>
<td>6</td>
<td>
• Prepare the Workshop presentation materials.<br>
• Collect screenshots captured during system implementation.<br>
• Prepare illustrations for:<br>
&nbsp;&nbsp;+ AWS Lambda<br>
&nbsp;&nbsp;+ Amazon SQS<br>
&nbsp;&nbsp;+ AWS Step Functions<br>
&nbsp;&nbsp;+ Amazon Bedrock<br>
&nbsp;&nbsp;+ Amazon CloudWatch<br>
&nbsp;&nbsp;+ Amazon S3<br>
&nbsp;&nbsp;+ Amazon RDS<br>
• Prepare presentation content describing the Serverless architecture and Unit Test generation workflow.<br>
• Rehearse the presentation and refine the content.
</td>
<td>11/07/2026</td>
<td>11/07/2026</td>
<td>Workshop Materials</td>
</tr>

<tr>
<td>7</td>
<td>
• Perform the final system verification.<br>
• Compare implemented features with the original project requirements.<br>
• Verify the stability of the AWS Serverless workflow.<br>
• Remove unused AWS resources to avoid unnecessary charges.<br>
• Summarize all internship activities and achievements.<br>
• Finalize the internship report, worklog, and Workshop documentation.<br>
• Prepare all documents required for the project defense and acceptance.
</td>
<td>12/07/2026</td>
<td>12/07/2026</td>
<td>Project Documentation</td>
</tr>

</tbody>
</table>

### Week 12 Achievements:

* Successfully completed the ZeroBug Agent system based on a Serverless architecture on AWS.
* Successfully tested the complete workflow from user request submission to automatic Unit Test generation.
* Optimized AWS Lambda, AWS Step Functions, and Amazon SQS configurations to improve system performance and reliability.
* Successfully completed result storage on Amazon S3 and execution history management on Amazon RDS.
* Monitored and evaluated the system using Amazon CloudWatch Logs and AWS Step Functions Execution History.
* Finalized all technical documentation, architecture diagrams, Workshop materials, and internship report.
* Removed unused AWS resources to optimize operational costs.
* Successfully completed all internship objectives while gaining valuable experience in Serverless architecture, AWS services, and Generative AI for automated Unit Test generation.