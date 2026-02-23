# CloudCost Optimizer

Automated cloud cost optimization engine with AWS Cost Explorer API, Terraform automation, and predictive scaling for enterprise workloads.

[![Python 3.11](https://img.shields.io/badge/Python-3.11-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![AWS](https://img.shields.io/badge/AWS-Cost--Explorer-FF9900?style=flat&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/)
[![Terraform](https://img.shields.io/badge/Terraform-1.6-7B42BC?style=flat&logo=terraform&logoColor=white)](https://www.terraform.io/)
[![React 18](https://img.shields.io/badge/React-18-61DAFB?style=flat&logo=react&logoColor=black)](https://reactjs.org/)

## Overview

CloudCost Optimizer is an intelligent cost management platform that connects to AWS Cost Explorer, analyzes spending patterns with ML-driven forecasting, generates actionable right-sizing recommendations, and automates Terraform changes to reduce cloud bills by an average of 30-40%.

## Key Features

- **Cost Anomaly Detection**: Automated spike detection using statistical models on AWS Cost Explorer data.
- **Right-Sizing Recommendations**: Analyzes EC2, RDS, and Lambda utilization to suggest optimal instance types.
- **Terraform Automation**: Generates and applies Terraform change sets for approved resource modifications.
- **Predictive Forecasting**: ML-based cost forecasting with 30/60/90-day projections using Prophet.
- **Executive Dashboard**: Budget tracking, cost-by-service breakdown, and savings ROI reporting in React.

## Tech Stack

- **Backend**: Python (FastAPI), AWS SDK (Boto3).
- **ML/Forecasting**: Prophet, Scikit-learn, Pandas.
- **Infrastructure-as-Code**: Terraform, AWS CDK.
- **Frontend**: React.js, Recharts, Tailwind CSS.
- **Deployment**: AWS Lambda (scheduled jobs), DynamoDB (state), CloudWatch.

## Project Structure

```text
├── cost-analyzer/         # Python service using AWS Cost Explorer API
├── recommendation-engine/ # ML-based right-sizing models
├── terraform-generator/   # Automated Terraform plan generation
├── optimizer-dashboard/   # React frontend for cost visibility
└── infrastructure/        # AWS CDK deployment stacks
```

## License

MIT License. See [LICENSE](LICENSE) for details.
