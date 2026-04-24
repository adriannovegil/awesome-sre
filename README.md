# Awesome SRE [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

You want your computer systems to run well, and the subjective definition of what well means depends on the nature of the system and your goals regarding it.

Most of the time, the primary motivation for companies is to create profit for the owners and shareholders.

The definition of running well will therefore be a derivative of the business model objectives.

> "Hope is not a strategy."

## Contents

- [1. Site Reliability Engineering](#1-site-reliability-engineering)
- [2. SRE Culture](#2-sre-culture)
- [3. DevOps](#3-devops)
- [4. Monitoring and Observability](#4-monitoring-and-observability)
- [5. Alerting](#5-alerting)
- [6. Incident Response and Post-Mortem](#6-incident-response-and-post-mortem)
- [7. On-Call](#7-on-call)
- [8. Chaos Engineering](#8-chaos-engineering)
- [9. Automation and Toil Reduction](#9-automation-and-toil-reduction)
- [10. Capacity Planning](#10-capacity-planning)
- [11. Runbooks and Playbooks](#11-runbooks-and-playbooks)
- [12. Performance](#12-performance)
- [13. SLOs and SLIs Tools](#13-slos-and-slis-tools)
- [14. Books](#14-books)
- [15. Examples and Sandboxes](#15-examples-and-sandboxes)
- [16. Community and Forums](#16-community-and-forums)
- [17. References](#17-references)
- [18. License](#18-license)
- [19. Contributing](#19-contributing)

## 1. Site Reliability Engineering

- [What is Site Reliability Engineering?](https://landing.google.com/sre/) - Google's foundational page on SRE.
- [SRE Book - Google](https://sre.google/sre-book/table-of-contents/) - Free online version of the original Google SRE book.
- [School of SRE - LinkedIn](https://github.com/linkedin/school-of-sre) - Comprehensive curriculum for onboarding new SREs, covering Linux, networking, databases, and more.
- [How They SRE](https://github.com/upgundecha/howtheysre) - Curated collection of publicly available resources on how technology and tech-savvy organizations practice Site Reliability Engineering.
- [SRE Interview Prep Guide](https://github.com/mxssl/sre-interview-prep-guide) - Comprehensive checklist of topics and resources to prepare for SRE interviews.
- [Awesome SRE Cheatsheets](https://github.com/michael-kehoe/awesome-sre-cheatsheets) - Collection of cheatsheets for various SRE tools and practices.

## 2. SRE Culture

- [SRE vs DevOps: What's the Difference?](https://cloud.google.com/blog/products/devops-sre/sre-vs-devops-competing-standards-or-close-friends) - Google Cloud blog post explaining the relationship between SRE and DevOps.
- [Building Reliable Systems with SRE - Google](https://sre.google/resources/) - Collection of talks, articles, and case studies about SRE culture and practices.
- [Blameless Post-Mortems](https://sre.google/sre-book/postmortem-culture/) - Chapter from the Google SRE book on creating a blameless post-mortem culture.
- [Love DevOps? Wait until you meet SRE](https://www.atlassian.com/it-unplugged/devops/site-reliability-engineering-sre) - Atlassian's take on the relationship between SRE and DevOps culture.
- [What is the role of a Site Reliability Engineer?](https://cloudacademy.com/blog/what-is-the-role-of-a-site-reliability-engineer/) - Overview of the SRE role and responsibilities.

## 3. DevOps

- [The Phoenix Project](https://itrevolution.com/product/the-phoenix-project/) - A novel about IT, DevOps, and helping your business win.
- [DORA Metrics](https://dora.dev/) - Research program that identifies the capabilities that drive software delivery and operations performance.
- [DevOps Roadmap](https://roadmap.sh/devops) - Community-driven roadmap for DevOps practitioners.
- [Accelerate: State of DevOps](https://cloud.google.com/devops) - Google Cloud's annual State of DevOps report and resources.
- [The DevOps Handbook](https://itrevolution.com/product/the-devops-handbook-second-edition/) - Practical guide for implementing DevOps in any organization.

## 4. Monitoring and Observability

<!--lint ignore double-link-->
- [My Awesome Observability Repo ;-)](https://github.com/adriannovegil/awesome-observability)
- [Prometheus](https://prometheus.io/) - Open source monitoring system and time series database, the de facto standard for cloud-native monitoring.
- [Grafana](https://grafana.com/oss/grafana/) - Open source analytics and interactive visualization web application for dashboarding.
- [OpenTelemetry](https://opentelemetry.io/) - Collection of APIs, SDKs, and tools for instrumenting, generating, collecting, and exporting telemetry data.
- [Datadog](https://www.datadoghq.com/) - Unified monitoring and security platform for metrics, traces, and logs.
- [Nagios](https://www.nagios.com/) - Comprehensive IT infrastructure monitoring software application.

## 5. Alerting

<!--lint ignore double-link-->
- [My Awesome Observability Repo ;-)](https://github.com/adriannovegil/awesome-observability)
- [Prometheus Alertmanager](https://github.com/prometheus/alertmanager) - Handles alerts sent by Prometheus server, deduplicating, grouping, and routing them to the correct receiver.
- [Grafana OnCall](https://grafana.com/oss/oncall/) - Open source incident response and on-call management tool that integrates with Grafana.
- [Sloth](https://github.com/slok/sloth) - Easy and simple Prometheus SLO (service level objectives) generator for alerts.
- [Moira](https://github.com/moira-alert) - Real-time alerting system, backed by Graphite, designed to be independent of any monitoring solution.

## 6. Incident Response and Post-Mortem

- [A collection of post-mortems](https://github.com/danluu/post-mortems) - Curated collection of post-mortems from various companies and incidents.
- [A collection of postmortem templates](https://github.com/dastergon/postmortem-templates) - Collection of templates for writing effective post-mortems.
- [Our incident postmortem template](https://www.hostedgraphite.com/blog/incident-postmortem-template) - Hosted Graphite postmortem template.
- [Postmortem exercise](https://docs.google.com/document/d/1ob0dfG_gefr_gQ8kbKr0kS4XpaKbc0oVAk4Te9tbDqM/edit) - Google's postmortem exercise document.
- [incident.io](https://incident.io/) - Incident management platform that helps teams respond, communicate, and learn from incidents directly within Slack.
- [Squadcast](https://www.squadcast.com) - SRE platform for incident management, on-call scheduling, and reliability workflows.
- [PagerDuty](https://www.pagerduty.com/) - Digital operations management platform for real-time incident response.
- [Splunk On-Call](https://www.splunk.com/en_us/investor-relations/acquisitions/splunk-on-call.html) - On-call and incident response tool by Splunk, formerly known as VictorOps.
- [OpsGenie](https://www.opsgenie.com/) - On-call and alert management to keep services always on.
- [AlertOps](https://alertops.com/) - Transforms real-time operational intelligence into automated incident response.
- [Blameless](https://www.blameless.com/) - SRE platform for incident management, retrospectives, and reliability insights.
- [OnPage](https://www.onpage.com/) - Incident alert management system with a secure smartphone app for response teams.
- [PagerTree](https://pagertree.com/) - Intelligent alert routing for the modern team.
- [Cabot](https://cabotapp.com/) - Get alerted when services go down or metrics go crazy.
- [xMatters](https://www.xmatters.com/) - Service reliability platform to automate operations workflows.
- [Derdack Enterprise Alert](https://www.derdack.com/) - Enterprise alert notification software.
- [Bigpanda](https://www.bigpanda.io/) - AIOps event correlation and automation platform.
<!--lint ignore double-link-->
- [OpenDuty](https://github.com/ustream/openduty) - __(Deprecated)__ Open source incident escalation tool similar to PagerDuty, no longer maintained.
- [ngDesk](https://www.ngdesk.com/) - All-in-one application that includes support, sales, asset management, marketing and pager.
- [Geneos](https://www.itrsgroup.com/products/geneos) - Real-time monitoring for all your environments in one platform.
- [FireHydrant](https://www.firehydrant.com) - Tools for service catalogs, incident response, status pages, and retrospectives.
- [Rootly](https://www.rootly.io) - Incident management platform with automated workflows and Slack integration.

## 7. On-Call

- [Grafana OnCall](https://grafana.com/oss/oncall/) - Open source on-call management tool with calendar integration, escalation chains, and ChatOps.
- [PagerDuty On-Call](https://www.pagerduty.com/platform/on-call-management/) - Automated scheduling, escalation policies, and on-call reporting.
- [Being On-Call - Google SRE Book](https://sre.google/sre-book/being-on-call/) - Google's guide on on-call best practices and sustainable workloads.
- [Awesome On-Call](https://github.com/upgundecha/howtheysre#on-call) - Collection of articles on how companies handle on-call.

## 8. Chaos Engineering

- [My Awesome Chaos Repo ;-)](https://github.com/adriannovegil/awesome-chaos-engineering)

## 9. Automation and Toil Reduction

- [Eliminating Toil - Google SRE Book](https://sre.google/sre-book/eliminating-toil/) - Chapter on identifying and reducing toil in SRE practice.
- [Rundeck](https://www.rundeck.com/) - Open source runbook automation for incident management, business continuity, and self-service operations.
- [Ansible](https://www.ansible.com/) - Simple, agentless IT automation platform for configuration management, application deployment, and orchestration.
- [Terraform](https://www.terraform.io/) - Infrastructure as Code tool for building, changing, and versioning infrastructure safely and efficiently.
- [Pulumi](https://www.pulumi.com/) - Infrastructure as Code using familiar programming languages like Python, Go, JavaScript, TypeScript, and C#.
- [Shoreline](https://shoreline.io/) - Incident automation platform that enables on-call engineers to debug and repair production issues with real-time automation.
- [StackStorm](https://stackstorm.com/) - Open source event-driven platform for runbook automation, ChatOps, and auto-remediation.

## 10. Capacity Planning

- [Capacity Planning - Google SRE Book](https://sre.google/sre-book/software-engineering-in-sre/) - Google's approach to capacity planning in SRE.
- [Kubernetes Vertical Pod Autoscaler](https://github.com/kubernetes/autoscaler/tree/master/vertical-pod-autoscaler) - Automatically adjusts the amount of CPU and memory requested by pods.
- [Kubernetes Horizontal Pod Autoscaler](https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale/) - Automatically scales the number of pods in a deployment based on observed metrics.
- [KEDA](https://keda.sh/) - Kubernetes Event-driven Autoscaling component that provides fine-grained autoscaling for any container workload.
- [KubeStellar Console](https://github.com/kubestellar/console) - Multi-cluster Kubernetes dashboard with AI-powered operations, real-time observability, and CNCF project integrations across edge and cloud clusters.

## 11. Runbooks and Playbooks

- [Rundeck](https://www.rundeck.com/) - Open source runbook automation for incident management and self-service operations.
- [Google SRE Workbook - Practical Alerting](https://sre.google/workbook/alerting-on-slos/) - Guidelines for writing actionable alerts with associated runbooks.
- [PagerDuty Incident Response Docs](https://response.pagerduty.com/) - Open source documentation covering PagerDuty's incident response process and runbook best practices.
- [Elastic Runbook Automation](https://www.elastic.co/guide/en/observability/current/create-alerts.html) - Guidelines for creating alerting rules with automated response actions.

## 12. Performance

- [Brendan Gregg's Systems Performance](https://www.brendangregg.com/systems-performance-2nd-edition-book.html) - Comprehensive resource on systems performance analysis and tuning.
- [USE Method](https://www.brendangregg.com/usemethod.html) - Utilization, Saturation, and Errors methodology for analyzing the performance of any system.
- [K6](https://k6.io/) - Developer-centric, open-source load testing tool built for making performance testing a productive experience.
- [Locust](https://github.com/locustio/locust) - Easy-to-use, scriptable and scalable performance testing tool written in Python.
- [Gatling](https://gatling.io/) - Load testing tool designed for continuous testing integrated with your development pipeline.
- [Flame Graphs](https://www.brendangregg.com/flamegraphs.html) - Visualization of profiled software, allowing the most frequent code-paths to be identified quickly.

## 13. SLOs and SLIs Tools

- [SLO Generator](https://github.com/google/slo-generator) - Tool by Google to compute and export Service Level Objectives, Error Budgets and Burn Rates using YAML configurations.
- [SLO Computer](https://github.com/last9/slo-computer) - Simplifies computing SLOs, error windows and alerts.
- [SLO Tracker](https://github.com/roshan8/slo-tracker) - A simple but effective way to track SLOs and Error budgets with webhook integration for alerting tools.
- [SLO exporter](https://github.com/seznam/slo-exporter) - Computes standardized SLI and SLO metrics based on events from various data sources.
- [Pyrra](https://github.com/pyrra-dev/pyrra) - Makes SLOs with Prometheus manageable, accessible, and easy to use for everyone.
- [Sloth](https://github.com/slok/sloth) - Easy and simple Prometheus SLO generator.
- [Nobl9](https://www.nobl9.com/) - SLO platform that connects to any data source to provide reliability insights and error budget tracking at enterprise scale.
- [OpenSLO](https://openslo.com/) - Open specification for defining and interfacing with SLOs, allowing for a common, vendor-agnostic approach to reliability tracking.
- [NthLayer](https://github.com/rsionnach/nthlayer) - Reliability requirements as code, generating Grafana dashboards, Prometheus alerts, SLOs, and PagerDuty configs from service.yaml.

## 14. Books

- [Site Reliability Engineering](https://sre.google/sre-book/table-of-contents/) - The original Google SRE book, free to read online.
- [The Site Reliability Workbook](https://sre.google/workbook/table-of-contents/) - Practical companion to the SRE book with actionable examples.
- [Building Secure and Reliable Systems](https://sre.google/books/building-secure-reliable-systems/) - Combines security and reliability practices for designing systems.
- [Implementing Service Level Objectives](https://www.oreilly.com/library/view/implementing-service-level/9781492076803/) - Step-by-step guide to creating SLIs, SLOs, and error budgets by Alex Hidalgo.
- [Seeking SRE](https://www.oreilly.com/library/view/seeking-sre/9781491978856/) - Conversations about running production systems at scale, edited by David N. Blank-Edelman.
- [Observability Engineering](https://www.oreilly.com/library/view/observability-engineering/9781492076438/) - Practical approach to achieving observability in distributed systems by Charity Majors, Liz Fong-Jones, and George Miranda.
- [Chaos Engineering](https://www.oreilly.com/library/view/chaos-engineering/9781492043850/) - System resiliency in practice by Casey Rosenthal and Nora Jones.

## 15. Examples and Sandboxes

<!--lint ignore double-link-->
- [Observability Sandbox](https://github.com/adriannovegil/observability-sandbox) - Get up and running with Prometheus, Thanos, Grafana, and more using Docker and Docker Compose.
- [School of SRE](https://github.com/linkedin/school-of-sre) - LinkedIn's comprehensive self-study curriculum covering fundamentals to advanced SRE topics.
- [SRE University](https://github.com/andrealmar/sre-university) - Curated list of courses and resources for learning SRE.
- [Google SRE Resources](https://sre.google/resources/) - Official Google resources including talks, blog posts, and case studies.
- [Operate First](https://github.com/operate-first/SRE) - Community-driven SRE practices for open source cloud operations.

## 16. Community and Forums

- [SREcon](https://www.usenix.org/srecon) - USENIX conference dedicated to Site Reliability Engineering.
- [CNCF TAG Observability](https://github.com/cncf/tag-observability) - CNCF Technical Advisory Group for observability topics.
- [Google SRE Resources](https://sre.google/resources/) - Official talks, blog posts, and educational content from Google SRE teams.
- [SRE Weekly](https://sreweekly.com/) - Weekly newsletter curating the best SRE news and articles.
- [Awesome SRE](https://github.com/dastergon/awesome-sre) - A curated list of awesome Site Reliability and Production Engineering resources.

## 17. References

- https://github.com/dastergon/awesome-sre
- https://github.com/michael-kehoe/awesome-sre-cheatsheets
- https://github.com/andrealmar/sre-university
- https://github.com/awesome-sre/awesome-sre
- https://github.com/jdrowne/awesome-sre-books
- https://github.com/hekonsek/awesome-sre
- https://github.com/mterwill/awesome-sre
- https://github.com/operate-first/SRE
- https://github.com/SquadcastHub/awesome-sre-tools
- https://github.com/mxssl/sre-interview-prep-guide
- https://github.com/rishiloyola/SRE-Interviews
- https://github.com/unixorn/sysadmin-reading-list
- https://github.com/linkedin/school-of-sre
- https://github.com/upgundecha/howtheysre
- [Site Reliability Engineering - Rodolpho Eckhardt](https://www.youtube.com/watch?v=XI2zUFIsMwg)
- [Site Reliability Engineering at Dropbox](https://www.youtube.com/watch?v=ggizCjUCCqE)
- [Site Reliability Engineering](https://landing.google.com/sre/)

## 18. License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

## 19. Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

Thank you!
