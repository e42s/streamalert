# Stream Alert Kinesis Event Terraform Module

* This Terraform module configures a AWS Lambda function to read events from a speecific Kinesis Stream.

## Inputs
<table>
  <tr>
    <th>Property</th>
    <th>Description</th>
    <th>Default</th>
    <th>Required</th>
  </tr>
  <tr>
    <td>lambda_role_id</td>
    <td>The AWS IAM Role ID attached to the Lambda function</td>
    <td>None</td>
    <td>True</td>
  </tr>
  <tr>
    <td>lambda_production_enabled</td>
    <td>Enable/Disable this event source mapping</td>
    <td>None</td>
    <td>True</td>
  </tr>
  <tr>
    <td>lambda_function_arn</td>
    <td>The ARN of the Lambda function to read from Kinesis</td>
    <td>None</td>
    <td>True</td>
  </tr>
  <tr>
    <td>kinesis_stream_arn</td>
    <td>The ARN of the Kinesis Stream</td>
    <td>None</td>
    <td>True</td>
  </tr>
  <tr>
    <td>role_policy_prefix</td>
    <td>The prefix string for AWS IAM roles</td>
    <td>None</td>
    <td>False</td>
  </tr>
</table>

## Outputs
None