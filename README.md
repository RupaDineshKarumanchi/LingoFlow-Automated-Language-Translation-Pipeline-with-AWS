# LingoFlow-Automated-Language-Translation-Pipeline-with-AWS
LingoFlow is a serverless application that enables seamless real-time voice translation across multiple languages.
It leverages AWS cloud services to process spoken input, translate it into the desired language, and generate natural-sounding audio output.

The entire pipeline is automated using AWS Step Functions, orchestrating multiple AWS Lambda functions for a smooth, scalable, and efficient translation workflow.

# Features
1. 🎤 Voice-to-Text – Converts speech to text using Amazon Transcribe.
2. 🌍 Language Translation – Translates text to the target language using Amazon Translate.
3. 🔊 Text-to-Speech – Generates speech output using Amazon Polly.
4. ⚡ Serverless Orchestration – Fully automated with AWS Step Functions and AWS Lambda.
5. ☁ Scalable & Cost-Effective – Pay only for what you use with AWS serverless infrastructure.

![Blank diagram](https://github.com/user-attachments/assets/d717ff6f-d794-4009-855b-6fc9bd11a5c7)

# Services Used:

1. AWS S3 – Storage for input/output audio and intermediate files.
2. AWS Step Functions – Workflow automation and orchestration.
3. AWS Lambda – Custom processing for each step.
4. AWS Transcribe – Speech-to-text processing.
5. AWS Translate – Multilingual text translation.
6. AWS Polly – Text-to-speech synthesis.
7. AWS IAM – Secure permissions and access control.
8. AWS CloudWatch – Monitoring, logging, and debugging.

# Deployment

# Prerequisites
AWS account with required services enabled.
AWS CLI configured locally.
IAM roles with permissions for S3, Lambda, Step Functions, Transcribe, Translate, Polly, and CloudWatch.

# Steps
1. Clone Repository
   
2. Deploy Lambda Functions
Use AWS SAM or Serverless Framework to package and deploy functions.

3. Create Step Function Workflow
Define the state machine in AWS Step Functions to orchestrate Lambda functions.

4. Configure S3 Triggers
Set up S3 event triggers to start the workflow upon file upload.
