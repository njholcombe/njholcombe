## Howdy

- 🔭 Repository Details:
- public_architecture repository: A centralized repository for architectural documentation, diagrams, and conceptual overviews that explain the structure and design of projects maintained in my private repositories.
-  PythonProjects_priv repository: Holds all PyOpAnalytics application code.
-  lakehouse repository (private): AWS data lakehouse framework implementing a reusable job orchestration layer and a job factory pattern. The architecture leverages Lambda handlers built on shared Python layers, with DynamoDB serving as the control plane.
   This design enables rapid onboarding of both batch and Kinesis-based streaming workloads through metadata-driven configuration rather than custom code per job.
-  aws-celltower-pipeline repository (private): batch job for the datalake (EventBridge, Step Functions, Lambda, S3, Athena), SageMaker consumes silver/curated data, learns patterns, and produces ML artifacts related to outliers, coverage modeling, and tower stability.
-  fcc-asr-pipeline repository (private):resuable monthly batch job for the datalake (eventbridge, stepfunctions, lambda, s3, and Athena)
- These are my newer repos.  All code is private and will require a request for access.  My old repo is here: https://github.com/njh12
