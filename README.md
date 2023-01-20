# Delivery-Verification-Templates

## Delivery Verification for Argo Rollouts

[Argo Rollouts](https://argoproj.github.io/rollouts/) enables advanced deployment capabilities such as blue-green, canary, experimentation, and progressive delivery features to Kubernetes.

[OpsMx Intelligent Software Delivery](https://www.opsmx.com/isd-platform/isd-for-argo/) (ISD) platform integrates with Argo Rollout to enable automated verification of deployments to reduce the risk of rolling out bad releases to production.

ISD automates rollout verification with intelligence using machine learning algorithms and leverages Natural Language Processing (NLP) and Statistical analysis to identify risks in new releases compared to the base releases. 

To set up verification for your application, see [Getting Started with Automated Verification of Argo Rollouts](https://docs.opsmx.com/opsmx-intelligent-software-delivery-isd-platform-argo/user-guide/delivery-verification) 

## Delivery Verification Templates
ISD integrates with the most commonly available log and metrics monitoring tools to perform the analysis during rollout. 

Delivery Verification Templates are ConfigMaps that help ISD to identify the following
* From where to retrieve the data - Monitoring tools and accounts (credentials) used for the analysis.
* What data needs to be retrieved - Log and metric data that are relevant to the application.
* Advanced configurations - Custom business logic to process the logs and criticality of certain metrics over others.


Choose from the below tools to get a list of available templates 

* [DataDog](/Datadog)
* [ElasticSearch](/ElasticSearch)
* [NewRelic](/NewRelic)
* [Prometheus](/Prometheus)
* [Splunk](/Splunk)
* [StackDriver](/StackDriver)
