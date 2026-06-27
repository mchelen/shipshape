# Problem Statement 
How might we automate all standard aspects of the software development lifecycle?

# Why

The intention of this repo is to provide a fully templated software factory that can be cloned and reused for any software development. 

# What

All aspects of software development lifecycle should be accounted for including: 
- Understanding user needs
- Creating user stories
- Defining implementation plan
- Executing implementation 
- Performing QA testing
- Creating releases and deployments
- Monitoring application health and status
- Understanding usage and collecting feedback

# How

For each aspect of software development, an agent is created with the task of performing that function. 
The agent is provided with default best practices, and actively works across planning artifacts, repository codebase, and user commands to carry out the approach.

# Examples

- Business Analyst agent provides questions to the users, allowing understanding of the use cases and goals. 
- DevSecOps agent configures CI/CD pipelines, including static and dynamic code analysis, creation of releases, deployment to lower environments or feature branches, and promotion to higher environments.
- SRE agent that configures and implements observability, including logging, monitoring, and alerting. Defines incident response plan, escalation path, and performs postmortem incident analysis and remediation.
