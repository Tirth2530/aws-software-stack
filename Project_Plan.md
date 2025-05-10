# Project Plan – Work Breakdown Structure (WBS)

1. Set up Raspberry Pi cluster and K3s nodes
2. Configure AWS IoT Core and device job triggering
3. Create shell script and job YAML to run distributed tasks
4. Store outputs in AWS S3 and configure IAM
5. Set up CloudWatch logging and monitoring

```mermaid
graph TD
  A[Cluster Setup] --> B[AWS IoT Job Config]
  B --> C[Job Scripts + K3s YAML]
  C --> D[Upload to S3]
  D --> E[CloudWatch Monitoring]
