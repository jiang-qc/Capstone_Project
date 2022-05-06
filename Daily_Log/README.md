# Daily Log

## 5.2 Jigsaw Activity

- Maximizing Collective Intelligence: the shared or group intelligence that emerges from the collaboration, collective efforts, and competition of many individuals and appears in consensus decision
making
- Trust: assured reliance on the character, ability, strength, or truth of someone or something
- Forms of conflicts:
  1. Task Conflict: a disagreement over the goal or objective of a project/discussion/meeting
  2. Relationship Conflict: the conflict resulting from either personality clashes or 
negative emotional interactions between two or more people
  3. Process Conflict: a disagreement over how to achieve the goal
 
- Team Emotional Intelligence: the ability to identify and manage one's own emotions, as well as other people's emotions
- Psychological Safety: a belief that you won’t be punished when you make a mistake


## 5.3 Conception to Deployment + Coding Challenge Day

Useful tools in teamwork:
Git 
Logging
Documentation
Internal: use python docstrings
External: customer-facing / developer-facing / auto-docs


Containerized deployment:
Docker: package and run an application in an isolated environment called a container
Kubernetes: a portable, extensible, open source platform for managing containerized workloads and services
BanzaiCloud: 
Deployment: define the structure of the pod
Service: exposes applications running on pods as a network service. Pods are dynamic. The service creates a stable connection to one or multiple pods.
Ingress: manages external access to services in a cluster.


CI/CD:
Continuous integration
Commit your changes regularly
Share code with other developers so that everything is compatible
Automates tests and builds to find problems early
linting , checking for merge conflicts, building in dev

Continuous delivery
Builds on foundations of build and test automation from CI
Automate the steps leading up to production.


## 5.4 Team Contract and EDA

- The data is structured but umbalanced. We might need to do some preprocessing and cleaning.
- Another concern is the bias behind the data because the responses from strudents are subjective.
- When training data, the features might be corelated. To achieve a better performance, random forest models might be better than regression models.
- Jungyeul proposed to use transformer because we are dealing with text data. Neural networks might performs better. 
